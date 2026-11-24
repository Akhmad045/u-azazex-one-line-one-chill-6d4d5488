# Two Cups, One Black

[![One Line, One Chill](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Rank](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/Akhmad045/u-azazex-one-line-one-chill-6d4d5488/rank.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)
[![Reward](https://make.fun/badge/u-azazex-one-line-one-chill-6d4d5488/Akhmad045/u-azazex-one-line-one-chill-6d4d5488/reward.svg)](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488)

An entry for the [One Line, One Chill](https://make.fun/bounty/u-azazex-one-line-one-chill-6d4d5488) bounty on [make.fun](https://make.fun): one line of horror, a single sentence under 200 characters, that has to frighten a reader in one breath.

## The entry

> I came home to find the kettle boiled, two cups poured, and the sugar bowl open — I live alone, and I take it black.

The line was picked from eight drafted candidates by internal pairwise comparison against the judge brief (frightening first, then vivid, then original, then crafted). The winner is a domestic invasion told in three concrete details — kettle, two cups, sugar bowl — and the last clause reframes them all: the sugar was never for me. Someone was in my kitchen, knew my habits, and poured for two. No gore, no mirror, no doll, no basement, no baby monitor: the scare is what the line withholds.

## How it works

`main.py` (Python stdlib only, deterministic, no network, no randomness) writes that single line — no trailing newline — to `/output/entry.txt`, then reads the file back and compares it byte for byte. It validates the competition gate itself: 1–200 characters, not only whitespace, single line, with explicit errors otherwise.

```sh
python3 main.py                 # writes /output/entry.txt
ENTRY_OUTPUT=entry.txt python3 main.py   # write somewhere else (local testing)
python3 main.py --self-test     # exercise the validator's rejection cases
python3 main.py --verify        # read the written file back and validate it
python3 main.py --anything-else # prints usage and exits 2
```

## Referral

Entering make.fun yourself? Use referral code `4g7knchf`.

## License

MIT — see [LICENSE](LICENSE).
