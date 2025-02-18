Titanic & Iris Dataset Classification

Overview

This repository contains two machine learning projects:

Titanic Survival Prediction - A Logistic Regression model to predict passenger survival based on various features.

Iris Species Classification - A Logistic Regression model to classify different species of the Iris flower.

Both projects involve data preprocessing, visualization, and model training using Python and scikit-learn.

Titanic Survival Prediction

Dataset

The dataset is loaded from tested (1).csv.

Features used include Sex, Embarked, Age, Pclass, etc.

Missing values in Age are replaced with the most frequent values (e.g., 21).

Unnecessary columns (Cabin, Ticket, Name) are removed.

Categorical variables (Sex, Embarked) are converted to numerical values.

Model

Logistic Regression is used to predict survival.

Data is split into 80% training and 20% testing sets.

Model accuracy is evaluated using accuracy_score.

A test prediction example is provided.

Visualization

Heatmaps show missing values.

Statistical summaries provide insights into the dataset.

Iris Species Classification

Dataset

The dataset is loaded from IRIS.csv.

Features include sepal length, sepal width, petal length, and petal width.

Target variable: species (Setosa, Versicolor, Virginica).

Model

Logistic Regression is used for classification.

Data is split into 80% training and 20% testing sets.

Model accuracy is evaluated, and a test prediction is demonstrated.

Installation

Ensure you have the required libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn ipywidgets

Usage

Clone the repository and run the scripts:

git clone https://github.com/aDp08/data-science-projects.git
cd data-science-projects
python titanic.py  # Run Titanic model
python iris.py     # Run Iris model

Results

The models provide predictions based on input data.

Accuracy scores validate model performance.

Data preprocessing ensures optimal results.
