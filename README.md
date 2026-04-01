# 🌍 Flag Quest
<img width="1845" height="894" alt="image" src="https://github.com/user-attachments/assets/b9852400-723b-4528-b737-78a39c1660da" />


A flag geography quiz game built as a single static HTML file, playable directly in the browser.

**[Play](https://insanecipher.github.io/flag-quest/)**

## How to Play

1. A country's flag is shown on the right panel
2. Spin the globe by dragging and find the country, then click it
3. You have **5 guesses** per round before the turn ends
4. The **country name** is revealed after your 1st wrong guess
5. The **continent** is revealed after your 3rd wrong guess
6. A 60-second turn timer drains on screen — answer faster for more points
7. Each correct answer adds **+10 seconds** to the global clock

## Scoring

Scoring is exponential — speed and accuracy are both heavily rewarded.

| Situation | Approximate Score |
|---|---|
| 1st try, first 5 seconds | ~900 pts |
| 1st try, 25 seconds | ~340 pts |
| 3rd try, 10 seconds | ~55 pts |
| 5th try, any time | ~5 pts |

## Rules

- ❤️ **5 lives** — lose one when the turn timer runs out or you exhaust all 5 guesses
- ⏱ **5 minute global timer** — game over when it hits zero
- ✅ Correct answers add +10s to the global timer
- Each country only appears once per game

## Controls

| Action | Control |
|---|---|
| Rotate globe | Click and drag |
| Zoom | Scroll wheel |
| Guess a country | Click it |

---

## Tech

- [D3.js](https://d3js.org/) — globe projection and geographic rendering
- [TopoJSON](https://github.com/topojson/topojson) — high-fidelity country borders
- [Natural Earth](https://www.naturalearthdata.com/) via `world-atlas` — geographic data
- No frameworks, no build tools, no backend
