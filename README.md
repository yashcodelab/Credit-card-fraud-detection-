# Credit-card-fraud-detection-
* Overview:-

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. With the rising number of online transactions, identifying and preventing fraudulent activities has become critical. This project utilizes a credit card transaction dataset to build a predictive model that can effectively distinguish between genuine and fraudulent transactions.

* Dataset:-

The dataset used in this project is a public dataset available on Kaggle. It contains transactions made by European cardholders in September 2013. The dataset has the following characteristics:
1. Rows: 284,807 transactions
2. Columns: 31 features, including
3. V1 to V28: Principal components obtained from PCA (due to confidentiality)
4. Time: Seconds elapsed between each transaction and the first transaction
5. Amount: Transaction amount
6. Class: Target variable (0 = Non-Fraudulent, 1 = Fraudulent)

Project Workflow

1. Data Preprocessing-

Loaded the dataset using Python libraries (Pandas, NumPy).

Handled missing values and checked for data imbalances.

Scaled features using StandardScaler to improve model performance.

2. Exploratory Data Analysis (EDA)-

Analyzed the distribution of fraudulent vs. non-fraudulent transactions.

Visualized correlations between features using heatmaps.

Plotted transaction amount and time to identify patterns in fraudulent activities.

3. Model Building-

Algorithms Used:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Addressed data imbalance using techniques like SMOTE (Synthetic Minority Over-sampling Technique).

4. Model Evaluation-

Evaluated model performance using:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

Achieved an accuracy of over 95% with the Random Forest model and balanced precision recall for better fraud detection.

5. Results-

Identified key features that contribute most to fraud detection.

Random Forest and XGBoost models provided the best results in detecting fraudulent transactions.

The final model balances precision and recall to minimize false positives and negatives

* Technologies Used:-

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook for development and visualization

SMOTE for handling data imbalance

Random Forest and XGBoost for classification


* Results and Discussion-

The model achieved high accuracy with good precision and recall balance.

Future improvements could include deep learning techniques or integrating real-time fraud detection systems.

* Contributing

Feel free to fork the repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.
