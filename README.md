# Read-from-CSV

## AIM:
To write a program for reading the csv file content.
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:

```
##Developed by: paulsamson s
##REGISTER NUMBER: 212222230104
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Row",len(df.axes[1]))
```
## OUTPUT:
![r1](https://github.com/Rohithravi333/Read-from-CSV/assets/119394126/39fae374-bc0e-45c3-ab7e-b36b6cd6a55d)

## RESULT:
Thus the program written to read csv file.
