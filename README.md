# BuilderPlus v0.3.0 (WIP)
⚠️ **Work in Progress** — This mod is under active development. Expect bugs and missing features.

Replaces the vehicle editor UI in Kitten Space Agency with a KSP2-style interface.

## Features

### UI
- Parts catalogue with category sidebar (Font Awesome icons) and search bar
- Vertical toolbar with icons (translate, rotate, scale, snap, connect, radial symmetry, stages, symmetry)
- Sequence panel with category icons per part
- Launch panel with body/location selection (locations filter by selected body)
- Rounded corners and dark theme throughout
- Removed "Simulation Paused" alert in VAB

### Parts & Building
- Vertical rocket orientation — parts spawn upright like KSP
- Click-to-grab parts (no need to hold click)
- Camera auto-centers on first part placement and when moving root part
- Delete parts by clicking the catalogue while holding a part
- Save and load vehicles with delete option

### Keyboard Shortcuts
| Key     | Action |
|---------|--------|
| Delete  | Remove selected part |
| R       | Toggle radial symmetry |
| X       | Cycle symmetry (next) |
| Shift+X | Cycle symmetry (previous) |
| C       | Toggle angle snap |
| V       | Toggle connect |
| W/S     | Rotate part forward/back |
| A/D     | Rotate part left/right (flat) |
| Q/E     | Rotate part left/right |
| Shift+(W/A/S/D/Q/E) | Rotate part 45° instead of 15° |
| Ctrl+Z  | Undo |
| Ctrl+Y  | Redo |
| Scroll  | Pan camera up/down |
| Shift+Scroll | Zoom in/out |

### Gizmos
- Shift+Scale Gizmo scales uniformly on all axes
- Undo/Redo buttons in toolbar

## Known Limitations
- Part rotation shortcuts (W/A/S/D/Q/E) don't work correctly when Snap mode is active

## Planned
- Visual polish
- Drag and drop to arrange stages

## Dependencies
- [StarMap Mod Loader](https://github.com/StarMapLoader/StarMap) >= 0.4.5

## Installation
1. Copy the `BuilderPlus` folder to `KSA/Content/`
2. Add to `manifest.toml`:
```toml
[[mods]]
id = "BuilderPlus"
enabled = true
```
3. Launch via StarMap

## License
MIT