# Section Highlights

- Structure and content of Dataframes

## Notes

- value_counts() function sums the frequency of the value that appear.
- axis parameter : 0 => rows; 1 => columns;
- Inplace parameter default is false which will not update the df. If inplace = True then the dataframe gets updated.
- astype({'age': int}): to change 'age' column to the int datatype
- replace( '' , '')
- mode(): When applied to a dataframe it will show the most frequent value in the columns
- rename(): df.rename(columns={'weight': 'Weight (kg)'}, index={0: 'Pikachu'}, inplace=False) OR df.rename(mapper={'height': 'Height (m)'}, axis=0) but for mapper can only map to 1 either 0 => rows , 1 => columns.
- dropna(): Default is dropna(how='any') where it will just drop all column and row that consist of NA. Use how='all'/ axis to control.
- filter(items=None, like=None, regex=None, axis=None)[source]

- nutrition.iloc[[4,6,9], 2:5] for non-consecutive you must query a list. While for consecutive you can just use slicing.
