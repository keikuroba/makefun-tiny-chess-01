# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/keikuroba/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/keikuroba/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine: a 0x88 board, negamax alpha-beta with iterative deepening, a transposition table, quiescence search, and piece-square evaluation — the whole engine in a single `main.py` under 4,096 bytes. It plays the make.fun tiny-chess-01 gauntlet through the env at `MAKEFUN_ENV_URL`, searching to a fixed node budget (never a clock) so every trial replays deterministically.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

(The env is the competition kit's practice server; see the kit's `RULES.txt` for how to start it.)

---

<sub>Entered on [make.fun](https://make.fun/?ref=6996tzqv&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
