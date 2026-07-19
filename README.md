# 🌳 Decision Tree Regression & Classification

A Machine Learning project demonstrating the implementation of **Decision Tree Regression** and **Decision Tree Classification** using Scikit-learn. The project includes model training, hyperparameter tuning, visualization, feature importance analysis, and performance evaluation.

## 📌 Project Overview

Decision Trees are versatile machine learning algorithms that can solve both regression and classification problems.

This project demonstrates:

- Decision Tree Regression
- Decision Tree Classification
- Hyperparameter tuning
- Feature importance analysis
- Tree visualization
- Performance comparison

## 🎯 Objectives

- Predict continuous values using Decision Tree Regression.
- Predict class labels using Decision Tree Classification.
- Understand tree structure.
- Evaluate model performance.
- Analyze important features.

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## 📂 Project Structure

```
Decision_Tree/
│
├── screenshots/
│   ├── regression_tree.png
│   ├── classification_tree.png
│   ├── XGBoost.png
│   └── confusion_matrix.png
│
├── data/
│   ├── Movie_regression.csv
│   └── Movie_classification.csv
│
├── DecisionTree.ipynb
└── README.md
```

## 📊 Dataset

The project uses a structured dataset containing multiple numerical and categorical features.

Typical preprocessing steps include:

- Handling missing values
- Encoding categorical variables
- Feature selection
- Train-test split

## ⚙ Workflow

### 1. Data Preprocessing

- Load dataset
- Clean data
- Encode categorical variables
- Feature engineering

### 2. Train-Test Split

Split the dataset into:

- Training Set
- Testing Set

### 3. Model Training

Regression:

- Decision Tree Regressor

Classification:

- Decision Tree Classifier

## 🔧 Hyperparameter Tuning

GridSearchCV is used to optimize parameters such as:

- max_depth
- min_samples_split
- min_samples_leaf
- criterion

This improves model performance and reduces overfitting.

## 📈 Evaluation Metrics

### Regression

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### Classification

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## 🌳 Decision Tree Visualization

The trained decision tree is visualized to understand:

- Decision rules
- Splitting criteria
- Leaf nodes
- Tree depth

## ⭐ Feature Importance

Feature importance is calculated to identify the most influential variables used by the model.

Visualization includes:

- Bar chart
- Ranked feature importance

## 📷 Results

The project demonstrates:

- Accurate regression predictions
- Effective classification performance
- Clear tree visualizations
- Feature importance analysis
- Hyperparameter optimization

## 📌 Future Improvements

- Random Forest
- Gradient Boosting
- XGBoost
- Cross-validation
- Model deployment using Streamlit
- Explainable AI (SHAP/LIME)
