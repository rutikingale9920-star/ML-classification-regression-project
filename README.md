# ML-classification-regression-project
A machine learning project implementing Decision Tree, Random Forest, Linear Regression, and Random Forest Regressor with preprocessing, model evaluation, accuracy comparison, confusion matrix, and visualizations.
Project Overview

Data preprocessing (handling missing values, encoding, scaling)

Model building for Classification & Regression

Algorithms used:

Decision Tree Classifier

Random Forest Classifier

Linear Regression

Random Forest Regressor

Visualization of results

Confusion matrix & accuracy comparison

Final evaluation and insights

📂 Project Structure
├── data/                     # Dataset used for training/testing  
├── notebooks/                # Jupyter notebook (.ipynb)  
├── models/                   # Saved models (optional)  
├── plots/                    # Graphs & confusion matrix images  
└── README.md                 # Project documentation

-----Technologies & Libraries-----

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

-----Algorithms Used & Justification-----
✔ Decision Tree

Simple, interpretable, works well for non-linear data, and requires minimal preprocessing.

✔ Random Forest

Ensemble model that reduces overfitting and improves accuracy using multiple trees.

✔ Linear Regression

Used for regression tasks where variables have linear relationships.

✔ Random Forest Regressor

Performs well on non-linear regression using ensemble learning.

🔧 Preprocessing Steps

Handling missing values

One-hot encoding for categorical features

Feature scaling (if needed)

Train-test split

Outlier detection (optional)

-----Evaluation Metrics-----

For Classification:

Accuracy Score

Confusion Matrix

Classification Report

ROC Curve (optional)

For Regression:

Mean Squared Error (MSE)

Mean Absolute Error (MAE)

R² Score

-----Results & Visualizations-----

Accuracy comparison chart

Confusion matrix heatmap

Decision tree plot

Regression prediction vs actual graph

(All graphs included in the plots/ folder.)

-----Conclusion-----

This project demonstrates how different machine learning models perform on the same dataset. Random Forest performed the best among the classifiers due to its ensemble nature, while Random Forest Regressor delivered superior results for regression tasks.

-----Future Enhancements-----

Hyperparameter tuning using GridSearchCV

Add XGBoost and SVM for further comparison

Deploy the model using Flask / Streamlit

Add CI/CD and model monitoring
