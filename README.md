# dcv_matrix
Dict of Common Values is a sparse matrix representation that is especially useful for discrete valued sparse matrices with a few number of unique values, e.g. user-rank matrices. This representation first converts dense matrix to coordinate format, then groups by column index to eliminate any repeating index. This ensures that each stored value does not repeat throughout the sparse format. Currently implemented:

  - Transform
  - Inverse transform
  - Save to disc
  - Load from saved

## Requirements
  - Numpy
  - Pandas
