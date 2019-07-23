# I would use the "wc" command.  The output othat can be piped to a file so that the researcher can see how many values are in each file. A line of code such as:
find . -name 'values*' | wc -l

# or

find . -name 'values*' | wc -w
