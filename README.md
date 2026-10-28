# Retro_FPS_GCS Assets

Textures and 3D models for [Retro_FPS_GCS](https://github.com/NeuralDrifter/Retro_FPS_GCS)
(Pie3D), kept here so the main project stays small.

| Folder | Contents |
|---|---|
| `textures/` | 1,209 textures (WebP, 256x256 and smaller) in pack folders, e.g. `textures/Horror/Brick/` |
| `models/` | 608 `.glb` models in category folders, e.g. `models/decorations/Dungeon/`, plus `model-sizes.json` (each model's real width and depth in meters) |

The folder layout is the one Retro_FPS_GCS reads from `src/assets/`: copying `textures/` and
`models/` into the project's `src/assets/` makes them appear in the Asset Library.

## License

Everything here is CC0 (public domain). Credits and sources are in
[`textures/README.md`](textures/README.md) and [`models/README.md`](models/README.md);
each pack's original license text is in `textures/<pack>/LICENSE.txt` and
`models/licenses/`.
