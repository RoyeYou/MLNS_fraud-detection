# MLNS_fraud-detection

Generate node inforamtion and use transaction features to do fraud detection.

Anti-money laundering (AML) regulations are essential in protecting financial systems, but they come with significant costs for institutions. The advance in machine learning algorithms shows great promise for fraud detection toolkits. In this project, we motivate the opportunity to apply machine learning algorithms for anomaly detection in financial transactions. Since the intrinsically private nature of financial transactions, we utilised a synthetic financial dataset to conduct experiments,  totalling 6,362,620 transactions, in which 8,213 illicit transactions are included. In this project we constructed directed graphs with 7 node features including amount, old balance of the sender, new balance of the sender etc. We show results from a binary classification task predicting illicit transactions using variations of Logistic Regression (LR), Random Forest (RF), and XGBoost. With the aim of decreasing False Negative Rates, we use F2 score as a main evaluation metric, and the findings provide good results 0.73 from XGboost in the (1:10) under-sampling technique. With the experiments, we inspire to include deep neural networks for future work.

The dataset is a kaggle dataset: https://www.kaggle.com/datasets/ealaxi/paysim1

