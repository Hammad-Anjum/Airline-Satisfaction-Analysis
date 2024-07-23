# Airline-Satisfaction-Analysis

This project consists of analyzing the 'Airline Satisfaction' dataset that is available on kaggle. This project aims to uncover the hidden trends and patterns through data visualization, preprocess the data using scaling etc, and building and evaluating 7-8 different models.


## Dataset
The dataset is available at : https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction and contains 23 columns with 100,000+ rows. The columns are as follows:
- Gender: Gender of the passengers (Female, Male)
- Customer Type: The customer type (Loyal customer, disloyal customer)
- Age: The actual age of the passengers
- Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)
- Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)
- Flight distance: The flight distance of this journey
- Inflight wifi service: Satisfaction level of the inflight wifi service (0:Not Applicable;1-5)
- Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
- Ease of Online booking: Satisfaction level of online booking
- Gate location: Satisfaction level of Gate location
- Food and drink: Satisfaction level of Food and drink
- Online boarding: Satisfaction level of online boarding
- Seat comfort: Satisfaction level of Seat comfort
- Inflight entertainment: Satisfaction level of inflight entertainment
- On-board service: Satisfaction level of On-board service
- Leg room service: Satisfaction level of Leg room service
- Baggage handling: Satisfaction level of baggage handling
- Check-in service: Satisfaction level of Check-in service
- Inflight service: Satisfaction level of inflight service
- Cleanliness: Satisfaction level of Cleanliness
- Departure Delay in Minutes: Minutes delayed when departure
- Arrival Delay in Minutes: Minutes delayed when Arrival
- Satisfaction: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)

## Models 
After preprocessing and handling class imbalance, the following models were built and evaluated on the test set and test file:

### Logistic Regression
Accuracy score of testing set = 0.87 

Precision score of testing set = 0.87 

Recall score of testing set = 0.87 

F1 score of testing set = 0.87 

--------------------------------------
Accuracy score on testing file = 0.56 

Precision score on testing file = 0.31 

Recall score on testing file = 0.56 

F1 score on testing file = 0.4 

## Random Forest 
Accuracy score of testing set = 0.97 

Precision score of testing set = 0.97 

Recall score of testing set = 0.97 

F1 score of testing set = 0.97 

-----------------------------------
Accuracy score on testing file = 0.96 

Precision score on testing file = 0.96 

Recall score on testing file = 0.96 

F1 score on testing file = 0.95 


### Decision Tree 
Accuracy score of testing set = 0.95 

Precision score of testing set = 0.95 

Recall score of testing set = 0.95 

F1 score of testing set = 0.95 

-----------------------------------
Accuracy score on testing file = 0.87 

Precision score on testing file = 0.87 

Recall score on testing file = 0.87 

F1 score on testing file = 0.87 

### K-Neighbors 
Accuracy score of testing set = 0.93 

Precision score of testing set = 0.93 

Recall score of testing set = 0.93 

F1 score of testing set = 0.93 

------------------------------------
Accuracy score on testing file = 0.75 

Precision score on testing file = 0.75 

Recall score on testing file = 0.75 

F1 score on testing file = 0.75 

### SVM 

Accuracy score of testing set = 0.93 

Precision score of testing set = 0.93 

Recall score of testing set = 0.93 

F1 score of testing set = 0.93 

------------------------------------
Accuracy score on testing file = 0.44 

Precision score on testing file = 0.19 

Recall score on testing file = 0.44 

F1 score on testing file = 0.27 

### MLP 

Accuracy score of testing set = 0.95 

Precision score of testing set = 0.95 

Recall score of testing set = 0.95 

F1 score of testing set = 0.95 

----------------------------------------
Accuracy score on testing file = 0.46 

Precision score on testing file = 0.61 

Recall score on testing file = 0.46 

F1 score on testing file = 0.34 

### Naive Bayes

Accuracy score of testing set = 0.85 

Precision score of testing set = 0.86 

Recall score of testing set = 0.85 

F1 score of testing set = 0.85 

--------------------------------------

Accuracy score on testing file = 0.52 

Precision score on testing file = 0.6 

Recall score on testing file = 0.52 

F1 score on testing file = 0.48 



