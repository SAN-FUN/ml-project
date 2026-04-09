Task 1
Label: repeat_purchase_flag
This is the target variable to be predicted by the ML model,because it directly represents whether the customer made a repeat purchase within 30 days or not.

Data Leakage Column: discount_used_on_repeat_order
This column directly related with repeat purchase but our model prediction itself is whether customer repeat the purchase or not.Hence this column introduce leakage because this will not be available at prediction time and it affects the accuracy of model and its performance.

Task 2

1.Data analysis and  Data cleaning

Before training any model,we need to analyse the data,identify if any null values,outliers and make sure the data is clean before training the model

2.Data Splitup

Before training the model,we need to split the dataset like 70% for training data,15% test set and 15% for validation and final tuning.It is the most important step to get good accuracy in the model.
