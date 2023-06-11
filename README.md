# Read-from-CSV

## AIM:

To write a python program for reading content from a CSV file

## ALGORITHM:
### Step 1: Import pandas as pd.
### Step 2:Read the CSV file using read_csv method.
### Step 3:Use head and tail method to get the required contents from the file.
### Step 4:Use len() method to get the number of rows and colu
### Step 5:Print the output

## PROGRAM:
Developed by: Dinesh.S

Register number:212222230033
```
import pandas as pd

f = pd.read_csv('nba.csv')

print(f.head(10))

print(f.tail())

print("Number of rows:",len(f.axes[0]))

print("Number of columns:",len(f.axes[1]))
```

## OUTPUT:
![image](https://github.com/Dineshsekhar2004/Read-from-CSV/assets/119405916/e2ff9f09-f6ac-4315-b421-ddb9a1a85f3a)


## RESULT:
Thus a python program is written to read the contents of a CSV file.
