# EXP-3-Implementation-of-log-transformation
## AIM:
Perform log transformation on international airline passenger data.
## ALGORITHM:
## STEP 1: 
Import the required packages like pandas and numpy
## STEP 2: 
Read the data using the pandas
## STEP 3: 
Perform the data preprocessing if needed and apply log transformation.
## STEP 4: 
Plot the data according to need, before and after log transformation.
## STEP 5: 
Display the overall results.
## PROGRAM:
## DEVELOPED BY: P SYAM TEJ
## REF NO : 212221240056
```
import numpy as np
import pandas as pd
data= pd.read_csv('AirPassengers.csv')
data.head()
data.dropna(inplace=True)
x=data['Month']
y=data['#Passengers']
data_log=np.log(data['#Passengers'])
X=data['Month']
Y=data_log
import matplotlib.pyplot as plt
plt.plot(x,y)
plt.xlabel('Original Data')
plt.plot(X,Y)
plt.xlabel('Log- Transformed data')
```
## OUTPUT:
## FIRST FIVE ROWS:
![image](https://github.com/Syam-tej/EXP-3-Implementation-of-log-transformation/assets/93427224/c63a851c-c874-4073-84e1-5852f9f4eacc)
## BEFORE LOG TRANSFORMATION:
![image](https://github.com/Syam-tej/EXP-3-Implementation-of-log-transformation/assets/93427224/a7e80629-b19b-4a85-ac1b-fe3ae2168579)
## AFTER LOG TRANSFORMATION:
![image](https://github.com/Syam-tej/EXP-3-Implementation-of-log-transformation/assets/93427224/dcf2b2a0-fa1f-4ec8-bf0e-fe367421f971)
## RESULT:
Thus we have created the python code for the log transformation on international airline passenger data.
