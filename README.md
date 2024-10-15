# Data for HR

## The Right Bargain
A lot of times it so happens that the HR of the company is confused whether to retain a particular employee by giving a raise or whether the employee is going to stay no matter if he/she is given a raise or whether to simply let that employee go.
* How to make an informed decision?
* What is the necessary data required to make this informed decision?
* How can we use this data to improve the work culture of the company so that we don't lose on a good employee?
* When to let go off a good employee?
* When to let go off a bad employee?
* Or the basic of all questions : How do you define a good employee or a bad employee?

Let the Data Scientist come to your rescue!

## The approach to the solution
Following are the steps that I will be using to address this problem and ultimately finding a solution this problem:
* First thing first, I will try to know more about my dataset first. What all variables my dataset contains, what are the type of these variables, are there any duplicate values?, are there any null values?, are there any type of outliers in any kind of variables?
* Then I will analyze my data. Most probably I will be using visualization to explore and get insights into my dataset. Sometimes you find answers in this step only.
* Because there's a requirement of a machine learning model, there are certain things that should be known before the model could be even built. Like is there any class imbalance that exists, are there any string type labels that needs to be encoded. Also we need to split our data into data used for training and data used for testing so that we can do some model validation.
* Because there are different ways to classify a model, we will build different models: Logistic Regression, Decision Tree, Random Forest. We will then evaluate each and every model on the test data using different metrics like accuracy, precision, recall and F1 score, and then choose the best model out of them.
* Once the model is chosen, we will see which variables matter the most when taking a decision to retain or let go off an employee.
* Finally, we will give some insights of what can be done by the HR to improve the overall work culture or environment of the company so that the employees stay motivated and how we can make the most out of the available resources.
