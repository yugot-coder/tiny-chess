# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yugot-coder/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yugot-coder/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, built for the make.fun tiny-chess-01 bounty.

Bitboard board (Python ints, ray tables), negamax PVS alpha-beta with a
transposition table, quiescence search, late-move reductions and check
evasions; tapered piece-square evaluation with doubled and passed
pawn terms. Fully deterministic: a fixed 60,000-node budget per move,
no clock, no randomness.
