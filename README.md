<div align="center">

# Student Performance Prediction Using Ridge & Lasso Regression

### Understanding Regularization Through Real Student Data, Feature Impact Analysis, and Machine Learning Visualization

</div>

---

# About This Project

This project explores how machine learning models behave when multiple student-related features influence academic performance at the same time.

Instead of using every available feature blindly, this notebook focuses on understanding:
- which features actually contribute to prediction
- how models react to unnecessary influence
- how coefficient values change
- and how Ridge & Lasso Regression control model behavior differently

The project was built using a student performance dataset containing features such as:
- Study Time Weekly
- Absences
- GPA
- Extracurricular Activities
- and other academic-related attributes

Only selected important features were used for model training to keep the workflow focused and interpretable.

---

# Why Ridge & Lasso?

While working with regression models, some features start dominating predictions while others add noise or unnecessary complexity.

This notebook demonstrates how:

### Ridge Regression
tries to reduce the effect of extremely large coefficients without removing features completely.

and how:

### Lasso Regression
goes a step further and can completely shrink less important feature coefficients close to zero.

Instead of memorizing theoretical definitions, this project visually explores their behavior through:
- model training
- coefficient comparison
- feature analysis
- regression graphs
- and prediction results

The goal was to understand these models practically through implementation and visualization.

---

# Workflow of the Project

---

## Step 1 — Import Libraries

Essential Python libraries were imported for:
- preprocessing
- visualization
- regression modeling
- and numerical computations

Libraries used:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Step 2 — Load & Explore Dataset

The dataset was loaded using Pandas and explored to inspect:
- feature structure
- numerical columns
- feature relationships
- and dataset quality

The notebook includes proper Markdown explanations to keep the workflow structured and beginner-friendly.

---

## Step 3 — Data Preprocessing

Basic preprocessing was performed before model implementation.

This included:
- checking data consistency
- handling feature selection
- preparing numerical input features
- and organizing the dataset for regression analysis

---

## Step 4 — Feature Selection

Instead of using all columns, only selected features were chosen such as:
- StudyTimeWeekly
- Absences
- GPA
- Extracurricular Activities

This helped focus the model on meaningful academic behavior patterns rather than unnecessary complexity.

---

## Step 5 — Feature Scaling

Data scaling was applied before training because Ridge and Lasso models are highly sensitive to feature magnitudes.

Standardization helped keep all features on a balanced numerical scale.

---

## Step 6 — Apply Ridge Regression

Ridge Regression was implemented to observe how coefficient values shrink while still keeping all features involved in prediction.

The model learned student performance trends while controlling over-aggressive coefficient growth.

---

## Step 7 — Apply Lasso Regression

Lasso Regression was then applied on the same dataset to compare behavior.

Unlike Ridge, Lasso started reducing the influence of weaker features much more aggressively.

This created a very interesting comparison between:
- feature importance
- coefficient reduction
- and prediction behavior

---

## Step 8 — Visualization & Graph Analysis

Separate graphs were created for:
- Ridge Regression
- Lasso Regression
- coefficient behavior
- prediction patterns
- and feature influence analysis

Visualizations were used to understand how both models react differently even when trained on the same student dataset.

---

## Step 9 — Final Comparison

At the end of the notebook, both models were compared side by side using:
- coefficient comparison tables
- prediction behavior
- and graphical analysis

This comparison helped explain how regularization changes machine learning model behavior in practical implementation.

---

# What This Project Demonstrates

This repository demonstrates:
- practical implementation of Ridge & Lasso Regression
- feature scaling workflow
- feature importance understanding
- regularization concepts
- coefficient comparison
- preprocessing workflow
- regression visualization
- and model comparison techniques

---

# Technologies Used

<div align="center">

| Technology | Role in Project |
|---|---|
| Python | Built the complete machine learning workflow |
| Pandas | Loaded and handled student dataset records |
| NumPy | Supported numerical operations and array processing |
| Matplotlib | Created regression graphs and visual analysis |
| Seaborn | Helped generate statistical visualizations |
| Scikit-learn | Applied Ridge, Lasso, scaling, splitting, and regression models |

</div>

---

# Key Learning Outcome

This project was developed to understand:
- how regularization works in real implementation
- how feature coefficients behave
- why scaling matters
- how Ridge and Lasso differ practically
- and how regression models can be analyzed visually instead of only theoretically

The notebook combines preprocessing, regression modeling, coefficient analysis, visualization, and comparison into a complete practical machine learning workflow.

---

<div align="center">

### Repository Includes

Feature Selection • Standardization • Ridge Regression • Lasso Regression • Coefficient Comparison • Visualization • Regression Analysis • Student Performance Prediction

</div>

---
