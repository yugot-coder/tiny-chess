# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yugot-coder/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yugot-coder/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, built for the make.fun tiny-chess-01 bounty.

Bitboard board (Python ints, ray tables) with copy-make; negamax PVS
alpha-beta with a transposition table, null-move pruning, late-move
reductions, futility pruning and check extensions; quiescence over
captures and promotions, with all evasions when in check. Tapered
piece-square evaluation plus bishop pair, doubled, isolated and passed
pawn terms, rook open-file bonuses and king shelter. Fully
deterministic: a fixed 100,000-node budget per move, no clock, no
randomness.
