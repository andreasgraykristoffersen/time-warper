# Time Warper

A 2D arcade shooter where you can stop time and scrub the world backwards — but never yourself.

**Play it:** https://andreasgraykristoffersen.github.io/time-warper/

## The idea

Press **E** and time stops. Scroll backwards as far as you like: the swarm, the bullets and the
damage you dealt all unwind with it — but **you stay standing exactly where you are**, and so do
your hearts, your xp and every upgrade you own. Rewinding is unlimited, but every fifth rewind
costs you a heart.

## Modes

| Mode | How it works |
|---|---|
| **Survive** | Two minutes. Splinter lands at 1:30 left, Fracture at 1:00, Terminus at 0:30 — they stay. Outlive the clock. |
| **Endless** | No deadline, a stopwatch counting up. A boss every 30 seconds, each cycle harder than the last. Death is the only ending. |
| **Boss duels** | Each boss freezes the clock dead at 30 and gives you thirty seconds to kill it. Win and the clock restarts; that boss never returns. Killing all three is the only way to win. |

## Controls

- **WASD / arrows** move, **mouse** aims — the gun fires on its own
- **E** stop time, wheel / drag / **A**·**D** to scrub, **E** or **Space** to land
- **1 2 3** pick an upgrade · **F** fullscreen · **M** mute
- On touch: drag the left half to move, the right half to aim

## Upgrades

Kills are xp. Every level freezes time and offers three of fifty upgrades — lasers, bomblets,
ring volleys, orbit blades, medic rounds that drop healing on the ground, and **Echo**, which
leaves a copy of you replaying the seconds you just erased, carrying your whole arsenal.
Some upgrades only appear once you own what they build on.

## Built with

One HTML file, no build step, no dependencies — canvas 2D, hand-rolled fixed-timestep loop,
WebAudio for the synth score and every sound effect. The soundtrack option is
*Cyberpunk Strength* by ribhavagrawal, embedded in the page.
