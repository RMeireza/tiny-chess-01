# tiny-chess-01 entry — packed sunfish PST engine

Single-file 4,093-byte Python bot. LZMA-packed + base85 engine based on
thomasahle/sunfish (nnue_4k pst_entry, GPL-3.0) with a small env driver:
- full move-history tracking for repetition avoidance
- null-move pruning + LMR (as in upstream)
- 8.3s/move deadline honoring the 10s move limit

Licensed GPL-3.0 (see LICENSE). Engine (c) Thomas Ahle & contributors.
