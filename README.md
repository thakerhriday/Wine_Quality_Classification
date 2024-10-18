# Wine_Quality_Classification
The objective of this project is to classify wine quality into three categories: "Not Good," "Average," and "Good" using machine learning classification models. We have used random forest classification.

Wine quality is a critical factor in the wine industry, influencing consumer preferences. The goal of this project is to predict wine quality based on physicochemical properties using classification techniques.

The challenge lies in accurately predicting wine quality using machine learning techniques while handling class imbalance, as the majority of wines in the dataset are classified as "Average."
![image](https://github.com/user-attachments/assets/2232b6c6-28e6-443a-9dab-07e92b81f3ee)

**About the Data Set**

The dataset used is the Wine Quality Dataset from the UCI Machine Learning Repository, containing physicochemical properties of red wine.

Features: Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Chlorides, Free Sulfur Dioxide, Total Sulfur Dioxide, Density, pH, Sulphates, Alcohol
Target variable quality was mapped to "Not Good" (3, 4), "Average" (5, 6), and "Good" (7, 8).

**Methodology**

Scaling the fetures values was done using min-max Scaling, handling class imbalance was done using SMOTE (Synthetic Minority Over-sampling Technique).

Three classification models were tested: Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest.

Models were evaluated based on accuracy  as primary factor and precision, recall, and F1 score as secondary factors.

**Logistic Regression Results**
![image](https://github.com/user-attachments/assets/007b8d47-81a1-4c13-8b5e-820e0b2d7815)

**KNN**
![image](https://github.com/user-attachments/assets/6639c636-848f-4f4b-83d5-8f3b403322fa)

**Random Forest**
![image](https://github.com/user-attachments/assets/9c975f13-12e6-4bfd-ad26-a95234a41afb)

**Cocnlusion**

Random Forest performed the best among the models tested, with the highest accuracy and F1 score.
Handling class imbalance with SMOTE improved model performance.
Future work could involve hyperparameter tuning or testing additional algorithms like Support Vector Machines (SVM).
