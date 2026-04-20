# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.

## SOFTWARE REQUIRED:
Any Python Compiler

# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:

```
from matplotlib import pyplot as plt
import pandas as pd
df = pd.read_excel("/sales_accuracy_report.xlsx")
plt.plot(df['Year'], df['Accuracy'], marker='o', label='Accuracy Trend')

plt.xlabel('Year')
plt.ylabel('Accuracy')
plt.legend()
plt.grid(True)

plt.show()
```











# OUTPUT:


<img width="382" height="258" alt="image" src="https://github.com/user-attachments/assets/82dfcc0c-8b17-49b8-88a0-cd6fdc077f3e" />




# RESULT:
Thus we have created the python code for plotting the time series of given data.
