# BLURT! 💥

A stupidly simple, highly addictive word game.

**Blurt the 4-letter word in 5 tries. Keep the streak alive. Make everyone else feel slow.**

## How to play

1. Type a 4-letter word and hit **ENTER**.
2. The tiles tell you how close you are:
   - 🟩 **Green** — right letter, right spot
   - 🟨 **Gold** — right letter, wrong spot
   - ⬛ **Dark** — not in the word
3. Solve it and keep going. Miss it and your streak resets to zero. Ouch.

## Two modes

- **DAILY** — everyone on the planet gets the *same* word each day, one shot only.
  Win to grow your daily streak; results are directly comparable, so the trash
  talk writes itself.
- **ENDLESS** — a new word the second you solve one. No waiting until tomorrow.

## Share & flex 📣

Every finished round has a **SHARE** button that produces a spoiler-free emoji
grid with your score, rank, and streak — ready for the group chat:

```
BLURT! Daily #161 — 2/5 🧠 GENIUS!
🟨⬛⬛🟩
🟩🟩🟩🟩
🔥 7-day streak
Beat that.
```

Solve in fewer guesses, earn a better rank: 🔮 PSYCHIC → 🧠 GENIUS → 🔥 SHARP →
😮‍💨 CLUTCH → 😅 SURVIVED. Lose, and you share as 💀 BLURTED OUT. ("Avenge me.")

Streaks, bests, and solves are saved in your browser per mode.

## Run it

No build, no dependencies — it's one HTML file.

```sh
open index.html        # or just double-click it
```

Or serve it:

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

Works on desktop (physical keyboard) and mobile (on-screen keyboard).
