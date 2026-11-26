# Machine Learning Projects

A collection of hands-on Machine Learning projects covering classification, regression, and Natural Language Processing (NLP). These projects demonstrate the complete machine learning workflow, from data preprocessing and feature engineering to model training, evaluation, and visualization, using Python and Scikit-Learn.

## Projects Overview

## 1. Multi-Class Benchmark Classification Pipeline (Iris / Wine)

Objective: Build and evaluate supervised classification models using benchmark datasets such as Iris or Wine.

Key Tasks
- Load and explore datasets using Pandas.
- Perform Exploratory Data Analysis (EDA) and visualization using Seaborn.
- Normalize features using StandardScaler.
- Split the data into training and testing sets (80/20).
- Train Logistic Regression and Decision Tree classifiers.
- Evaluate and compare model performance.

Models
- Logistic Regression
- Decision Tree Classifier

Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Tools: Python, Pandas, Scikit-Learn, Seaborn, Matplotlib

---

##2. Real Estate Housing Price Prediction (Ridge & Lasso Regression)

Objective: Predict median house values using the California Housing dataset and compare linear regression models with regularization.

Key Tasks
- Load and explore the California Housing dataset.
- Handle missing values, if present.
- Perform feature engineering, including interaction features where useful.
- Analyze feature correlations using a heatmap.
- Standardize numerical features and encode categorical features, where applicable.
- Train and compare regression models.
- Tune hyperparameters using GridSearchCV.
- Visualize predicted vs. actual values and residuals.

Models
- Ordinary Least Squares (OLS) Linear Regression
- Ridge Regression (L2 Regularization)
- Lasso Regression (L1 Regularization)

Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Tools: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, GridSearchCV

---

## 3. NLP Sentiment Classification on Customer Reviews (TF-IDF)

Objective: Process customer or movie reviews and classify their sentiment as positive or negative using text classification.

Key Tasks
- Load the review dataset.
- Clean text by removing HTML tags, punctuation, and unnecessary content.
- Convert text to lowercase and remove stopwords.
- Tokenize text and apply stemming or lemmatization.
- Convert text into numerical features using TF-IDF.
- Train and compare sentiment classification models.
- Create a prediction helper to test custom reviews.

Models
- Multinomial Naive Bayes
- Logistic Regression

Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Classification Report

Tools: Python, Pandas, NLTK, Regular Expressions, Scikit-Learn, TF-IDF

---

 Tech Stack

- Programming Language: Python
- Data Processing: Pandas, NumPy
- Machine Learning: Scikit-Learn
- Natural Language Processing: NLTK, TF-IDF
- Data Visualization: Matplotlib, Seaborn
- Development Environment: Jupyter Notebook

 Machine Learning Workflow

1. Data Collection
2. Data Exploration (EDA)
3. Data Cleaning and Preprocessing
4. Feature Engineering and Feature Scaling
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Visualization and Prediction

## Learning Outcomes

- Understand supervised Machine Learning workflows.
- Perform data cleaning, preprocessing, and exploratory data analysis.
- Apply feature scaling and feature engineering techniques.
- Train and evaluate classification and regression models.
- Perform text preprocessing and TF-IDF vectorization.
- Compare models and interpret their performance.
- Visualize data and model results.

## Future Improvements

- Optimize hyperparameters and explore additional algorithms.
- Apply cross-validation for more reliable evaluation.
- Save trained models for reuse.
- Build user-friendly interfaces for predictions.
- Deploy selected models as web applications or APIs.

## Author

Onkar Purjalkar

Machine Learning | Data Science

