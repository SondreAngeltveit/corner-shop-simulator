# Corner Shop Simulator

A turn-based browser game about running a corner shop on the edge of chaos.

Play it here --> https://sondreangeltveit.github.io/corner-shop-simulator/ 

---

## What is it?

You run a corner shop. Customers walk in with attitudes, demands, and occasionally pigeons. You make decisions. Stats change. Things spiral. You try to survive.

Each turn a customer enters and you pick one of three actions. Your choices affect four stats:

| Stat | What it means |
|---|---|
| 💰 Money | Runs out = bankrupt |
| ⭐ Reputation | Hits zero = nobody comes in |
| 😰 Stress | Hits 100 = breakdown |
| 🔥 Chaos | Hits 25 = total anarchy |

---

## Features

- **12 base customers** — each with unique mechanics, greetings, and action outcomes
- **5 unlockable customers** — gated behind grade thresholds, with a streak system to keep them
- **Random events** — health inspections, power cuts, pigeon infestations, flash sales, celebrity sightings and more
- **Shop upgrades** — buy permanent improvements mid-run (Security Camera, Staff Kettle, Shop Radio...)
- **Consumables** — emergency supplies when things go wrong (Paracetamol, Box of Biscuits, Fire Extinguisher)
- **3 difficulty modes** — Chill, Normal, Chaos Mode
- **Survival goal** — reach turn 30, then choose to close up or push on for rewards
- **End-of-day summaries** — every 20 turns you get a recap of how the day went
- **Grading system** — F to S+ based on your final stats
- **Leaderboard** — top 5 runs saved in your browser
- **Personal bests** — tracks longest run, best grade, total runs

---

## How to play

Just open `corner-shop-simulator.html` in any modern browser. No install, no server, no internet connection required after the first load (fonts load from Google Fonts).

---

## Technical notes

- Single HTML file — all CSS and JavaScript are inline
- No dependencies, no build step, no backend
- Save data stored in `localStorage` (stays in your browser)
- Works in Chrome, Firefox, Safari, Edge

---

## Built with

- HTML / CSS / JavaScript (vanilla)
- [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) and [Syne](https://fonts.google.com/specimen/Syne) via Google Fonts
- Built iteratively with [Claude](https://claude.ai)
