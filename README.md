# machine-learning-nanodegree
This repository contains class assignments and projects from my completed Udacity's Machine Learning Nanodegree.

The following projects were worked on during the Nanodegree:

### Project 0 - Titanic Survival Exploration

In this project the goal was to predict whether a passenger survived given 
information about sex, age, class, ticket price, family members, and embarking location. At first, no 
machine learning algorithm is used to make the predictions resulting on an accuracy of about 80% on the training set.
However, when using ML models like Random Forest and Support Vector Classifiers, it was possible to boost accuracy on
the training set above 95%. By comparing it with performance from a top Kaggle entry, the accuracy expected on the test
set is around 80%. This is further validated by also doing a cross validation score analysis on the training set. 

### Project 1 - Predicting Boston Housing Prices

This is the first official project for the Machine Learning Engineer Nanodegree. The goal is to predict the housing prices
in Boston. The first part of the project is downloading and exploring the dataset. From a correlation map it is clear that
the percentage of the lower status has the strongest negative correlation with housing prices. After optimizing and
fitting a Decision Tree Regressor, two other key parameters are identified: the average number of rooms and the weighted
distances from employment centers in Boston. The next part of the notebook digs into how to systematically develop the model
and track the performance as a function of the max_depth parameter in the Regressor. Finally, a housing price is predicted
for a pre-determined client.

### Project 2 - Student Intervention System
This project  analyzes a dataset containing features and graduation status of 395 students. Multiple classification algorithms are 
compared to identify optimal predictive performance on student graduation status. Support Vector Machines (SVMs) repeatedly result in the best predictive performance for the training and testing sets. Tuning by doing a Grid Search Optimization on the 'C' and 'gamma' parameters results in a 83% graduation status prediction accuracy on the test set. An additional analysis is done to find key features determining student graduation status. By using the feature variance as a filter, it is possible to see that Age, Mother's Education, Father's Education, Going Out w/ Friends, Weekend Alcohol Consumption, Health Status, and Absences contain the majority of the information necessary to predict a student's graduation performance.  

### Project 3 - Creating Customer Segments
In this project consumption behavior of 440 customers is analyzed to determine their likely business operation/profile. The main product categories are Fresh, Milk, Grocery, Frozen, Detergents_Paper, and Delicatessen. The natural logarithm is applied to the dataset inorder to give the features a normal distribution. Afterwards, outliers in more than one feature are removed. To understand the underly customer structure, principal compnent analysis (PCA) is done on the transformed and cleaned dataset. The dataset is reduced to two PCA components before applying a K-Means clustering algorithm. Clustering shows that customers can be split into two types of business operations: Hotel/Restaurant/Cafe and Retailer.  

### Project 4 - Train SmartCab to Drive
The fourth project consits of implementing a learning algorithm to train an agent moving as a car in a simulated traffic environment. The goal is to construct a working Q-learning algorithm for the agent. To start building the algorithm, it is necessary to get the car to take valid actions such as turning, moving forward, and doing nothing. Next, a set of states is created to define the allowed states of the environment. During learning, an entry will be created and updated for every state the agent occupies and receives a reward. A decay function controlling the balance between exploring and exploitation will be used to converge to optimal actions. Once the full Q-learning algorithm is implemented, it is possible for the agen to learn how to safely and efficiently navigate the simulated city traffic. 

### Project 5 - Capstone: Predicting Educational Achievement Gaps
