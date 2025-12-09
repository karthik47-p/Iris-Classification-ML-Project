# Iris Classification ML Project

## Overview
This project implements a **machine learning model** to classify the famous **Iris dataset** into three species: *Iris-setosa*, *Iris-versicolor*, and *Iris-virginica*.  
The model uses the **K-Nearest Neighbors (KNN)** algorithm and provides accuracy metrics, confusion matrix, and predictions.

## Dataset
- **Source:** CSV file included in the repository (`Data/Iris.csv`)  
- **Columns:**
  - `Id`: Unique identifier for each sample
  - `SepalLengthCm`: Sepal length in cm
  - `SepalWidthCm`: Sepal width in cm
  - `PetalLengthCm`: Petal length in cm
  - `PetalWidthCm`: Petal width in cm
  - `Species`: Target variable (Iris species)

## Features
- Python 3.x
- Pandas
- Scikit-learn
- Seaborn / Matplotlib for visualization
- Export predictions to CSV for portfolio/LinkedIn showcase

## Steps
1. Load the dataset using Pandas
2. Explore data (columns, missing values, basic statistics)
3. Split dataset into training and testing sets
4. Train **KNN classifier**
5. Predict species for test data
6. Evaluate using **confusion matrix** and **classification report**
7. Save predictions to CSV

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/karthik47-p/Iris-Classification-ML-Project.git
