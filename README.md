# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1.Import necessary libraries (pandas, LabelEncoder, train_test_split, etc.).
2.Load the dataset using pd.read_csv().
3.Create a copy of the dataset and drop unnecessary columns (sl_no, salary).
4.Check for missing and duplicate values using isnull().sum() and duplicated().sum().
5.Encode categorical variables using LabelEncoder() to convert them into numerical values.

## Program:
/*
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: M.R.ANUMITHA
RegisterNumber:  212223040018

import pandas as pd
pf=pd.read_csv("Placement_Data.csv")
pf.head()
pf1=pf.copy()
pf1=pf1.drop(['sl_no','salary'],axis=1)
pf1.head()
pf1.isnull().sum()
pf1.duplicated().sum()
x=pf1.iloc[:,:-1]
x
y=pf1["status"]
y
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)
from sklearn.metrics import accuracy_score,confusion_matrix,classification_report
accuracy=accuracy_score(y_test,y_pred)
accuracy
confusion=confusion_matrix(y_test,y_pred)
confusion
classification=classification_report(y_test,y_pred)
print(classification)
lr.predict([[1,80,1,9,1,1,90,1,0,85,1,85]])
*/

## Output:
![the Logistic Regression Model to Predict the Placement Status of Student](sam.png)

![PIC 2](https://github.com/user-attachments/assets/40bf6ac1-9e69-4d54-82d0-df194e9a4f33)

![PIC 3](https://github.com/user-attachments/assets/d033dfc0-6a51-40f4-b752-9ded5b805def)

![PIC 4](https://github.com/user-attachments/assets/a0c67832-ddfe-41ff-a7a3-141042e02759)

![PIC 5](https://github.com/user-attachments/assets/148dc75d-b7b1-4e3f-b88c-8ff47c72fc30)

![Screenshot 2025-04-26 132925](https://github.com/user-attachments/assets/febd9d14-ac02-44ec-8e1a-5e93bcf31bd9)

![Screenshot 2025-04-26 132935](https://github.com/user-attachments/assets/2389f35b-cac1-465f-a1ea-b024fc87b401)

![Screenshot 2025-04-26 132947](https://github.com/user-attachments/assets/b25adf9c-7962-4053-b962-286e87877d3b)

![Screenshot 2025-04-26 132959](https://github.com/user-attachments/assets/82038d59-f49c-4314-9df7-5ae536a35322)


## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
