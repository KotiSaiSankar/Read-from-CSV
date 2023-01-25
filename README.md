# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:
```
'''
DEVELOPED BY : Koti Sai Sankar
REGISTER NUMBER : 22001315
'''

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```


## OUTPUT:
![Screenshot 2023-01-24 105630](https://user-images.githubusercontent.com/118344248/214657244-3a7c4ec7-8fab-440a-ac6e-3de658fdc673.jpg)

## RESULT:
A python program to read data from CSV files has been created successfully.
