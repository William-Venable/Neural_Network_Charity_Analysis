# Neural_Network_Charity_Analysis

## Project Overview
Using what we know about machine learning and neural networks, we'll use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup (AS).

## Analysis
### Data Preprocessing
  - What variable(s) are considered the target(s) for your model?
    - We need to analyze if our applicants will be successful if funded by AS. The target variable would be IS_SUCCESSFUL values in our data.
  - What variable(s) are considered to be the features for your model?
    - We would consider all other columns of data in the provided CSV to be considered the features for our model other than EIN and NAME.
  - What variable(s) are neither targets nor features, and should be removed from the input data?
    - EIN and NAME because they are neither targets or features.

### Compiling, Training, and Evaluating the Model
  - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - First I selected 3 hidden layers with 200 neurons in the first and 150 in the other two, but I thought that they weren't accurate enough so I switched to 4 hidden layers by adding one with 250.
  - Were you able to achieve the target model performance?
    - The model accuracy was only 73%, so unfortunately not.
  - What steps did you take to try and increase model performance?
    - I increased the amount of hidden layers I used to furhter the training model.

## Summary
In the end, we were unable to achieve our target model performance of 75% by only reaching 73%. Reasoning for this might be because there was not enough present data for the DLM to be accurate. Other machine learning tools such as the Logistic Regression model, or SVM might be a bit more accurate.
