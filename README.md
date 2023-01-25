# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
 import sys
### Step 2:
Assign a variable count =0
### Step 3:
open a file in read mode
### Step 4:
iterate a variable (lines) through the file
### Step 5:
Assign a variable words = lines.split ()
## PROGRAM:
```
# Developed by: VIKASH S
# Register Number: 22008879

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1])
```
## OUTPUT:

![WhatsApp Image 2023-01-25 at 21 49 31](https://user-images.githubusercontent.com/119433834/214644927-32c66d83-1c7c-43cd-b44d-c2d41115e972.jpg)

## RESULT:

Thus the program is written to find the word count from the contents of a file using command line arguments.
