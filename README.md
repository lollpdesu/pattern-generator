# Pattern Generator

**Design seamless vector patterns in your browser and export them as clean SVG or PNG in real-world sizes.**

A single, self-contained HTML file. You don't need to install anything, the app has no dependencies, and it works offline.

[**▶ Open the app in your browser**](https://lollpdesu.github.io/pattern-generator/) &nbsp;·&nbsp; [**Download the latest release**](../../releases/latest)

---

## Patterns

| | |
|---|---|
| **Voronoi** | Organic cells from random or hand-placed seeds, with density maps and relaxing |
| **Delaunay** | Triangulation of the same seeds |
| **Polygon** | One regular polygon, sized CAD-style by side length, inner radius or outer radius |
| **Hexagon** | Honeycomb grid, pointy or flat |
| **Squares** | Straight grid or 45° diamonds |
| **Brick** | Any brick ratio and row offset |
| **Random tiles** | Squares mixed with long pieces |
| **Dots** | Offset, square or hex arrangement |
| **Triangles** | Curved triangles on a triangular grid |
| **Flower** | Petals on every grid edge |
| **Arcs** | Interlaced circle arcs |
| **Al Bahar façade** | The "breathing" façade with uniform, linear, radial, wave, ripple or noise opening, plus a live animation |

## Features

**Seamless tiling.** Make any pattern tile on X, Y or both, with a live tile preview. The *Regular cells* fit adjusts the width or height so the cells keep their shape.

**Exact sizes.** Work in px, mm, cm or m and type values to any precision. With mm, cm or m, the matching cylinder diameter and radius appear under the canvas size. That helps when you wrap a pattern around a round object.

**Shape and style.**
- Gap, straight or rounded corners, holes, grid offset, rotation (with an on-canvas gizmo) and stretch on X and Y.
- Fills from random palettes, linear or radial gradients, density maps, cell size or a single color, with color variation, strokes, edges and a background.

**Polygon tool.** Live measurements (side, inner and outer radius and diameter, perimeter, area, angle), dash-dot construction circles, corner radius, and a button that fits the canvas to the polygon.

**Export.**
- SVG with real units (`width="200mm"`) and optional Inkscape layers.
- PNG at 1×, 2×, 4× or 8× (mm, cm and m are converted at 96 dpi).
- Seed coordinates as JSON or CSV.

**Workflow.** Presets, undo and redo (80 steps), projects saved and opened as JSON (drag and drop works too), and auto-save in the browser.

## Getting started

1. [Open the app online](https://lollpdesu.github.io/pattern-generator/), or download `pattern-generator.html` from the [latest release](../../releases/latest) and open it in Chrome, Edge or Firefox.
2. Pick a pattern, set the canvas size and unit, and turn on **Seamless** if you need it.
3. Export from the **EXPORT** tab or with <kbd>Ctrl</kbd>+<kbd>S</kbd>.

Your settings are saved in the browser automatically. Use **EXPORT → PROJECT → Save JSON** to keep a project as a file.

## Keyboard shortcuts

| Key | Action |
|---|---|
| <kbd>G</kbd> | Generate |
| <kbd>R</kbd> | Relax (Voronoi) |
| <kbd>F</kbd> | Fit the canvas to the view |
| <kbd>0</kbd> | Show at real size (1:1) |
| <kbd>1</kbd> – <kbd>4</kbd> | Tools: add, move, remove, rotate |
| <kbd>Space</kbd> + drag, or right / middle drag | Pan |
| Mouse wheel | Zoom |
| <kbd>Ctrl</kbd>+<kbd>Z</kbd> / <kbd>Ctrl</kbd>+<kbd>Y</kbd> | Undo / redo |
| <kbd>Ctrl</kbd>+<kbd>S</kbd> | Save SVG |

## Feedback & bugs

Found a bug or have an idea for a new pattern? [**Open an issue →**](../../issues/new/choose)

- **Bug report:** what happened, steps to reproduce, and ideally a screenshot or your project JSON (EXPORT tab → PROJECT → Save JSON).
- **Feature request:** new patterns, settings or export options. Reference images help a lot.

## License

[MIT](LICENSE). You're free to use, change and share it, including commercially. Patterns you create with the app are yours.

The "Counter-Strike" display font (by SoJa) embedded in the app for headings belongs to its author and is not covered by this license.
