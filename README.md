# Neural_Network_Charity_Analysis
Module 19: Neural Networks and Deep Learning Models
### Project Overview
Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
### Results
###### Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
    - `IS_SUCCESSFUL` column is the target for this model
2. What variable(s) are neither targets nor features, and should be removed from the input data?
    - Columns `EIN` and `NAME` have been dropped / removed
3. What variable(s) are considered to be the features for your model?
    - Remaing columns are the features in this model
###### Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - I chose to change the activation function and neurons to increased the model's performance
        - Layer1 120 neurons with a relu function
        - Layer2 70 nuerons with a relu function
        - Layer3 50 neurons with a linear function
2. Were you able to achieve the target model performance?
    - Target module performance was 75%, after many tries I was only able to achieve 73%
3. What steps did you take to try and increase model performance?
    - I used used the following adjustments to acheive the target predictive accuracy (Some components were better as they were and changed back to the original code)
        - Adjusting the input data to ensure that there are no variables or outliers that are causing confusion in the model, such as:
            - Dropping more or fewer columns.
            - Creating more bins for rare occurrences in columns.
            - Increasing or decreasing the number of values for each bin.
        - Adding more neurons to a hidden layer.
        - Adding more hidden layers.
        - Using different activation functions for the hidden layers.
        - Adding or reducing the number of epochs to the training regimen.

![image1](https://github.com/robyndook/Neural_Network_Charity_Analysis/blob/7f18bb3c0a6096fea3b2fc8df5f76fbb13515a4d/Images/2022-05-07_14-57-20.jpg)

![image](https://github.com/robyndook/Neural_Network_Charity_Analysis/blob/7f18bb3c0a6096fea3b2fc8df5f76fbb13515a4d/Images/2022-05-07_14-57-57.jpg)

### Summary
By removing noisy variables, adding neurons and hidden layers I was about to predidict whether a donation is successfull by an accuract of 0.7250 and Loss of 0.5571
###### Recommendation
Use a Random Forest Classifier to determine the inport input variables
<!--
Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing
What variable(s) are considered the target(s) for your model?
What variable(s) are considered to be the features for your model?
What variable(s) are neither targets nor features, and should be removed from the input data?
Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
Were you able to achieve the target model performance?
What steps did you take to try and increase model performance?
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
-->
