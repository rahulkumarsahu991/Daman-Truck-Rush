# Daman Truck Rush 3D

A 3D Indian-highway truck driving game that runs in the browser — on a phone or a laptop, no install.
Developed for fun and to build my skills.

**Play:** https://rahulkumarsahu991.github.io/Daman-Truck-Rush/

## What's in it

- **4 trucks** — 14 Wheeler (hi-deck with tarpaulin), 16 Wheeler (tipper), 18 Wheeler (open-body trailer), Diesel Tanker — with spinning wheels, Indian truck art and "HORN OK PLEASE"
- **17 routes** — Daman's 10 most-run routes (coal, pellet, iron ore, cement, fines loads) plus 7 scenic routes: NH-48, Thar Desert, Western Ghats (rain), Manali (snow), Konkan Coast, Mumbai City, Jim Corbett
- **30 levels** from Beginner to Pro Max, plus an Endless mode — traffic gets heavier and your truck gets faster
- **Day, evening, night or auto day→night**, with headlights and lit signs after dark
- **3 cameras** — full cabin interior (steering, gear lever, live gauges), body (chase) and drone
- **Fuel pumps** along the road — slow down in the left lane to refuel
- Exhaust smoke, road dust, boosters, coins, near-miss bonuses, engine and horn sounds

## Controls

| | Phone | Keyboard |
|---|---|---|
| Steer | ◀ ▶ buttons, steering wheel or tilt (Settings) | ← → or A D |
| Accelerate | **RACE** pedal (or Auto accelerate in Settings) | ↑ or W |
| Brake | **BRAKE** pedal | ↓, S or Space |
| Horn | horn button | H |
| Camera | camera button | C or 1 / 2 / 3 |
| Pause | pause button | P or Esc |

## Tech

A single `index.html` — plain JavaScript and [three.js](https://threejs.org) (MIT licence, loaded from a CDN), with every truck, road and building built in code. The first load needs an internet connection for the 3D engine.
