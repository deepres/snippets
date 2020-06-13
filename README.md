# snippets
code snippets saving my life

## Console

### ls, xargs, sed

- list all the files with matching pattern
- create a list of entries and execute against each of them
- find two first occurences of the '-' character and remove it 
- update the file instead of outputting the result to the console

`ls -1 *-repos.csv | xargs sed -i '' 's/-//1; s/-//1'`
