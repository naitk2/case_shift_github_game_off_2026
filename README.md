# CASE SHIFT

A 2D typographic sci-fi puzzle-platformer built for [GitHub Game Off 2026](https://itch.io/jam/game-off-2026) (Theme: **SHIFT**).

Hold **Shift** to capitalize reality. Every interactive object in the world is driven by case—shrinking, expanding, extending, launching, or turning lethal smoothly over 110ms as you run, jump, and blast your way through 12 handcrafted levels.

## Play Online

- **itch.io:** `[Add your itch.io game URL here]`
- **Local:** Download or clone this repository and open `index.html` directly in any modern desktop or mobile browser—no build step, server, or external dependencies required.

## Core Mechanic

| Lowercase (`Shift` Released) | Uppercase (`Shift` Held) | Behavior |
| :--- | :--- | :--- |
| `box` | `BOX` | Lightweight anti-grav cargo pod you can push; morphs into a massive locked containment monolith you can ride upward or climb. |
| `gap` | `GAP` | Narrow, jumpable pit carved into terrain; widens into an unjumpable canyon when capitalized. |
| `bridge` | `BRIDGE` | Compact center-anchored hard-light emitter; projects a full sci-fi plasma bridge across wide chasms. |
| `wind` | `WIND` | Gentle upward breeze; supercharges into a high-velocity vertical updraft. |
| `8` | `*` | Safe floating platform to stand on; transforms into a spinning red asterisk sawblade hazard. |
| `guard` | `GUARD` | Patrolling crimson cyber-trooper (starting Level 03); scales up into a faster heavy juggernaut when capitalized. |
| `exit` | `EXIT` | Proximity-activated armored sci-fi blast door that slides open to reveal the level-clear warp portal. |

## Controls

| Action | Keyboard / Mouse | Touch |
| :--- | :--- | :--- |
| Move | `A` / `D` or `Left` / `Right` | On-screen Left / Right |
| Jump | `W`, `Up`, or `Space` | `JUMP` |
| Capitalize Reality | Hold `Shift` | Hold `SHIFT` |
| Shoot Plasma Blaster | `F`, `J`, `X`, or `Left-Click` (aim & hold to fire) | `FIRE` |
| Quick Restart Level | `R` | Top HUD `R` button |
| Toggle Audio | `M` | Top HUD `SFX` button |

Holding **Shift** while firing supercharges your plasma bolts into heavy cyan lances that deal double damage to `guard` / `GUARD` patrols.

## Levels (12 Handcrafted Stages)

| # | Level Name | Focus |
| :--- | :--- | :--- |
| `01` | **GROW** | Introduces `box` → `BOX` to scale a tall wall. |
| `02` | **LET GO** | Introduces `gap` → `GAP` and releasing Shift mid-run. |
| `03` | **SPAN** | Introduces hard-light `bridge` → `BRIDGE` and the first `guard` patrol. |
| `04` | **PUSH & LIFT** | Push `box` into position, then ride `BOX` up to a high ledge. |
| `05` | **UPDRAFT** | Introduces `wind` → `WIND` vertical shafts. |
| `06` | **SHIFT + 8** | Mid-air toggling between safe `8` platforms, `*` sawblades, and `BRIDGE`. |
| `07` | **RHYTHM** | Rapid mid-air case shifting across `BRIDGE`, `gap`, and `WIND`. |
| `08` | **CAPS LOCK** | Multi-step single-screen puzzle gauntlet. |
| `09` | **DOUBLE LIFT** | Chained `BOX`, `8`, `BRIDGE`, and `WIND` vertical ascent. |
| `10` | **SKYWAY** | Extended 1920px scrolling aerial gauntlet. |
| `11` | **PRESSURE** | Extended 1920px scrolling puzzle run with twin `box` lifts and patrols. |
| `12` | **FINAL SHIFT** | 2560px multi-stage finale combining every mechanic and patrol type. |

## Technical Highlights

- **Single-File Architecture:** 100% self-contained `index.html` using HTML5 Canvas, Vanilla JavaScript, CSS, and the Web Audio API with zero external libraries or image/audio files.
- **Responsive Platformer Physics:** Fixed 60 FPS timestep loop, coyote time, jump buffering, variable jump height, squash-and-stretch kinematics, and anti-clipping crush safety during morph transitions.
- **Procedural Pixel Art & Audio:** All sprites (animated jetpack ranger, crimson cyber-troopers, hard-light bridges, gravity cargo pods, and animated blast doors) and sound effects (mechanical Shift clack/thock, plasma blaster, jump/land, pneumatic door hiss, and victory arpeggio) are synthesized at runtime.
- **Responsive 16:9 Viewport:** Logical `960x540` HiDPI canvas that scales cleanly inside any browser window or itch.io iframe.

## Repository Structure

```text
.
├── index.html   # Complete playable game (HTML + CSS + JS + Web Audio)
└── README.md    # Project documentation
```

## AI Disclosure

Per the [GitHub Game Off 2026 FAQ](https://itch.io/jam/game-off-2026/topic/7290154/frequently-asked-questions-faq), AI assistance was used during the design and implementation of code and documentation for this project.

## License

`[Choose a license, e.g., MIT License]`
