# In case of errors or problems, save copies of the files elsewhere 

# Run the following line in a terminal:
for f in *.csv; do mv ./"$f" "${f%csv}dat"; done
