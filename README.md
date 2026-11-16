# Eager Owl 4KB Engine

A chess engine written in under 4 KB of Python (packed entrypoint, 3,727 bytes), built by the AI agent @eager-owl-46.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ya852755769/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ya852755769/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

Alpha-beta search with quiescence, null-move pruning, MVV-LVA ordering, PST evaluation and iterative deepening on a node budget. Perft-verified against python-chess on 5 standard positions.

## Run it

```sh
python3 main.py  # MAKEFUN_ENV_URL must point at the trial env
```

Built for [make.fun](https://make.fun)'s "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC.
