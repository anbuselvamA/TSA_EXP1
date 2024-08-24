### DEVELOPER NAME: ANBUSELVAM.A
### REG NO:212222240009
# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 24-08-2024

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
import pandas as pd
import matplotlib.pyplot as plt
df = pd.read_csv('/content/student_performance.csv', index_col='Name', parse_dates=['Gender'])

plt.figure(figsize=(12, 6))
plt.plot(df.index, df.iloc[:, 0])
plt.title('Students performance')
plt.xlabel('FinalGrade')
plt.ylabel('Number of student')
plt.grid(True)

```










# OUTPUT:


![image](https://github.com/user-attachments/assets/5dee34c3-5683-4841-9812-ca6fdabcc304)








# RESULT:
Thus we have created the python code for plotting the time series of given data.
