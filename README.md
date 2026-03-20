# 🧀 Swiss Cheese Defence

An interactive, browser-based educational game that teaches road safety through the **Swiss Cheese Model** of accident causation (James Reason, 1990).

**Live game:** https://engluka.github.io/swisscheese-website-v3/

---

## About

The Swiss Cheese Model explains how complex system failures occur when defensive layers all have gaps that align simultaneously. This game applies that concept to road safety using the **Safe System Approach**, requiring players to actively defend five safety pillars.

---

## How to Play

1. Open `index.html` in any modern browser — no server, no dependencies, no build step required.
2. Enter your name and click **Start Game**.
3. Hazards (red dots) travel left → right through five cheese slices.
4. **Click a hole** to plug it before a hazard passes through.
5. A crash only happens when holes in **all five layers align at once**.
6. **One crash = Game Over.**
7. Survive each timed challenge to advance levels. There are **4 challenges** to reach Level 5.

---

## Scoring

| Action | Points |
|---|---|
| Active block — you plugged the hole that stopped a hazard | **+50 + level × 15** |
| Passive block — cheese body stopped hazard (no hole there) | +2 |
| Survival — staying alive each second | +level per second |

A pop sound plays on every active block.

---

## The Five Safe System Pillars

| Pillar | Description |
|---|---|
| 🛣️ Safe Roads | Road infrastructure designed to be forgiving of human error |
| 🚗 Safe Vehicles | Crash protection and avoidance technology (AEB, airbags, ESC) |
| 🚦 Safe Speeds | Speed limits set by road function; speed cameras and enforcement |
| 🧑‍🤝‍🧑 Safe Road Users | Licensed, sober, unimpaired users wearing seatbelts |
| 🚑 Post-Crash Care | Rapid emergency response and quality trauma care |

---

## Challenges

| # | Challenge | Mechanic | Safety Lesson |
|---|---|---|---|
| 1 | ⚡ Speed Surge | Hazards move at 2× speed | Kinetic energy rises with the square of speed |
| 2 | 🌊 Swiss Avalanche | Triple hazard spawn rate | High volume overwhelms safety systems |
| 3 | 🔀 Shifting Cheese | Holes shift position every second | Safety gaps are not static — complacency is dangerous |
| 4 | 🌫️ Blind Spot | Severely reduced visibility | Night, fog, and distraction cut hazard detection time |

---

## Project Structure

```
index.html      # Complete game — single self-contained file
README.md       # This file
LICENSE         # Copyright notice
```

No build tools, no package manager, no external dependencies. Clone and open `index.html`.

---

## License

Copyright © 2026 Dr. Anteneh Afework Mekonnen. All rights reserved.
See [LICENSE](LICENSE) for details.
