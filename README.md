# Read-from-CSV

## AIM:
To write a python program for to read a csv file and find the number of rows and columns present in it.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.
## PROGRAM:
#Program to read from a csv file and find the number of rows and columns in it
#Developed by: Pradeesh S
#Reference number: 212221240038
import pandas as pd
df=pd.read_csv('data.csv')
print(df.head(10))
print(df.tail(5))
print('No. of rows:',len(df.axes[0]))
print('No. of columns:',len(df.axes[1]))
## OUTPUT:
![](out.jpg)
## RESULT:
Thus, the program wriiten to read from a csv file and find the number of rows and columns in it.