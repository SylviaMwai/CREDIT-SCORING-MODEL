# CREDIT-SCORING-MODEL

## 1. BUSINESS UNDERSTANDING

#### a) PERSPECTIVE
Credit scoring is a crucial process financial institutions employ to evaluate the probability of an applicant defaulting on a loan. This process enables lenders to make well-informed decisions regarding loan approval and lending terms. By analyzing various factors, financial institutions can estimate the applicant's creditworthiness, reducing the risk of bad loans and ensuring more accurate, data-driven lending decisions.

Machine learning models, particularly those for binary classification, play a significant role in predicting the likelihood of default to enhance decision-making. Logistic regression is commonly used for such tasks, but other models, like decision trees and random forests, can be considered to understand better the factors that predict default risk.

#### b) OBJECTIVES
The main objective of this project is to develop a predictive model that estimates the probability of loan default based on demographic and financial attributes. These attributes include:

i) Age

ii) Sex

iii) Job

iv) Housing status

v) Savings and checking account balance

vi) Credit amount

vii) Loan duration

viii) Loan purpose

The target variable in this project is defaulter, a binary classification that indicates whether an applicant has defaulted on a loan (bad) or not (good). This model aims to:

• Apply logistic regression as the primary method to handle the binary classification task.

• Consider additional machine learning models like decision trees and random forests to identify key predictors of default behaviour.

• Enable financial institutions to minimize the risk of bad loans through data-driven insights and more precise loan approval decisions.

Relevant objectives include

• Improving accuracy in predicting defaults

• Refining decision-making processes

• Expanding the analysis with multiple models to ensure robustness in prediction.

## 2. DATA MODELLING

The three main models tested were:

- *Logistic Regression*

- *Decision Tree Classifier*

- *Random Forest Classifier*

#### a) Technique Selected:

**Logistic Regression** was chosen as the final model for the following reasons:

• Logistic Regression provided a good balance of interpretability and performance with an accuracy of 72% on the test set.

• It outputs probabilities, which are essential for credit scoring to give confidence levels about whether an individual will default.

• The confusion matrix and classification report showed reasonable precision and recall for the non-defaulter class (though improvement is needed for defaulter prediction).

## 3. CONCLUSION

The logistic regression model provided a reasonable prediction accuracy of 72%, although it struggled with recall for defaulters, achieving only 13%. This may be due to class imbalance.

The Random Forest and Decision Tree models were also tested but did not outperform logistic Regression significantly. However, Random Forest did show promise in capturing the defaulter class more accurately than other models.

### Summary of Model Performance:
1. Logistic Regression:
- Accuracy: 72%

- Precision (Defaulter): 52%, Recall (Defaulter): 13%

2. Decision Tree:
- Accuracy: 62%

- Precision (Defaulter): 36%, Recall (Defaulter): 32%

3. Random Forest:
- Accuracy: 69%

- Precision (Defaulter): 46%, Recall (Defaulter): 19%
