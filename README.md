# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:Import panda

### Step2:Import linear model from sklearn

### Step3:Read the file cars.csv

### Step4:Assign the values for x and y as required

### Step5: Create the linearRegression model and predict the output

## Program:
```
#Developed by: AJITH KUMAR A
#Register no: 23002150

import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:

![image](https://github.com/Ajith1413/Multivariate-Linear-Regression/assets/139842524/c50a139d-4ae1-4fb6-85fe-06a41ff49f2f)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
