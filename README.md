# Iris Classification Using Machine Learning

## Author

**Name:** Matteddula Mayuri

**College:** Sri Venkateswara College of Engineering

**Internship:** Machine Learning Internship

**Task Number:** Task 1 – Iris Classification

---

## Project Description

The Iris Classification project is a machine learning classification problem that predicts the species of an iris flower based on its physical measurements. The model uses sepal length, sepal width, petal length, and petal width to classify flowers into different species.

---

## Objective

The main objective of this project is to build a machine learning model that can accurately classify iris flowers into their respective species and demonstrate the complete machine learning workflow.

---

## Dataset Information

The Iris dataset contains 150 flower samples with the following features:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Classes:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

---

## Tools and Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Exploratory Data Analysis (EDA)

The following EDA operations were performed:

* Dataset preview using `head()`
* Dataset information using `info()`
* Statistical summary using `describe()`
* Missing value analysis
* Data visualization

---

## Visualizations

The following plots were generated:

* Scatter Plot
* Histogram
* Pair Plot

These visualizations helped in understanding the relationships between the features and species.

---

## Machine Learning Models Used

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier

---

## Model Evaluation

The models were evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

Among all the models, K-Nearest Neighbors (KNN) achieved the best performance.

---

## Model Saving

The trained KNN model was saved using Joblib as:

`iris_model.pkl`

---

## Example Prediction

Input:

* Sepal Length = 5.1
* Sepal Width = 3.5
* Petal Length = 1.4
* Petal Width = 0.2

Predicted Output:

`Iris-setosa`

---

## Conclusion

This project successfully demonstrates the complete machine learning process, including data analysis, visualization, model training, evaluation, and model deployment. The developed model can accurately predict iris flower species based on their measurements.
