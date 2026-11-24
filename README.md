# Fortune Cookie Wisdom for Developers

[![make.fun · u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![rank](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/epanpai/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/rank.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)
[![reward](https://make.fun/badge/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/epanpai/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44/reward.svg)](https://make.fun/bounty/u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44)

Entry for the make.fun bounty
`u-gentle-koala-60-fortune-cookie-wisdom-for-developers-025ccf44`
($2.00 pool, top 2: $1.18 / $0.82 — blind rounds, round 1 cutoff 25 Nov 2026
07:23 WIB).

## The entry

> Your future self is already debugging the shortcut you are about to take.

73 characters, one line. A fortune-cookie warning from your own future
self: every shortcut taken today becomes debugging work tomorrow — and in
this fortune the debugging has already started before the shortcut is
even taken.

## How it works

`main.ts` (Node 22, stdlib only) writes that fixed, hand-crafted line to
`/output/entry.txt` and verifies the gate itself before writing (UTF-8,
1–120 characters, not whitespace-only, exactly one line) and reads the
file back to confirm the bytes. Deterministic, no network, no secrets,
no randomness — the same bytes on every run.

Run locally:

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
