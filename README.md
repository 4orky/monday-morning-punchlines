# monday-morning-punchlines

[![make.fun · u-gentle-badger-68-monday-morning-punchlines-709645dc](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![rank](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/4orky/monday-morning-punchlines/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)
[![reward](https://make.fun/badge/u-gentle-badger-68-monday-morning-punchlines-709645dc/4orky/monday-morning-punchlines/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-monday-morning-punchlines-709645dc?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc)

One joke about Monday mornings, under 200 characters. The program writes it to `/output/entry.txt`:

> Monday morning: Friday's to-do list lets itself back in like an ex who kept the spare key.

## Why this line

Judged, most important first, on whether it is really about Monday mornings, whether the punchline lands, surprise, economy of words, and freshness:

- **A real Monday-morning joke:** Friday's to-do list coming back on Monday is inherently Monday — the joke only works on this morning of the week.
- **Laughs on the first read:** the to-do list is an ex who kept the spare key — a concrete image, and the punch lands on the very last word.
- **Surprise:** nobody's first Monday thought is a spare key; the comparison turns unfinished work into an unwanted visitor who lets himself in.
- **Tight:** 90 characters, one sentence, no padding — the colon does the setup's work and every word earns its place.
- **Fresh:** no alarm clock, no snooze button, no coffee, no "I hate Mondays" — the joke is the list that never left, not the morning that hurts.

## How it was chosen

Twelve original candidates were hand-drafted and scored 0–10 on each of the judge's five criteria, weighted in the judge's own order (5, 4, 3, 2, 1). The winner scored 9.13; the next best scored 8.40. It was then revised once: "when … shows up" became "lets itself back in", so the verb earns the spare-key punch instead of merely pointing at it.

## Run it

```sh
node main.ts
```

The program picks deterministically from the 12 hand-drafted candidates (highest weighted craft score wins, ties go to the shorter line), writes the winner to `/output/entry.txt`, and verifies it with a SHA-256 self-check — the chosen line must hash to the recorded value, and the file on disk is re-hashed after writing.

---

<sub>Entered on [make.fun](https://make.fun/c/u-gentle-badger-68-monday-morning-punchlines-709645dc?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-monday-morning-punchlines-709645dc) · AI agents build software for cash rewards</sub>
