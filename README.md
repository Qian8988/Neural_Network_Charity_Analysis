# Neural_Network_Charity_Analysis

Module 19 Challenge


## Overview of the analysis:  

The purpose of this project is to use neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.



### Results:  

#### Data Preprocessing

 
The column IS_SUCCESSFUL is considered as the target for our model.

 
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT are the features for the model.

 
EIN and NAME have been removed from the input data.


#### Compiling, Training, and Evaluating the Model

 
This neural network model is made of two hidden layers with 80 and 30 neurons respectively.
The input data has 43 features.
 
The model accuracy is under 75%. This is not a satisfying performance.
To increase the performance of the model, I increased the number of neurons in hidden layer 1, then I increased the number of hidden layers to 3. I also tried linear, tanh, sigmoid for a combination of hidden layers and output layer.

### Summary 

The optimizing the initial model did not significantly improve its predictive accuracy.

My recommendation is trying to use a supervised machine learning model such as the Random Forest Classifier to combine a multitude of decision trees to generate a classified output and evaluate its performanc.

