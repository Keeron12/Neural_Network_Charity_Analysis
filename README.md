# Neural_Network_Charity_Analysis

## Overview
The purpose of the analysis was to use machine learning and neaural networks to predict wether applicants will be successful if funded.
## Results

### Data Preprocessing
- The variable considered as the target was IS_SUCCESSFUL
- The variables considered features are APPLICATION_TYPE, AFFILIATION,
CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, ASK_AMT, SPECIAL_CONSIDERATIONS
- The variables that need to be removed are EIN, NAME

### Compiling, Training, and Evaluating the Model
- I added 2 layers of neurons. One with 6 units and the other with 8 units. The activation function where relu for the layers and sigmoid for the output. I chose 6 and 8 after testing different amount of units per layer to improve the accuracy. I chose relu since the input classifications where nonlinear. I chose sigmoid, since we wanted a binary output of yes or no
- I was not able to achieve the target model performance
- I tried changing the amount of neuron combinations to improve the accuracy

## Summary
In conclusion, the overall results are not accurate enough to to use in predicting wether a charity would be successful if receiving funding. A different model to that could be used is SVM. SVM could be used because it can take in multiple data types like the ones provided in the data.