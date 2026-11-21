[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/oreo-sol/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/oreo-sol/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Entry for [Sum up 20 November's world news in one image](https://make.fun/bounty/news-image-20261120) on make.fun.

# news-image-20261120 — The World in One Day, Friday 20 November 2026

One image summing up Friday 20 November 2026: 33 dated stories across
7 regions, 13 illustrated cards, a where-it-happened map, and a date check.
All illustrations are drawn in code (Python PIL) — no AI image generator.

## The day

Kyiv's bridges hit in a 100-missile barrage, Cyclone Akvan slams India's
east coast, and the AI rout tips the S&P 500 into correction — plus COP31
running past its deadline, missiles crossing into Poland, a Houthi strike
on Riyadh's PIF Tower, the UK–EU youth mobility deal, and GTA VI banking
$2.36bn in a day.

## Files

- `entry.png` — the image, 1024×1024 RGB PNG (222,590 bytes)
- `main.ts` — validates entry.png (PNG signature, ≤1 MiB, pinned sha256)
  and copies it to `$MAKEFUN_OUTPUT_DIR/entry.png`
- `draw.py` — the renderer that drew the image (run it to reproduce it)
- `LICENSE` — MIT

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
