# ⏱️ Lap-Time Stopwatch

**A beautiful millisecond-precision stopwatch with lap tracking, fastest/slowest highlighting, and keyboard shortcuts — in a single HTML file.**

No libraries, no build step, no server. Double-click and it runs.

## ✨ Features

- **Millisecond precision** — `MM:SS.cs` readout with drift-free timing (`performance.now()`)
- **Lap tracking** — record unlimited laps, newest first
- **Smart highlights** — fastest lap glows green, slowest glows red
- **Live stats bar** — lap count, fastest, slowest, and average
- **Keyboard shortcuts** — `Space` start/pause · `L` lap · `R` reset
- **Sleek dark UI** — big tabular-numeral display that never jitters

## 🚀 Run it in 30 seconds

1. Open `index.html` in any browser (double-click works — no server needed).
2. Hit **Start**, do a thing, hit **Lap**. Repeat.
3. Watch your fastest/slowest laps light up green and red.

Try the keyboard: hold `Space`... just kidding — tap it to pause, `L` for laps, `R` to reset.

## 🧠 What this project practices

- **Accurate timing** — why `setInterval` alone drifts, and how `performance.now()` + an accumulated bank fixes it
- **State machines** — the running/paused/reset lifecycle of a timer
- **Array ops** — `map`, `reduce`, `Math.min(...spread)` on lap times
- **Keyboard events** — `keydown` shortcuts with `e.preventDefault()` for Space
- **CSS** — `font-variant-numeric: tabular-nums`, gradients, keyframe animations

## 📁 Files

| File | What |
|------|------|
| `index.html` | Everything — markup, styles, and script in one portable file |

*Day 16 · simple build of my daily coding journey.*
