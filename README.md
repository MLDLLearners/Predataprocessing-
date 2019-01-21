# Predataprocessing-
Machin learning
1.there are server stages in the ML process.
Data Pre-processings:
 here we will import the data set using some python libery which are 
Pandas,numby,matplotlib
Import numpy as np
Import pandas as p
Import matplotlib.pyplot as plt
Should be save the working directory in the windows
.Data missing : here we will be corrected the data using mean function in the dataset
from sklearn.preprocessing import Imputer
Category :To traing the Ml model we should not have the text data in the data set so using label encoder we will convert the numberic again sometime numeric will have problem on prediction so will do boolean type   using one hot encoder 
Which is assign dummy variables to the data in the dataset.
from sklearn.preprocessing import LabelEncoder,OneHotEncoder

Splitting the dataset into traning set and test set: 
Which is very important in the Ml model to train the test set the data which can understand the correlation bw variables. best way to do 80:20 train and test respectively. test_size=0.2
Feature scalaing : if there is more difference between the variable range then we must apply the feature scaleing . which actually apply the gives the scale  or normalization.  


Regression :
Note:
1. when every we build the model we should be check the below five characterstics to make model performance better .1.All in 2.Backward elimination 3.bidiretional elimination 4.forward selection 5.score comparision.
2.make sure that dataset should be in the numbers format to build the ML model. If any text present in the dataset then by using label encoder and onehot encoder we should create the dummy variables.
3.model will be used dummy variable instead of text.

1.	Simple linear regression : 
•	it is model where you can find only you dataset having combination of the dependent and independent variable 
•	Which is y=bo+x*b1
•	 here B0 is constant and b1 is coeffient  of X and X is value of indepent variable .
2.Multiple linear regression: 
•	where dependent variable depends on more than one independent variable then we should go for this model. 
Y=b0+x1*b1+x2*b2+x3*b3…….xn*bn



