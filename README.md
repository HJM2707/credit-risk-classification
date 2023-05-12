# credit-risk-classification


## An oppurtunity to Analyze high and low risk loans
### In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.


## Creating the Logistic Regression Model

### Procedure 
#### -- Data importation 
#### -- Data analyzing 
#### -- Extracting features and target value 
#### -- Splitting the Data in Train and test using train_test_split
#### -- Resampling and fitting the model

### Results

### Logistic model with default param


#### The precision score attain from the first model creation for healthy loans (0) shows score of 0.9964, with only few false positive indication. Model's accuracy for high-risk loans (1) is only 0.8746 with more false positives compared with healthy loans. Model's recall for healthy loans (0) scored for 0.9957. And the recall score for high-risk loans (1) is only 0.8928 that shows effect of false negative.

### Logistic model with resampled data


#### The accuracy score for healthy loans (0) has improved significantly to 0.9999 compared with original data . The resampling also boost the high risk loan (1) to 0.8725 and also have effect on the recall whihch scores 0.9968.
