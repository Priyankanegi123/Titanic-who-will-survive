# Titanic-who-will-survive
**ABSTRACT:**
This project is based on the survival prediction of the passengers on the RMS Titanic. One of the reasons for the loss of lives on that ship was the shortage of lifeboats for the passengers and crew. Although, some people were more likely to survive than others. In this ML model we will predict which passengers survived the tragedy.

**DATASET:**
The dataset contains the passengers name, age, gender, socio-economic class etc. The dataset has been divided into training and testing dataset. The training set has 891 examples and 11 features + the target variable(survived). Two of the features are float, five are integers and five are objects. Below is a list of the features:

•	PassengerId: unique id of a passenger

•	Pclass: Passenger ticket class.

•	Sex:  sex

•	Age: age in years 

•	Sibsp: number of siblings or spouses who aboard the titanic

•	Parch: number of parents or children who aboard the titanic

•	Ticket: ticket number

•	Fare: passenger fare

•	Cabin: cabin number

•	Embarked: port of embarkation

**DATA ANALYSIS:**
Feature conversion of data types from float to int64 and spotting of features containing missing values and replacing them with values. Analaysing on which feature the survival depends. 
Here are some insights we had after analysing the data: 

• Pclass, sex, cabin and embarked are categorical features. 

• Comparison of genders is important, as females are more likely to survive.

• The fare didn’t contribute much to the model.

**ALGORITHMS USED:**
The following problem is a classification problem so we used random classifier model as it works best for the model with an accuracy of 96.52
