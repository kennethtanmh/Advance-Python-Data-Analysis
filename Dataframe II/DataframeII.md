# Section Highlights

- Advance indexing with binary ops
- Sorting, lookups and recording
- Pruning duplicates, NAs, Columns and Rows

## Notes

- isin(values):return a boolean Series showing whether each element in the Series matches an element in the passed sequence of values exactly.
- lookup(row_labels, col_labels): Label-based “fancy indexing” function for DataFrame. Given equal-length arrays of row and column labels, return an array of the values corresponding to each (row, col) pair.
- sort_index(\*, axis=0, level=None, ascending=True, inplace=False, kind='quicksort', na_position='last', sort_remaining=True, ignore_index=False, key=None) : sort the index for respective row/columns
