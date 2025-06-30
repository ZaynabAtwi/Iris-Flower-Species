# 🌸 Iris Flower Species Classification using Machine Learning

This repository contains a comprehensive implementation of a machine learning model to classify Iris flower species based on their physical features. The project is built and run on Google Colab and demonstrates the full data science pipeline—from data loading and exploratory analysis to model training and evaluation.

## 📌 Project Overview

The Iris dataset is a classic multivariate dataset introduced by the British biologist and statistician Ronald Fisher in 1936. It contains 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify each flower into one of three species:
- *Iris-setosa*
- *Iris-versicolor*
- *Iris-virginica*

This project:
- Loads and preprocesses the dataset
- Performs exploratory data analysis (EDA)
- Visualizes data distributions and relationships
- Applies several classification algorithms
- Compares model performance
- Evaluates the best-performing model using accuracy and confusion matrices

## 🔍 Key Features

- **Clean and modular code** implemented in a Google Colab notebook
- **EDA with visualizations** using `matplotlib`, `seaborn`, and `pandas`
- **Multiple ML algorithms**: Logistic Regression, K-Nearest Neighbors, Decision Trees, and Support Vector Machines
- **Model evaluation** using confusion matrix, classification report, and accuracy score
- **Well-structured and annotated notebook** for clarity and learning purposes

## 📁 Repository Structure
📦iris-flower-classification
┣ 📜README.md
┣ 📓iris_classification.ipynb ← Google Colab notebook (link below)


## 🧠 Technologies Used

- Python 3
- Google Colab
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)

## 📊 Dataset Description

| Feature        | Description           |
|----------------|-----------------------|
| Sepal length   | Length of the sepal (cm) |
| Sepal width    | Width of the sepal (cm)  |
| Petal length   | Length of the petal (cm) |
| Petal width    | Width of the petal (cm)  |
| Target         | Flower species: Setosa, Versicolor, Virginica |

The dataset is available directly via `sklearn.datasets.load_iris()`.

## 🧪 Model Performance

- Achieved high classification accuracy (typically >95%) with multiple algorithms.
- SVM and Decision Tree models performed particularly well on this dataset.
- Confusion matrices indicate clear class separability, especially for *Iris-setosa*.

## 📈 Sample Visualizations

- Pair plots showing feature distributions across species
- Correlation heatmap
- Box plots for univariate analysis
- Decision boundaries (where applicable)

## 🔗 Project Notebook

You can view and run the entire project using the following Colab link:  
👉 [Google Colab Notebook](https://colab.research.google.com/drive/1yJZb9NW76BzEZS1YIBdfoxhYyFVq8pji?usp=drive_link)

> 💡 *Ensure you have access to Google Colab with a Google account to run this notebook interactively.*

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/iris-flower-classification.git

