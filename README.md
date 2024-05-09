# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Read the csv file
<br>

### Step2
Get value of X and Y variables
<br>

### Step3
Create the linear regression model and fit
<br>

### Step4
Predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm cube.

<br>

### Step5
Print the predicted output.
<br>

## Program:
```
Developed by: THARUN SRIDHAR
Reg.No: 212223230230
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))





```
## Output:
![image](https://github.com/Tharun0707/Multivariate-Linear-Regression/assets/145548496/c5a96951-4f7a-4956-abf9-b18a81997f6e)

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
