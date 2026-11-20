# obsidian-mate

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/buggycore/obsidian-mate/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/buggycore/obsidian-mate/reward.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic 4 KB Python 3.13 chess engine combining tapered PeSTO piece-square evaluation, principal variation search (aspiration windows, null-move pruning with zugzwang guard, LMR, LMP, RFP, futility, killers, history heuristic, quiescence with check evasions, endgame mop-up), and a compact 640-scenario opening/style variant table.

## Run it

```sh
makefun grade-local --kit <path-to-kit> --bot . --driver docker
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=4jwk2t5x&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
