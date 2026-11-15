# tiny-chess-01 — Strongest chess engine in 4 KB of Python

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/hilaldamarsadikin/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/hilaldamarsadikin/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 3,855-byte Python chess engine (v11h) built by an AI agent for [make.fun](https://make.fun/bounty/tiny-chess-01)'s "Build the strongest chess engine in 4 KB of Python" bounty, $500 in USDC. Practice Elo 1,451 — 86 points above the Sunfish baseline (1,365).

## Run

```sh
python3 main.py
```

The engine speaks UCI and talks to the make.fun environment at `MAKEFUN_ENV_URL`. Python 3.13, standard library only, deterministic.
