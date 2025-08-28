# 1.Heart-disease-prediction-using-Machine-Learning
This project focuses on predicting the likelihood of heart disease using Machine Learning models. The dataset contains various health-related attributes (such as age, cholesterol, blood pressure, etc.), and the goal is to build an accurate classifier that can assist in early detection of heart-related issues. 

# 2. Features

Preprocessing of the dataset (handling missing values, scaling, and encoding).

Implementation of multiple ML models:

Logistic Regression

Random Forest

Gradient Boosting

Model comparison based on Accuracy, Precision, Recall, F1-score, and ROC-AUC.

Visualization of results using:

Confusion Matrix

ROC Curve

Best performing model is saved for future predictions.

Predictions are exported into a CSV file.
 
# 3. The dataset used is heart.csv, which contains patient medical records with the target variable:

0 → No Heart Disease

1 → Presence of Heart Disease 

# 4.  Tech Stack

Python

Jupyter Notebook

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, joblib

# 5. Results

The Random Forest Classifier achieved the best performance with 100% accuracy on the test set (in this dataset).

Generated plots: Confusion Matrix & ROC Curve. 

# 6.Future Work

Hyperparameter tuning for more robust models.

Deploying the model using Flask / FastAPI.

Building an interactive web app with Streamlit.

# 7.output picture 
<img width="1317" height="1101" alt="confusion_matrix_rf" src="https://github.com/user-attachments/assets/4852b747-5e22-450c-a781-80707eacd4a7" />
<img width="1697" height="1101" alt="roc_curve" src="https://github.com/user-attachments/assets/8db80846-b710-417e-8113-748265869cd6" />



