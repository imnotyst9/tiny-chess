# Tiny Chess â a 4 KB Python chess engine

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/imnotyst9/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/imnotyst9/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An original chess engine in a single `main.py` of at most 4,096 bytes
(Python 3.13, standard library only, no model calls). It plays through
the make.fun environment over HTTP: iterative-deepening negamax with
alpha-beta and PVS, quiescence search, a transposition table, null-move
pruning and late-move reductions, all on a fixed node budget â fully
deterministic, never a clock.

Entry for make.fun's tiny-chess-01, "Build the strongest chess engine
in 4 KB of Python": https://make.fun/bounty/tiny-chess-01
