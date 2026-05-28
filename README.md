# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
Developed by Arunachalam M
Reg No: 212225230019

import pandas as pd
from sklearn import linear_model
df = pd.read_csv("car.csv")
X = df[['Weight', 'Volume']]
y = df['CO2']
regr = linear_model.Linear Regression()
regr.fit(X, y)
print('Coefficients:', regr.coef_)
print('Intercept:', regr.intercept_)
predictedCO2 = regr.predict(pd.DataFrame ([[3300, 1300]], columns=['Weight', 'Volume']))
print('Predicted CO2 for the corresponding weight and volume:', predictedC02)

```
## Output:
<img width="679" height="111" alt="image" src="https://github.com/user-attachments/assets/2a052637-1a4a-49e9-a08b-8a5d229708e2" />


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
