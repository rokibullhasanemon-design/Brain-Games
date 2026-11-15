# At-a-Glance Visual Memory Trainer

An interactive, zero-dependency browser application designed to train rapid visual encoding, spatial chunking, and short-term recall through timed flash exercises.

## Key Features

- **4 Cognitive Training Modes:**
  - **Spatial Grid:** Memorize and reconstruct illuminated tile patterns.
  - **Shapes & Colors:** Encode both grid position and object identity (Circle, Triangle, Star, Hexagon).
  - **Number Sequence (Chimp Test):** Track ascending numbers (`1..N`) and uncover them in exact order once masked.
  - **Digit Matrix:** Rapidly chunk and recall multi-digit grids using keyboard or on-screen numpad input.
- **Customizable Difficulty:** Switch between `3×3`, `4×4`, `5×5`, and `6×6` grids and adjust flash exposure from `1.0s` to `8.0s` (with `1.5s`, `3.0s`, and `5.0s` presets).
- **Quadrant Chunking Guides:** Toggle visual crosshairs to practice grouping dense grids into 4 mental clusters.
- **Blind-Spot Diagnostics:** Automatically detects center vs. peripheral recall drift, overlays dashed ghost outlines on missed targets, and tracks session streak and accuracy.

## Tech Stack

- **HTML5 & Inline SVG** — Semantic structure and crisp scalable vector shapes
- **CSS3** — Dynamic CSS Grid layouts, custom properties, and state animations
- **Vanilla JavaScript (ES6+)** — Finite state machine game loop, Fisher-Yates shuffling, and coordinate-based error analysis

## Getting Started

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/at-a-glance-trainer.git
