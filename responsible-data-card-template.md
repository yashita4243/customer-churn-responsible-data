Responsible Data Card

Dataset purpose
The dataset will be used to predict customer churn and help the company identify customers who may leave its service. The prediction should support decisions, not make decisions automatically.

Provenance and permission
The dataset is provided as customer-churn-training.csv. The original source, consent status, and usage permissions need to be verified.

Population and representation
The dataset represents the customers included in the training data. Missing groups and representation imbalance need to be checked.

Features and target
Input features will be used to predict the churn target. The exact columns and target label must be verified. Features containing future information must not be used for prediction.

Quality checks
Check missing values, duplicate records, outliers, class balance, and ensure that training and test data are properly separated.

Risks and safeguards
Potential risks include privacy violations, biased predictions, false positives, and false negatives. Use only authorized data, check model performance across relevant groups, and keep human review in important decisions.

Intended evaluation
Use existing business rules as a baseline. Evaluate Precision, Recall, F1-score, calibration, fairness, and false-positive and false-negative errors before deployment.
