# tiny-chess-01

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty ($500).

It plays the house gauntlet through the env: alpha-beta search with a
transposition table, quiescence over captures and promotions, MVV-LVA
move ordering and killer moves, and a material plus piece-square
evaluation. It searches to a fixed node budget per move, never a clock,
so a trial's replay plays the same moves. It makes no model calls.

- `main.py` is the whole engine: at most 4,096 bytes as committed,
  Python 3.13, standard library only.
- `LICENSE` is the MIT licence.
