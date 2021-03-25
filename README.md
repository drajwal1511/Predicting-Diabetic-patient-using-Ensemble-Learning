# Predicting-Diabetic-patient-using-Ensemble-Learning
## Problem
The Objective of the Project is to diagnostically predict whether or not a patient has diabetes based on certain diagnostic measurements in the dataset. All patients are female of age >=21. 

## Ensembe Learning 
In statistics and machine learning, ensemble methods use multiple learning algorithms to obtain better predictive performance than could be obtained from any of the constituent learning algorithms alone.

## Constituent models/algorithms

### KNN
K nearest neighbors is a simple algorithm that stores all available cases and classifies new cases based on a similarity measure (e.g., distance functions). 

### Random Forest
Random forests or random decision forests are an ensemble learning method for classification, regression and other tasks that operate by constructing a multitude of decision trees at training time and outputting the class that is the mode of the classes or mean/average prediction of the individual trees.

### Logistic Regression
Logistic Regression, also known as Logit Regression or Logit Model, is a mathematical model used in statistics to estimate (guess) the probability of an event occurring having been given some previous data. Logistic Regression works with binary data, where either the event happens (1) or the event does not happen (0).

### GridSearch
Grid search is the process of performing hyper parameter tuning in order to determine the optimal values for a given model.
it is difficult to manually change the hyperparameters and fit them on the training data every time. It helps to loop through predefined hyperparameters and fit the estimator (model) on the training set. 
1. estimator
2. params -  list of parameters and the range of values for each parameter of the specified estimator. All you need to do is create a dictionary (variable params in my code) that has the hyperparameters as keys and an iterable that holds the options we need to try out.
3. cross validation - A cross validation process is performed in order to determine the hyper parameter value set which provides the best accuracy levels. variance problems is dealt with in cross validation.

## ScreenShots
### Distributions By Pregnancy
![image](https://user-images.githubusercontent.com/44205030/112432407-db475d80-8d66-11eb-9696-f75867972f49.png)
### Distributions by Glucose Level
![image](https://user-images.githubusercontent.com/44205030/112432440-e8fce300-8d66-11eb-9c45-662a918c3b4f.png)
### Distributions by Diastolic Level
![image](https://user-images.githubusercontent.com/44205030/112432523-0a5dcf00-8d67-11eb-9011-e003daa498f1.png)
### Distributions by Tricep 
![image](https://user-images.githubusercontent.com/44205030/112432559-16499100-8d67-11eb-9586-ffea4ca9a29f.png)
### Distribution by Insulin Level
![image](https://user-images.githubusercontent.com/44205030/112432596-219cbc80-8d67-11eb-9e6a-fa81a0599ec5.png)
### Distribution by BMI
![image](https://user-images.githubusercontent.com/44205030/112432625-2b262480-8d67-11eb-8bce-ac377e327ead.png)
### Distribution by Diabetic Pedigree Function
![image](https://user-images.githubusercontent.com/44205030/112432719-47c25c80-8d67-11eb-9257-2c4f9c59e93c.png)
### Distribution by Age
![image](https://user-images.githubusercontent.com/44205030/112432743-50b32e00-8d67-11eb-8034-f815fe35edc3.png)
### Comparison of KNN, Random Forest and Logistic Regression
![image](https://user-images.githubusercontent.com/44205030/112520930-f3989600-8dc1-11eb-93a5-c4e77694d52e.png)

## Conclusion
![image](https://user-images.githubusercontent.com/44205030/112520954-fa270d80-8dc1-11eb-870e-c6acb201d0fa.png)
The Score of ensemble model is more than the Individual score of constituent models
