# Bitboard Chess

A bitboard chess engine in 4,096 bytes of Python for make.fun tiny-chess-01: alpha-beta with iterative deepening on a fixed node budget, quiescence, MVV-LVA + killer + history ordering, transposition table, and an eval of material + piece-square tables + pawn structure + king shelter. Deterministic: no clock, no randomness.

Run it: set MAKEFUN_ENV_URL to the game env and run `python3 main.py`.
