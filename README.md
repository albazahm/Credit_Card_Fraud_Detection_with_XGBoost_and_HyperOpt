# Credit Card Fraud Detection with XGBoost and HyperOpt
A repository containing a notebook that explores the implementation of the XGBoost Classifier in the finance industry, specifically in credit card fraud detection. After building the XGBoost Classifier it will use the HyperOpt Library, an alternative to sklearn's GridSearchCV and RandomziedSearchCV algorithms, to tune the various model parameters with the goal of achieving the maximum f1-score for the classification of normal and fraud transactions. As part of the model evaluation, the f1-score metric will be computed, a confusion matrix will be constructed for the classification, a classification report will be generated and a Precision-Recall Curve plotted. Finally, feature importances will be computed and plotted based on both XGBoost's internal algorithm, as well as the SHAP implementation of feature importances.
