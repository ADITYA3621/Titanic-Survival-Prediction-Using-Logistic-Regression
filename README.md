# Titanic-Survival-Prediction-Using-Logistic-Regression
The Titanic survival prediction project attempts to predict, based on a variety of features, whether or not a passenger on the Titanic survived by using machine learning algorithm logistic regression.

#The dataset used for this project usually contains information about :

PassengerId: A unique identifier for each passenger.
Age: The age of the passenger.
Fare: The amount of money paid for the ticket.
Sex: The gender of the passenger (male or female).
SibSp: The number of siblings or spouses traveling with the passenger.
Parch: The number of parents or children traveling with the passenger.
Zero: It's not clear what this column represents. It seems to be a column with the name "Zero," but without more context, its purpose is uncertain.
Pclass: The passenger class, indicating the class of the ticket (1st, 2nd, or 3rd class).
Embarked: The port at which the passenger boarded the Titanic.
Survived: The target variable indicating whether the passenger survived (1) or not (0).

#Algorithm

With this dataset, I performd a binary classification task to predict the survival status of passengers based on the other features. The logistic regression algorithm can be applied for this purpose, taking into account the features such as age, fare, gender, family relations (SibSp and Parch), passenger class, and embarked port.

#Preprocessing

I had to preprocess the data, deal with missing values, encode categorical variables (such "Sex" and "Embarked"), and perhaps remove or add values to the "Zero" column if it wasn't necessary for the study before running the logistic regression model.
