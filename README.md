# Read-from-CSV

## AIM:
To read a CSV file 'NBA.csv' and count number of rows and columns.
## ALGORITHM:
### Step 1:
Import the pandas library, which is essential for data manipulation and analysis.
### Step 2:
Use the pd.read_csv() function to read the contents of the "NBA.csv" file into a DataFrame object called df. 
### Step 3:
Utilize the head() method of the DataFrame to print the first 10 rows.
### Step 4:
Use the tail() method to print the last 5 rows of the DataFrame. 
### Step 5:
Access the axes attribute of the DataFrame to determine and print the number of rows and columns

## PROGRAM:

```
import pandas as pd
df=pd.read_csv("NBA.csv")
print(df.head(10))
print(df.tail(),"\n")
print("No. of rows",len(df.axes[0]))
print("No.of columns",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/Ravi-1105/Read-from-CSV/assets/139841688/74ca30a5-4d34-44bf-95b7-0fb0710c9989)
![image](https://github.com/Ravi-1105/Read-from-CSV/assets/139841688/69d7595a-c037-4163-8edd-e167a4537f50)

## RESULT:
Thus, the given aim was acheived and printed.
