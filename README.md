# 🦕 Dino Finder

A browser-based 3D dinosaur exploration game built with Three.js. Roam a blocky voxel forest, track down hidden dinosaurs using a compass, and identify them by keeping them fully in your sights!

## Play

**[Open `index.html` directly in any modern browser — no server or install needed.](https://nebinbiju1.github.io/dino-hunter/)**

## How to Play

| Control | Action |
|---|---|
| `W A S D` | Move |
| Mouse | Look around |
| `Space` | Jump |
| `ESC` | Release mouse |

1. Click the screen to lock your mouse and start exploring.
2. Watch the **compass** (top-left) — it shows the hidden dinosaur's name, direction, and distance.
3. When you get close, a **teal beacon** will pulse above the dinosaur.
4. **Keep the dinosaur fully in view** for 2.5 seconds — the golden ring fills up as you lock on.
5. A fact card pops up with a pixel-art portrait and a fun dinosaur fact!
6. A new dinosaur spawns somewhere in the world after each discovery.

## Dinosaurs

| Dinosaur | Fun Fact |
|---|---|
| 🔴 Tyrannosaurus Rex | Bite force of 12,800 lbs — enough to crush a car |
| 🔵 Triceratops | Had up to 800 teeth and a vivid display frill |
| 🟡 Brachiosaurus | Taller than a 4-story building; front legs longer than back |
| 🟠 Velociraptor | Turkey-sized and feathered in real life! |
| 🟣 Stegosaurus | Brain the size of a walnut; tail spikes called a "thagomizer" |

## Features

- Procedurally generated voxel terrain with grass, dirt, stone, water, and sand
- 180 randomly placed trees with varied canopy shapes
- Drifting clouds and dynamic fog
- Fully 3D block-built dinosaur models with unique colours and details
- 2D pixel-art dino portraits on the fact card
- Directional compass that updates in real time

## Tech

- Vanilla HTML/CSS/JavaScript — zero dependencies except [Three.js r128](https://threejs.org/) (loaded from CDN)
- No build step required
