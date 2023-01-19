# Fraud Detection Model for Imbalanced Data
I built this machine learning model to detect credit card fraud in imbalanced data sets. This notebook will test different methods on skewed data - the idea is to compare if preprocessing techniques work better when there is an overwhelming majority class that can disrupt the efficiency of our predictive model. It also showcases how to apply cross validation for hyperparameter tuning on different classification models. Models used are:
1. Logistic Regression
2. SVMs
3. Random Forest
4. Anomaly Detection Techniques


### Data
The data I used in this project is from the "Credit Card Fraud Detection" dataset on Kaggle (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

### Model
The model I used in this project is logistic regression.

### Challenges
One of the main challenges I encountered in this project was the imbalanced nature of the data. To counter this, I used cross-validation and resampling techniques.

Another challenge was the presence of outliers in the data. I handled these by using robust scalers during preprocessing.

Finally, choosing the appropriate classification metric was also a challenge, as the data was highly imbalanced. I ultimately decided to use precision and recall as my evaluation metrics.

### Results
My model achieved a recall of 93% on the test data. This demonstrates its effectiveness at identifying fraudulent credit card transactions while minimizing the number of false negatives.
