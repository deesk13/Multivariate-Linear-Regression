# Implementation of Multivariate Linear Regression
## NAME: DEVA DHARSHINI I

## REGISTER NO: 21223240026
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
import pandas as pd

### Step2
import pandas as pd.

### Step3
Get the value of X and y variables.
### Step4
Get the value of X and y variables.

### Step5
predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm.

## Program:
```
'''
Python program to implement multivariate linear regression and predict the output.
Developed By:DEVA DHARSHINI I
Reference Number:212223240026
'''
import pandas as pd
from sklearn import linear_model
data= pd.read_csv("/content/cars (1) (1).csv")
X=data[['Weight','Volume']]
Y=data['CO2']
regr=linear_model.LinearRegression()
regr.fit(X,Y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print("prediction CO2 for the corresponding weight and volume",predictCO2)
```
## Output:

### Insert your output

![Screenshot 2024-05-12 161224](https://github.com/deesk13/Multivariate-Linear-Regression/assets/150927063/200ebb36-e8da-43b2-9208-ef34737a31db)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
