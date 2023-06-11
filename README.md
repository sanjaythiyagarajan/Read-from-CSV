# Read-from-CSV

## AIM:

To write a python program for reading content from a CSV file

## ALGORITHM:

Step 1: Import pandas as pd.

Step 2:Read the CSV file using read_csv method.

Step 3:Use head and tail method to get the required contents from the file.

Step 4:Use len() method to get the number of rows and colu

Step 5:Print the output

## PROGRAM:
```
Developed by: SANJAY T
Register number:212222110039

import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("rows",df.axes[0])
print("columns",df.axes[1])
print("no.of.rows",len(df.axes[0]))
print("no.of.columns",len(df.axes[1]))  

```

## OUTPUT:

![image](https://github.com/sanjaythiyagarajan/Read-from-CSV/assets/119409242/094abfb1-dd95-4110-86c9-e14b1e39fe99)


## RESULT:

Thus a python program is written to read the contents of a CSV file.
