# Forest Tug-of-War

A single-file HTML5 math game for 7–8 year olds. Two animal teams — **Foxes** and **Bears** — tug on a rope: every correct answer pulls their team one step toward the win.

Developed by **Qwen3.8 27B NVFP4**.

## Play

Just open `forest-tug-of-war.html` in any modern browser (Chrome, Edge, Firefox, Safari).

No installation, no internet connection, no external files — everything (graphics, sound, logic) is in one file.

## How it works

- Solve the problem and tap the correct answer (or use the keyboard).
- A correct answer moves your team **1 step** along the rope; the winning side pulls the rope toward itself.
- First team to pull the red flag **6 steps** to its side wins.
- Wrong answers cost nothing — after **2 mistakes** a **Hint** button appears with a dot-frame (two 5×2 ten-frames; crossed-out dots are subtracted).
- Optional 2-minute timer; if time runs out, the team that pulled more wins (equal pull = draw).

## Controls

| Action | Keys |
|---|---|
| Foxes' answers | `A` / `S` / `D` |
| Bears' answers | `J` / `K` / `L` |
| Pause / resume | `P` |

All buttons work with touch, mouse and keyboard; every touch target is at least 56 px.

## Settings

- **Problems:** Addition / Subtraction / Mixed
- **Difficulty:** Up to 10 / Up to 20 (no carrying) / Up to 20 (with carrying)
- **Match length:** No time limit / Two minutes
- **Options:** Sound / Reduced motion / Big numbers

The game also respects the system "reduce motion" setting automatically.

## Extras

- The animals **react with their faces**: they smile when they pull the rope correctly, frown on a mistake, celebrate (with confetti) when they win, and sweat when they lose. In a draw both teams celebrate.
- Full-screen button (where the browser supports it).
- Fully accessible: ARIA labels and live announcements for screen readers.

## File

| File | Description |
|---|---|
| `forest-tug-of-war.html` | the complete game (single file, offline) |

## License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
