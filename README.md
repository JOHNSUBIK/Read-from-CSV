# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_CSV method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Display the result.

## PROGRAM:
```
Developed by: John Paul J
RegisterNumber: 212223230093
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:

![Screenshot 2023-12-29 190117](https://github.com/JOHNSUBIK/Read-from-CSV/assets/150279319/0eefc5dd-0b11-4ded-ae77-bfd966a3ceeb)

## RESULT:
Thus the program excuted successfully
