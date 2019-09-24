# diabetes
This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes,
based on certain diagnostic measurements included in the dataset.
Several constraints were placed on the selection of these instances from a larger database. 
In particular, all patients here are females at least 21 years old of Pima Indian heritage.
The datasets consists of several medical predictor variables and one target variable, Outcome. 
Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age.
We’ll be using Python and some of its popular data science related packages.
First of all, we will import pandas to read our data from a CSV file and manipulate it for further use. 
We will also use numpy to convert out data into a format suitable to feed our classification model.
We’ll use seaborn and matplotlib for visualizations. We will then import classifier algorithm from keras. 
This algorithm will help us build our classification model.we will get the predection of outcome,and get the confusion matrix
