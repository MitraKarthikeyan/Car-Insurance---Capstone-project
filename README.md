# Car-Insurance capstone-project

## Dataset discription: 

* The columns are resembling practical world features.
* The outcome column indicates 1 if a customer has claimed his/her loan else 0.
* The data has 19 features from there 18 of them are corresponding logs which were taken by the company.

Dataset link: [Kaggle](https://www.kaggle.com/datasets/sagnik1511/car-insurance-data)

## Summary and findings:

1. After conducting significant data analysis, I experimented with various classification models to see how well they performed on the dataset. With accuracy, roc, precision, and recall score, I obtained quite decent results.
2. I have use SMOTE oversampling method for imbalanced classification data. *But I didn't stop there; using Grid Search, I fine-tuned the hyperparamters and viewed the classification report, which included ROC AUC and Precision-Recall curves for various models.
3. With that, I came to conclusion that Random Forest, SVC, and The Boosting Algoritm (AdaBoost, Gradient Boost, XGBoost) are models which are best fit for our dataset.
4. After Tuning the Hyperparameter XGBoost algorithm has the Highest Accuracy of exactly 85.45% & AUC of 0.92.
