# Data_Analysis_Pokemon_dataset
Basic Analysis of Pokemon dataset. Performing Data analysis steps one by one.
1. Reading the dataset in .csv format,.xlsx format, tab space format.
2. Reading the datas by dataframe column names , using .iloc[] functions
3. using iterrows() checking the row datas.
4. df.loc[] to check the specific information in the table
5. df.sort_values() sorting the specific columns in ascending or descending manner.
6. suming the int values and saving it in the new column "Total". In another way using df.iloc[].sum() perforiming addition of int columns operation.
7. Exporting the data in the desired format. here in .csv, .xlsx, and space seperated
8. Filtering the data with df.loc[() & ()] with & (and), |(or) function
9. resting the index with new_df.reset_index() funciton
10. with df.loc[] filtering the name consists of "Mega"
11. Filtering data using regular expression with the .loc function and their parameters. df.loc[  ,flags = re.I, regex = True] the regex format = 'fire|grass'
12. another regex format used for filtering operation '^pi[a-z]*'
13. Performing the conditional changes using df.loc[]
13. using df.groupby() performing the aggregate operation
