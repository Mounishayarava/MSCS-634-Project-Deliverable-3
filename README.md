# MSCS-634 Project Deliverable 3  
## Classification, Clustering, and Pattern Mining

# Overview
This project applies data mining and machine learning techniques on the Titanic dataset to explore classification, clustering, and association rule mining. The goal is to analyze passenger survival patterns and uncover meaningful insights using predictive and unsupervised learning methods.


# Dataset
The dataset used in this project is the **Titanic dataset from Kaggle**, which contains passenger information such as age, sex, passenger class, fare, and survival status.

Target Variable:
- Survived (0 = No, 1 = Yes)


# Techniques Used

## 1. Data Preprocessing
- Handled missing values using median and mode imputation
- Encoded categorical variables using Label Encoding
- Removed irrelevant features
- Standardized numerical features


## 2. Classification Models
Two classification algorithms were implemented:

- Decision Tree Classifier
- k-Nearest Neighbors (k-NN)

Additionally, hyperparameter tuning was performed using GridSearchCV to optimize the Decision Tree model.

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve and AUC

## 3. Clustering
K-Means clustering was applied to identify hidden patterns in the dataset.

- Optimal clusters selected using Elbow Method
- PCA used for visualization of clusters in 2D space


## 4. Association Rule Mining
Apriori algorithm was used to extract frequent itemsets and generate association rules.

Metrics used:
- Support
- Confidence
- Lift

# Key Insights
- Passenger class and gender significantly influence survival chances
- First-class passengers had higher survival probability
- Clustering revealed distinct passenger groups based on socio-economic features
- Association rules identified meaningful relationships between survival and passenger attributes


# Real-World Applications
- Predictive modeling for survival or risk prediction
- Customer segmentation in business analytics
- Pattern discovery in healthcare and finance
- Recommendation systems using association rules


# Challenges
- Handling missing data in multiple columns
- Ensuring consistent preprocessing across models
- Selecting optimal number of clusters
- Interpreting association rules meaningfully


# Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- mlxtend


# Conclusion
This project demonstrates how classification, clustering, and association rule mining can be combined to extract meaningful insights from real-world datasets. The models provided useful predictions and revealed hidden patterns in the Titanic dataset.

#MSCS-634-Project-Deliverable-3
-ProjectDeliverable3
-README
