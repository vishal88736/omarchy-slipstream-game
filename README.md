<p align="center"><img src="icon.svg" width="128" alt="Slipstream icon"></p>

# Slipstream

A high-speed cyber highway arcade racer for [Omarchy](https://omarchy.org)'s **Game Vibes**. Weave through neon multi-lane traffic, draft directly behind rivals to charge your **Kinetic Overdrive**, rack up **Near Miss** combo multipliers, and trigger Overdrive to smash through traffic in explosive takedowns!

Built as a single standalone HTML file powered by three.js and Web Audio synthesis. It automatically adopts your desktop theme's color palette, features bloom glow in dark themes, and remembers your all-time high score.

---

## Install

### On Omarchy

**From the menu:**
Open the Omarchy menu (`Super`), navigate to **Install → Gaming → Game Vibes**, and paste this repository's URL:

```
https://github.com/vishal88736/omarchy-slipstream-game
```

**Or from a terminal:**

```bash
omarchy games vibes install https://github.com/vishal88736/omarchy-slipstream-game
```

Once installed, **Slipstream** appears directly in **Game Vibes** in your application launcher (`Super + Space`).

---

## Controls

| Key | Action |
|---|---|
| `←` `→` / `A` `D` | Steer car & initiate drift |
| `↑` / `W` | Accelerate throttle |
| `↓` / `S` | Brake / tight drift control |
| `Space` / `Shift` | Trigger **Kinetic Overdrive** (Hyper Boost & Takedown Ram) |
| `Mouse` | Steer left/right · Click to Boost |
| `Esc` / `P` | Pause / resume / back to Game Vibes |
| `M` | Toggle sound effects on/off |
| `?` | In-game help & mechanics manual |
| `Q` | Return to Game Vibes (from pause screen) |

---

## Unique Gameplay Mechanics

- **Speed Orbs & Velocity Surges**:
  Collect glowing golden Speed Orbs floating along the highway lanes between traffic. Each orb gives an immediate instant acceleration surge (+25 km/h), extends the **Speed Surge** buff, recharges +20% Kinetic Boost energy, and awards +350 bonus points multiplied by your combo!
- **Aerodynamic Slipstream Drafting**:
  Tuck in right behind opponent vehicles within their drafting cone. You'll hear the aerodynamic whistle, pick up an immediate velocity surge, and recharge your **Kinetic Boost** gauge.
- **Near Miss Combos**:
  Swerving past traffic at razor-thin margins awards bonus score points and increases your **Combo Multiplier** (`x1` up to `x8`). Keep near-missing or drafting to prevent combo decay.
- **Kinetic Overdrive & Takedowns**:
  When charged, hit `Space` to unleash Overdrive. Your car surges past 300+ km/h with warp FOV, afterburner flames, and invincibility. Ram rival vehicles to launch them off the track for massive **TAKEDOWN** bonuses!
- **Dynamic Sectors**:
  Travel through evolving sectors including Metropolis, Neon Canyon, and Orbital Highway with increasing traffic density and highway police interceptors.

---

## Offline & Architecture

- **Single Self-Contained File**: Runs entirely offline with zero external network dependencies or asset downloads.
- **Synthesized Audio**: Procedural engine pitch modulation, aerodynamic wind whistle, tire screech, and explosive impacts synthesized in real time via Web Audio API.
- **Dynamic Theme Palette**: Automatically adapts colors to dark and light Omarchy desktop themes with real-time bloom post-processing.
