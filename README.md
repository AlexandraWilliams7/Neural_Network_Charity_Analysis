# Neural_Network_Charity_Analysis
## Overview
### Purpose
### Results 

#### Preprocessing
- What variable(s) are considered the target(s) for your model?

The "IS_SUCCESSFUL" column is the target for the model. 

- What variable(s) are considered to be the features for your model?

The "APPLICATION_TYPE, AFFLIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, AND ASK_AMT" columns are all features for the model.

- What variable(s) are neither targets nor features, and should be removed from the input data?

The EIN and Name variables were removed because they were neither targets nor features for the model.

#### Compile, Train, and Evaluate
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

There were two layers used. one layer had 80 neurons and the other had 30 neurons. 
ReLU was selected because it works well with positive nonlinear data.
Sigmoid was selected because there is binary classification in the data.

- Were you able to achieve the target model performance?

The model did not achieve the 75% target. The accuracy for the model was 73%. 

- What steps did you take to try and increase model performance?

To increase the model's performance the following steps were taken:

1. Dropped the 'SPECIAL_CONSIDERATIONS' Column.
2. Increased both hidden layers.
3. Added a third hidden layer.
4. Changed the output activation to Tanh.

### Summary
After making all the adjustments to the model, the model still did not reach the 75% target. The model only ran a 73% accuracy. In the future, the random forest model may work better. The random forest will be combat overfitting, put order to variables, handle the large dataset, and will run with deleting variables. It was also handle the outliers. 