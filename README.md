

# Classification_Fraud_Detection
Fraud Detection Model using Python's Jupyter

## Source Data
[Credit Card Fraud Data](https://www.kaggle.com/mlg-ulb/creditcardfraud)


## Question: We want to catch fraudulent transactions, can we build a model to do so?

This model was coded in Jupyter notebook. The models used were Local Outlier Factor & Isolation Forest. Testing was done using random sampling of 10% of the data.

## Results

The accuracy for the model was 99.75% which would be considered very good. However, we see that it is missleading because we have so much more non fraudulent data that the models predicted perfectly. This outweighs the the fact that the model did poorly on predicting fraudulent activity.

The Isolation Forest performed better than the Local Outlier Factor, however, error rates were still significatly high. The total number of fraudulent cases in this sample was 49. The Isolation Forest model had a recall of 29%. That means the model was able to correctly identify 29% of all fraudulent cases or a total of 14 cases. The model had a precison of 28%, meaning that when it predicted a transaction what fraudulent it was correct 28% of the time.

These models would needed more tweaking of parameters because as of now if presented to a client they would nt be very happy. Customers would be called 70% of the time to verify if a transaction was fraudulent. 

## Why is this important for business?


