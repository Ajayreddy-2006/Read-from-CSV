# Read-from-CSV

## AIM:
To read from CSV

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output:
```
## PROGRAM:
Developed by:T.Ajay
Ref.no:212223230007

import pandas as pd
f=pd.read_csv("/content/nba (2).csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![image](https://github.com/Ajayreddy-2006/Read-from-CSV/assets/145742508/7ed3c11d-1fed-440d-be21-e71e28e4571f)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
