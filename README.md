# credit-risk-classification

The purpose of this analysis is to evaluate the effectiveness of a linear regression machine learning (ML) model when predicting healthy vs high-risk loans from financial data.

Credit Lenders would benefit from this type of analysis, as they like to manage their loan portfolios more effectively by being able to predict
the likelihood of defaulting loans. 


### Summary

As seen from these evaluation metrics, Logistic Regression
does quite an excellent job in predicting healthy loans with a very high
precision and recall for the healthy loans. There is, however, slightly reduced
performance in the precision regarding the prediction of the high-risk loans,
meaning there are instances of healthy loans being mislabeled as high risk.


### Recommendation

This model is appropriate if the objective function would be
to minimize the misclassification of healthy loans; however, it does need a
scaler.

Further model tuning or the use of models such as Random
Forest or SVM will give better precision and recall for the high-risk class


For data science analysis, review [Credit Risk Classification jupyter notebook](Credit_Risk/credit_risk_classification.ipynb).


To review the data, check [Lending Data](Credit_Risk/Resources/lending_data.csv).
