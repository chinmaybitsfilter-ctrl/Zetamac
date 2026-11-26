# QuantMac — Zetamac-style trainer for quant interviews

A single-page web app for quant/HFT interview prep (Optiver, SIG, Jane Street, IMC, Citadel, Tower…).
No build step, no server — open `index.html` or host it on GitHub Pages. Installable on phone/laptop and works offline.

## Modes
| Mode | What it trains |
|---|---|
| Zetamac Classic | + − × ÷ with custom ranges (same defaults as arithmetic.zetamac.com), auto-submit when correct |
| Optiver 80-in-8 style | 80 mixed questions in 8 min, Enter to submit, −1 for wrong |
| Decimals / Fractions / Percentages & bps | The non-integer arithmetic that trading tests lean on |
| Squares, cubes & roots | 11²–99², cubes, √, powers of 2, ×11, near-100 |
| Big multiplication | 2×2, 3×1, 3×2, 4×1 digit |
| Estimation | ± tolerance answers: products, roots, ln, compounding, reciprocals |
| Number sequences | Next-term patterns (arithmetic, geometric, 2nd differences, interleaved, primes…) |
| Probability sprint | Dice, coins, cards, Bayes, EV, combinatorics — generated fresh |
| Custom mix | Any combination of the above |
| Brainteaser bank | 46 classic puzzles with hints, answer checking and solutions |
| Calibration | 90% confidence-interval practice |
| Stats | Personal bests, score trend, weakest question types |

Keys: answers auto-submit · `Tab` skip · `Esc` end · `Enter` replay. On phones an on-screen keypad appears.
Progress is saved in your browser (localStorage).

## Deploy on GitHub Pages
1. Upload `index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md` to this repo (main branch, root).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. Open `https://<username>.github.io/Zetamac/` — on Android Chrome use ⋮ → *Install app*; on iPhone Safari use Share → *Add to Home Screen*.
