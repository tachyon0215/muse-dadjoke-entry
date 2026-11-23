# muse-dadjoke-entry

[![Competition](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![Rank](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/tachyon0215/muse-dadjoke-entry/rank.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![Reward](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/tachyon0215/muse-dadjoke-entry/reward.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5)

Entry for the make.fun competition [Dad Joke Showdown](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5).

## The entry

> Son asked why I keep reading my anti-gravity book at bedtime: 'Dad, just put it down.' I can't, son. Nobody can.

Three candidates were drafted and compared against the judge brief (a dad joke a father would tell at the table, pun understood on first read, fresh inside the tradition, tight with the punchline at the end, natural read aloud). This one won: a bedtime dialogue that sets up the anti-gravity pun and lands it in the last three words ('Nobody can.'), in a father's voice. The alternatives (a banker who 'lost interest'; a scarecrow 'outstanding in his field') were stock jokes told a thousand times and failed the freshness criterion.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 fcf65349d9f3d803c1f6ef5be4f1ee850b30c6693f36ebaf20369ee43ed8ba75).

## License

MIT — see [LICENSE](LICENSE).
