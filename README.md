# Introduction

The idea of this project is to choose a machine learning model to predict the thickness of SiO2 layers based on 
spectroscopic elipsometry data. There were three chosen model evaluated: Decision Tree Regressor, Random Forest Classifier and Random Forest Regression. The final result was calculated based on mean of column "Thickness". 

# Results

The efficiency of models was analysed based on mean squared error and R^2 score. Mean squared error is used to calculate teh average squared difference between the predicted and the actual target values within a dataset. The lower MSE, the better model. R^2 score is also used in linear regression models. It is the amount of the variation in the output dependent attribute which is predictable from the input independent variable. The closer to one, the better. 

- Decision Tree Regressor

Firstly the simplest model was analysed. Decision tree regression is a machine learning technique that constructs a tree-like model to predict continous numerical values. It is divided to nodes and leafs. Child nodes embodies a particular range of values based on the split condition. The algorithm then repeat this process for each child node, recursively splitting the data further based on the best features and conditions.

After evaluating the accuracy it was concluded that it is too sensitive for the data. The differences between each training were too big which caused in unpredictability of the model. However, the plus was that we did not have to care about no values data. 

- Random Forest Classifier 

 Secondly, random forest classifier model was evaluated. The idea of this model is based on using multiple decision trees in order to make a prediction. Although it is less sensitive than only one decision tree and more precised, the project is not a classification problem but regression. 

- Random Forest Regression 

Here comes the winner. R^2 score for this model is always closed to one which makes it the best model overall. Interestingly, it is better for data to have some experimental files as well. 
