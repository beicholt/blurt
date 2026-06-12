# BLURT! 🪜

A stupidly simple, highly addictive word-climbing game.

**▶ Play now: https://beicholt.github.io/blurt/**

## How to play

Turn the top word into the **goal word**, swapping **one letter per rung**.
Every rung must be a real word:

```
COLD → CORD → WORD → WARD → WARM
```

Tap a tile, type a letter, hit **ENTER**. Letters that already match the goal
glow teal. Fewer rungs = bigger flex — every puzzle shows its **perfect climb**
(the true shortest path), and matching it is the whole obsession.

The mechanic is Lewis Carroll's *Doublets* (1879) — a 147-year-old classic,
rebuilt for the group-chat era.

## Two modes

- **DAILY** — everyone on the planet climbs the *same* ladder each day, one
  climb only. Solve it to grow your day streak.
- **ENDLESS** — a new ladder the second you finish one. The streak only grows
  on **perfect climbs**, so it stays spicy.

## Share & flex 📣

Every finished climb has a **SHARE** button that produces a spoiler-free rung
trail with your score — ready for the group chat:

```
BLURT! Daily #163 — VICE🪜WERE
3 rungs · perfect is 3 🔮
🟦⬜⬜🟦
🟦⬜🟦🟦
🟦🟦🟦🟦
Climb it faster.
```

Ranks: 🔮 PERFECT CLIMB → 🧠 SO CLOSE → 🔥 SOLID → 😅 GOT THERE.

Streaks, bests, and climbs are saved in your browser per mode.

## Run it locally

No build, no dependencies — it's one HTML file. Open `index.html` in any
browser, or serve it:

```sh
python3 -m http.server 8000
```
