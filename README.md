# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1:
import pandas as pd

### Step2:
Read the csv file

### Step3:
Get the values of x and y variables.

### Step4:
Create the linear regression model and fit.

### Step5:
Predict the CO2 emission of a car where the weight is 3300kg, and the vlume is 1300cm3.

### Steop6:
Print the predicted output.

## Program:
```
Developed by: Kabilan.V
register no: 212222100018
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

### Insert your output

![244925093-68aaf939-589b-435d-9491-4b479b9a38c6](https://github.com/kabilan22000284/Multivariate-Linear-Regression/assets/123469171/eb0fed0e-3a0b-42ec-a00f-fc3aa23fec58)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
