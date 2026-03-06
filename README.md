# 🌍 Traveler Challenge

A geography guessing game inspired by classic Flash-era map games. Test your knowledge of world cities — find them on the map before time runs out!

**[▶ Play now on GitHub Pages](https://grgbrg.github.io/traveler-challange)**

---

## How to Play

A city name appears on the screen. Your job is to click the correct location on the map as quickly and accurately as possible.

- **The closer your click**, the more points you earn
- **The faster you click**, the bigger the time bonus
- Each level consists of 8 questions
- Reach the score threshold to pass the level and advance
- Pass a level on your **first attempt** to earn a bonus

---

## Game Modes

| Mode | Description |
|------|-------------|
| 🌍 World | Cities from all over the world |
| 🗺️ Europe | European cities only, tighter map area |

---

## Difficulty

| Level | Countries shown | Threshold (lvl 1–9) | Threshold (lvl 10–12) | Timer |
|-------|----------------|---------------------|-----------------------|-------|
| Easy | ✅ Yes | 50% | 50% | 15s |
| Medium | ✅ Yes | 65% | 75% | 10s |
| Hard | ❌ No | 75% | 85% | 8s |

Cities are grouped into 4 tiers of difficulty (Easy → Expert), unlocked progressively across 12 levels. The final 3 levels (Expert) raise the threshold significantly.

---

## Features

- 🗺️ Interactive map powered by Leaflet.js
- 🏆 Global leaderboard via Firebase Realtime Database
- 🌙 Dark / Light theme
- 🇵🇱 🇬🇧 Polish and English language support
- 📱 Fully responsive — works on desktop, mobile portrait and landscape

---

## Running Locally

The game is a single self-contained HTML file — no build step needed.

```bash
git clone https://github.com/grgbrg/traveler-challange.git
cd traveler-challange
# Open index.html in your browser
```

Or just play it directly at **https://grgbrg.github.io/traveler-challange**

---

## Built With

- [Leaflet.js](https://leafletjs.com/) — interactive maps
- [Firebase Realtime Database](https://firebase.google.com/) — global leaderboard
- [Google Fonts](https://fonts.google.com/) — Playfair Display, DM Sans

---

## AI Assistance

This project was developed with the help of [Claude](https://claude.ai) (Anthropic) as a coding assistant — supporting implementation, debugging, and UI/UX decisions across multiple development sessions.
