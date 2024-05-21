# XGBoost-s-Impact-on-Fraud-Detection
### Fraud Detection Model Evaluation and Comparison
Objective:
The primary objective of this assignment is to develop a robust fraud detection model utilizing a dataset containing transactional information. The goal is to predict whether a transaction is fraudulent or not based on various features such as transaction category, amount, gender, and geographical details.

Dataset Description:
Size: 555,719 rows, 13 columns
Features: Initially included information such as category, transaction amount, gender, city, state, zip code, latitude, longitude, city population, occupation, merchant latitude, merchant longitude, and a binary label indicating whether the transaction is fraudulent or not.
Preprocessing: Columns such as 'city', 'state', 'zip', 'latitude', 'longitude', 'city_pop', and 'job' were dropped to streamline the dataset for model training.
Model Development and Evaluation:
Random Forest Model: Initially employed, yielding an accuracy of 99.76%. While precision for non-fraudulent transactions was perfect, there was room for improvement in detecting fraudulent ones.
Model Comparison: Gradient Boosting, Logistic Regression, and XGBoost models were implemented. Logistic Regression demonstrated competitive performance with an accuracy of 99.76% and significantly faster execution time compared to Random Forest and Gradient Boosting models.
Performance Metrics: Precision, recall, F1-score, and support were computed and summarized in a classification report for each model. Visual aids including confusion matrix, precision-recall curve, ROC curve, and feature importance plots were generated to facilitate a comprehensive understanding of model performance and behavior.
XGBoost:
Performance: XGBoost showcased competitive performance in fraud detection.
Advantages: XGBoost is known for its high performance, scalability, and efficiency in handling large datasets.
Model Interpretability: XGBoost provides feature importance scores, aiding in understanding the impact of each feature on the predictions.
Conclusion:
Through rigorous evaluation and comparison, this assignment underscores the significance of exploring multiple models for fraud detection tasks. While Random Forest initially exhibited high accuracy, alternative models like Logistic Regression and XGBoost proved to be both efficient and effective. XGBoost, in particular, showcased competitive performance and is favored for its scalability and efficiency. The assignment highlights the importance of not only accuracy but also computational efficiency in deploying fraud detection systems in real-world scenarios.
