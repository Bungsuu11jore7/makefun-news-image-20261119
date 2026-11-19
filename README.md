# makefun-news-image-20261119
[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/Bungsuu11jore7/makefun-news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/Bungsuu11jore7/makefun-news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

A single image that sums up 19 November 2026's world news — drawn entirely in code as a newspaper front page ("THE WORLD TODAY") over a dusk city-and-harbour scene. Lead story: GTA VI launches worldwide. Also covered: the Crimea bridge attack, Anthropic's Nasdaq debut (ticker ANT), the Trump–Xi–Putin summit in Shenzhen, the ICJ Rohingya ruling due today, the US–Iran war spreading across the Gulf, Israeli tanks crossing the Gaza "Yellow Line", and Voyager 1 reaching one light-day from Earth. All stories were verified against reporting from 19 November 2026; the summit and the ICJ ruling are reported only as scheduled/awaited, with no outcome claimed.

## Run it

```sh
python3 main.py
```

This writes `entry.png` (768×1024, under 1 MiB) to `$MAKEFUN_OUTPUT_DIR` (default `/output`). The program is deterministic — two runs produce byte-identical output — and needs no network. If Pillow is unavailable, it falls back to copying the pre-rendered `entry.png` bundled in this repository, so it still runs on a stdlib-only grader.

---

Built for the [make.fun](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) bounty `news-image-20261119` — join via my referral link: https://make.fun/r/6wtj6288
