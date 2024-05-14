# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. 
2. 
3. 
4. 

## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: P Mukteswara
RegisterNumber:  212223080039

import pandas as pd
data=pd.read_csv('spam.csv')

data.head()

data.info()

data.isnull().sum()

x=data["v1"].values
y=data["v2"].values
from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer

cv=CountVectorizer()
x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)

from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)

y_pred=svc.predict(x_test)
y_pred

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy
*/
```

## Output:
![9(1)](https://github.com/Mukteswara/Implementation-of-SVM-For-Spam-Mail-Detection/assets/162081121/365f9fd6-03b1-4b56-8f19-bc4d34a4bb28)
![9(2)](https://github.com/Mukteswara/Implementation-of-SVM-For-Spam-Mail-Detection/assets/162081121/6a75db7b-0615-4320-8a6e-32e76523dc99)
![9(3)](https://github.com/Mukteswara/Implementation-of-SVM-For-Spam-Mail-Detection/assets/162081121/d9862143-5a3e-4753-b3f0-97d1f011c777)
![9(4)](https://github.com/Mukteswara/Implementation-of-SVM-For-Spam-Mail-Detection/assets/162081121/f693c283-1dc8-4267-b140-c4404b74bbc9)
![9(5)](https://github.com/Mukteswara/Implementation-of-SVM-For-Spam-Mail-Detection/assets/162081121/1e486140-ff9f-4133-a8d1-db87c65b75de)




## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
