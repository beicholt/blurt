# BLURT! 💥

A stupidly simple, highly addictive word game.

**Blurt the 4-letter word in 5 tries. Keep the streak alive.**

## How to play

1. Type a 4-letter word and hit **ENTER**.
2. The tiles tell you how close you are:
   - 🟩 **Green** — right letter, right spot
   - 🟨 **Gold** — right letter, wrong spot
   - ⬛ **Dark** — not in the word
3. Solve it and a **new word starts immediately** — no waiting until tomorrow.
4. Miss it and your streak resets to zero. Ouch.

Your streak, best streak, and total solves are saved in your browser.

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
