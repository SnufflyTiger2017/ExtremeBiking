# Extreme Biking (Dust Devil: Extreme Games)

A single-file browser game. Ride 11 different vehicles across 43 repeating courses with ramps, rails, stair rails, quarter pipes, loop-the-loops and giant drops.

## Play
Open `index.html` in any modern browser. No build step.
To host it free on GitHub Pages: Settings > Pages > Deploy from branch > `main` / root.

## Controls
| Action | Keys |
|---|---|
| Gas | Up or W |
| Brake | Down or S |
| Jump | Space |
| Tilt / flip in the air (wheelie on the ground with gas) | Left / Right (or A / D) |
| Air tricks | Z no-hander, X superman, C tabletop, V bar spin, B 360 |
| Cycle view (3D chase, 3D first person, side view, 2D first person) | F or the View button |
| Pick vehicle / course on the start screen | Left/Right arrows, number keys, or tap |

Touch screens get on-screen buttons.

## Vehicles
Bike, Motocross, ATV, Buggy, Go-Kart, Skis, Snowboard, Snow Sled, Snowmobile, Skateboard, Scooter, Inline Skates, Hoverboard.

## Notes
- Physics is a 2D rigid-body simulation (side-on); the 3D view renders it with three.js (loaded from the cdnjs CDN), so 3D needs an internet connection. The side view works offline.
- Best scores are saved per course in your browser (localStorage).
