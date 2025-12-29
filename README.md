# Exploring Titanic Survival with Classification Models

# Overview

This project focuses on evaluating and preparing data to build classification models that predict passenger survival on the Titanic. Using the Titanic dataset from the Seaborn library, I explore data quality issues, handle missing and inconsistent values, and engineer relevant features. Multiple classification algorithms are trained and compared to assess their ability to predict the target variable (survived) and to better understand the factors associated with passenger survival.

The notebook walks through data exploration, preprocessing, model training, model tuning and performance evaluation.

# Objectives
- Explore data and basic statistics
- Impute missing values for age
- Prepare data for logistic modeling
- Build and evaluate predictive models (logistic, SVN, and decision tree) for Titanic survival
- Tune the Support Vector Machine (SVM) model.

# Dataset
**Titanic Dataset** Seaborn library


# Dependencies
This project uses the following Python libraries:

```
pandas
numpy
seaborn
scikit-learn
matplotlib
```

Install third-party dependencies with:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Model Evaluation

Model performance is evaluated using metrics such as:
- Precision
- Recall
- Accuracy

These metrics are used to compare models and assess predictive accuracy.

# Results & Insights

Key findings include:
- In addition to prioritizing women and children, passengers in higher classes were more likely to survuve in the Titanic
- Without scaling, the out-of-the-box Logistic model had better performance than the deicision tree or SVM model
- SVM is sensitive to scale; the model greatly improved after inputs were scaled. 