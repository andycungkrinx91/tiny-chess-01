# tiny-chess-01

A deterministic 4 KB Python 3.13 chess engine for [make.fun/bounty/tiny-chess-01](https://make.fun/bounty/tiny-chess-01).

- Tapered PeSTO piece-square evaluation with endgame mop-up
- Negamax + PVS + iterative deepening under a fixed node budget
- Transposition table, MVV-LVA, killers, history heuristic, null-move pruning, LMR, and quiescence search
- Standard library only (`main.py` <= 4,096 bytes)
