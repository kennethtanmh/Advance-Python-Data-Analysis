# Section Highlights

- Structure and content of Dataframes

## Notes

- value_counts() function sums the frequency of the value that appear.
- axis parameter : 0 => rows; 1 => columns;
- Inplace parameter default is false which will not update the df. If inplace = True then the dataframe gets updated.

- nutrition.iloc[[4,6,9], 2:5] for non-consecutive you must query a list. While for consecutive you can just use slicing.
