# Supervised-Learning-Challenge: Credit Risk Evaluator

### Background

* Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. This notebook aims to create machine learning models to classify the risk level of loans using the (#1) **Logistic Regression**, and (#2) **Random Forest Classifier**.

### Score Results (Logistic Regression vs. Random Forest Classifier):

#### Logistic Regression Scores (Unscaled)
Training Data Score: 0.9920724996560737
<br>
Testing Data Score: 0.9920037144036319

#### Random Forest Classifer (Scaled)
Training Score: 0.9973689640940983
<br>
Testing Score: 0.9915910028889806

### Model Comparison Reflection
The resulting scores between the training and testing data on the **logistic regression** (unscaled) model are closer, with only 0.00007 difference, compared the to the resulting scores using the **random classifier** (scaled) model with 0.0057 difference.  The diminutive difference between the two model suggests that any of the two models can be used to predict the risk level of loans. Between the two, logistic rogression model appear to be a better model.
