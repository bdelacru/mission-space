# 🚀 Mission: Red Planet

A 3D browser game where you plan, build and fly a mission to Mars. Made for the **NASA Space Apps Challenge** (middle/high school track).

**▶ Play it:** https://bdelacru.github.io/mission-space/

## What you do
1. **Meet the crew.** Talk to a planetary scientist, a spacecraft engineer, a launch-pad firefighter and a flight surgeon. Each one teaches a real space fact and quizzes you for bonus funding.
2. **Build your spacecraft.** Choose a launch vehicle, engine, fuel tanks, hull, power source, antenna, science instrument and spare parts. Set your fin and steering-thruster angles. Stay inside your budget, mass limit and power budget.
3. **Plan the launch.** Pick a launch tilt angle (gravity turn), then find the Earth–Mars launch window (Mars about 44° ahead of Earth).
4. **Fly to Mars.** Steer through meteoroids, boost, grab fuel and spare parts, and repair hull damage. A meter tracks your progress from Earth to Mars.
5. **Mission report.** Get a score and a debrief that explains how your engineering choices played out.

## Controls
| Key | Action |
|---|---|
| W A S D / Arrow keys | Steer |
| Shift | Boost (uses extra fuel) |
| R | Use a spare part to repair the hull |
| P | Pause |

If the game runs slowly, click **✨ HD** in the top-left corner to switch to **⚡ Fast** mode.

## Tech
A single `index.html` file using [three.js](https://threejs.org/) r128 (loaded from a CDN), with custom GLSL shaders for the planets, nebula, asteroids and engine exhaust, plus HDR bloom post-processing. There's no build step: open `index.html` in a browser, or host it on any static site.

## Science notes
- Real Earth-to-Mars trips don't cross the main asteroid belt, which lies beyond Mars. The game's space rocks are a "meteoroid swarm."
- Jupiter and Saturn are drawn much larger than they'd really look from there, so players can see them.
