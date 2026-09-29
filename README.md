# LITS Tetromino Shade Logic Puzzle

Logic puzzle where you shade exactly 4 connected cells per region to form L, I, T, or S tetrominoes while following adjacency rules.

## Features
- 3 hand-crafted puzzles of increasing difficulty (5×5, 6×6, 5×6)
- Visual region borders with amber highlights
- Per-region progress tracker showing shaded count
- Rule checker: detects 2×2 violations and wrong region counts
- Progress saved automatically via localStorage
- Tetromino reference guide in sidebar

## Usage
1. Click a cell to shade/unshade it
2. Each region's number label is shown in the cell
3. Watch the Region Status sidebar to track each area's count
4. Click Check to validate your solution

## Tech
- Tailwind CSS CDN
- Vanilla JS / DOM
- localStorage (per-puzzle progress)
