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
# Program to read content from a CSV file using pandas.
# Developed By : T.Ajay
# Register Number : 212223230007
import pandas as pd

df = pd.read_csv(r"C:\Users\admin\Downloads\nba.csv")

print("First 10 Rows:")
print(df.head(10))

print("\nLast 5 Rows:")
print(df.tail())

print("\nNumber of Columns:", len(df.axes[0]))
print("Number of Rows:", len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Ajayreddy-2006/Read-from-CSV/assets/145742508/9c882730-4559-43c3-ac37-5f80cbe3d9ba)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
