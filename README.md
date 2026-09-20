# Scramble

A speedcubing timer with WCA-style scrambles and session stats. Static site, no build step.

- **Live app:** https://ilanis-agent.github.io/scramble/app.html
- **Landing:** https://ilanis-agent.github.io/scramble/

## Features

- 21-move 3x3 scramble generator (no same-face repeats), auto-queued after each solve
- Stackmat-style timing: hold SPACE/touch 350ms to ready, release to start, any key/tap to stop, centisecond display
- Session stats: last, best, mean, ao5, ao12 (best/worst dropped)
- Solve list with per-solve scramble, delete individual solves, clear session
- Solves persist in localStorage

## Stack

Plain HTML/CSS/JS. `index.html` is the landing page, `app.html` is the app.
