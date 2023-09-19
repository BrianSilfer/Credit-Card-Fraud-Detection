# Project-4
Project 4 Proposal

Credit Card Fraud Detection

Data Source Used: Credit Card Transactions Fraud Detection Dataset
Link: https://www.kaggle.com/datasets/kartik2112/fraud-detection?select=fraudTrain.csv

Purpose:

The purpose of this project is to train and test a model on credit card transaction data to see whether or not a transaction was fraudulent using a Sequential machine learning model to predict a binary outcome or fraudulent or non-fraudulent. 

Project Steps:
Find Dataset- Learn and understand the variables within that data and how they will be explained within the scope of the project
Create Project Repository- Include Readme and Resources Folder. Google Collab will be used for my Jupyter notebook as the filesize for the 2 datasets are a total of 212MB. I will then upload the finished notebook to Github to skip the step of using local storage to run my analysis.
Data Cleaning: Clean, reformat, standardize, and normalize all data prior to modeling. This includes dropping any columns that are not helpful to predicting fraud and are purely informational.
Utilize spark to retrieve and manipulate data
Split data into test and training datasets
Create and train a model, optimizing it iteratively to achieve a 80% accuracy rating to predict whether a transaction is fraudulent or not.
Print the accuracy of the model
Draw conclusions regarding the model and its accuracy, ways that you improved the model, ways that made little to no improvement to the model. 

Conclusion:

I discovered that using machine learning models to predict fraud in credit card purchases can be highly valuable. I believe that the quality of the data is a huge factor in the overall predictive power of the model. The data source used in this project was created through a python package called faker and it creates credit card transaction data based on certain types of profiles. This dataset combined all of the possible card holder profiles into one dataset. With that being said, a sequential model with 1 input layer utilizing the relu activation function and 1 output layer utilizing the sigmoid activation function with 6 inputs. I used 50 and 25 epochs to train the model and they yielded the same accuracy score. This makes the 3rd model trained on 25 epochs a lot more efficient when it comes to training a model and if the dataset was larger, would take significantly less time to train then if 50 epochs were used. Through iterative steps to optimize the model, I found that adding an additional hidden layer to the model actually slightly hurt the accuracy score of the model. After creating several charts for categorical variables in my dataset, I discovered that


