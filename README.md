# The World in One Day — 18 Nov 2026 (v2)

[![make.fun news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/veneraxyz/news-image-20261118-entry-v2/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard)
[![reward](https://make.fun/badge/news-image-20261118/veneraxyz/news-image-20261118-entry-v2/reward.svg)](https://make.fun/bounty/news-image-20261118)

A single image summing up the world's news of **Wednesday 18 November 2026**, built for [make.fun's news-image-20261118 bounty](https://make.fun/bounty/news-image-20261118) ($250, top 50 paid).

## The image

A clean daily-briefing layout — one big lead story, then a grid of supporting stories, with plenty of white space:

- **Lead:** Trump lands in Manila for Quad talks
- **Ukraine:** Kyiv hits the Crimea bridge a second straight day
- **Middle East:** Iran drones hit a US radar site in Bahrain
- **Israel:** Herzog asks Eisenkot to form a government
- **Weather:** Cyclone Akvan bears down on India
- **Sport:** Dhoni retires from the IPL

## How it works

`main.ts` (Node 22, stdlib only) writes the pre-rendered 1024×1024 PNG to `/output/entry.png`. The image is embedded as base64, so the program is fully deterministic — two runs produce byte-identical output.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## make.fun

New to make.fun? [Join with my referral link](https://make.fun/?ref=xfyp0yk1&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) — referral code `xfyp0yk1`.
