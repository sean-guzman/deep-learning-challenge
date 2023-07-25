# deep-learning-challenge

Sean Guzman

Rutgers Data Sciences Bootcamp, Module 21 Challenge (25 July 2023)

## Overview
The purpose of this challenge is to create a deep learning model that can help select the applicants for funding with the best chance of success in their ventures for Applebet Soup, a non-profit organization.  we use Python (Jupyter Notebook) and load in a dataset and use the features to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

- Step 1: Preprocess the Data
    - Targets: IS_SUCCESSFUL
    - Features: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
    - Removed: EIN, NAME

- Step 2: Compile, Train, and Evaluate the Model
    - 1st Hidden Layer: 80 neurons, relu
    - 2nd Hidden Layer: 30 neurons, relu
    - Output Layer: 1 neuron, sigmoid
    - Number of Features: 43
    - Accuracy: 72.75%

- Step 3: Optimize the Model
    - 1st Hidden Layer: 150 neurons, relu
    - 2nd Hidden Layer: 100 neurons, relu
    - 3rd Hidden Layer: 50 neurons, relu
    - 4th Hidden Layer: 25 neurons, tanh
    - Output Layer: 1 neuron, sigmoid
    - Number of Features: 104
    - Accuracy: 76.3%

## Results
In the optimized model, features were increased from 43 to 104 by including NAME.  The model was also given two additional hidden layers with neurons increased overall and the accuracy improved from 72.75% to 76.3%, achieving target predictive accuracy higher than 75%.
