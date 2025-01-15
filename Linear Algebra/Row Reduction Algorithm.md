## Steps:
1. Swap rows to get the leftmost non-zero entry in the remaining rows to the top
2. Scale that row so the leading entry is a pivot 1
3. Clear all non zero entries in the column of that pivot
4. Repeat with all the remaining rows. with the like new top row being the one below the row that was just on top
We do not really need to do the last row