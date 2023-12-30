# Read-from-CSV

## AIM:

## ALGORITHM:
Step 1:

Import pandas as pd.

Step 2:

Read the CSV file using read_csv

Step 3:

use head and tail method to get the required contents from the file

Step 4:

Use len() method to get the number of rows and columns.

Step 5:

print the output
## PROGRAM:
```
Developed by: DHANUSH P
Register Number:23001835
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0))
print("NUmber of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Dhanush0143/Read-from-CSV/assets/139841924/07a54e64-570b-4bb8-9c68-7fc9c7d292f7)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
