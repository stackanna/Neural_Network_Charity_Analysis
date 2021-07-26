# Neural Network Charity Analysis

Click [HERE](https://github.com/stackanna/Neural_Network_Charity_Analysis/blob/f0d8455e9a2df45395834cab108da729d357b287/AlphabetSoupCharity.ipynb) to view [Neural Network Charity Challenge Analysis](https://github.com/stackanna/Neural_Network_Charity_Analysis/blob/f0d8455e9a2df45395834cab108da729d357b287/AlphabetSoupCharity.ipynb)

## Resources Used: Python & Google Collab

## Overview of Neural Network Charity Analysis

Bek is beginning her dive into neural networks! She is finally prepared to put her skills to work to assist in the foundation of how to predict where to make investments. With our knowledge of machine learning and neural networks, we utilized the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization. We have ten unique variables & columns that will be grouped together to help us distinguish this:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectively


![alt text](https://github.com/stackanna/Neural_Network_Charity_Analysis/blob/21e9802272a0e7cc00f1160ea6c4a1b88d039b07/Screen%20Shot%202021-07-25%20at%209.12.53%20PM.png)

Using our knowledge of TensorFlow, we designed a neural network, also known as a deep learning model, to create a binary classification model so that we can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. Assessing how many inputs there are before determining the number of neurons and layers in your model. We compiled, trained, and evaluated our binary classification model to calculate the model’s loss and accuracy.

# DATA PREPROCESSING

What variable(s) are neither targets nor features, and should be removed from the input data?
- The removed columns were EIN and NAME because they were just identification information.

# Compiling, Training, and Evaluating the Model:

How many neurons, layers, and activation functions did you select for your neural network model, and why?

8 neurons in layer 1, 5 neurons in layer 2 with an accuracy of roughly 73%. 

![alt text](https://github.com/stackanna/Neural_Network_Charity_Analysis/blob/283c7b0961224037a96aa815942bcdb5f7364d3e/Screen%20Shot%202021-07-25%20at%209.57.01%20PM.png)

Although we didnt achieve the 75% accuracy we were less than 2% away. 

![alt text](https://github.com/stackanna/Neural_Network_Charity_Analysis/blob/21e9802272a0e7cc00f1160ea6c4a1b88d039b07/Screen%20Shot%202021-07-25%20at%209.15.22%20PM.png)
