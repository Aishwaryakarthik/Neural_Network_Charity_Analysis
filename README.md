# Neural_Network_Charity_Analysis

Using Machine Learning to Predict Success of a Charity's Investment

The goal of this analysis is to create a neural network model that is able to predicting whether applicants will be successful if funded by Alphabet Soup. The dataset includes more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Overview of the analysis

Alphabet Soup, an organization engaged in the funding of charitable endeavours seeks to realize the best outcome of all their investments. The project was to help Beks of Alphabet Soup develop a machine learning model based on neural networks which uses binary classification to predict if an organization will be successful or not when sponsored.

## Results

The analysis involved the use of data from Alphabet Soup's business team. The CSV document entailed information on 34,000 organizations that have received funding from Alphabet Soup.

### Deliverable 1: Preprocessing Data for a Neural Network Model

A column labeled 'IS_SUCCESSFUL' in the tabular dataset showed whether an organization was successful or not upon sponsorship. Since this tells the outcome of funding or whether the money was used effectively, this variable therefore served as the target for the model's predictions.

Upon review of the remaining metadata on the organizations, nine other data points were determined as input variables for the model. The following variables were used as the features for the model.

1.APPLICATION_TYPE,

2.AFFILIATION,

3.CLASSIFICATION,

4.USE_CASE,

5.ORGANIZATION,

6.STATUS,

7.INCOME_AMT,

8.SPECIAL_CONSIDERATIONS,

9.ASK_AMT

The initial Deep-learning Neural Network involved 43 input features after encoding all the categorical features. As a deep learner, two hidden layers was used in the inital persuit. In an attempt to boost training, twice the amount of input(80 neurons) was used in the first layer. The second layer had 30 neurons and a single neuron for the output layer. The Relu function was used to activate the first and second layers. As a binary classifier the Sigmoid function was the best to be used to activate the output layer.

<img width="814" alt="merged_df_mod19_deliver1" src="https://user-images.githubusercontent.com/99555513/179275362-fd1035b0-a483-45a7-ac74-fd6f62ea2b34.png">


### Deliverable 2: Compile, Train, and Evaluate the Model

Using your knowledge of TensorFlow, you’ll design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. You’ll need to think about how many inputs there are before determining the number of neurons and layers in your model. Once you’ve completed that step, you’ll compile, train, and evaluate your binary classification model to calculate the model’s loss and accuracy.

<img width="599" alt="nn_summary" src="https://user-images.githubusercontent.com/99555513/179275738-c8cc9726-b60d-41be-ab2a-be489db4a937.png">


### Deliverable 3: Optimize the Model

Optimize your model in order to achieve a target predictive accuracy higher than 75% by using any or all of the following:

Adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:

1.Dropping more or fewer columns.

2.Creating more bins for rare occurrences in columns.

3.Increasing or decreasing the number of values for each bin.

4.Adding more neurons to a hidden layer.

5.Adding more hidden layers.

6.Using different activation functions for the hidden layers.

7.Adding or reducing the number of epochs to the training regimen.

## Summary

The model didnot achieve the target accuracy of 75% or more after attempts at improving it. It is however recommended that additional data might change the results since the model was tuned only on what was available. The fact that a Deep-Learning model could not achieve the desired results doesnot also mean that it is not achievable. An alternative will be compare performance of this model with an other machine learning model like RandomForestClassifier to evaluate performance.

