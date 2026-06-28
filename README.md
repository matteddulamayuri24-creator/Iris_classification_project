# Iris Classification Using Machine Learning

## Author

**Name:** Matteddula Mayuri

**College:** Sri Venkateswara College of Engineering

**Internship:** Machine Learning Internship

**Task Number:** Task 1 – Iris Classification

---

# Iris Classification Using Machine Learning

## Author

**Name:** Matteddula Mayuri
**College:** Sri Venkateswara College of Engineering
**Department:** Artificial Intelligence and Machine Learning
**Internship:** Machine Learning Internship
**Task Number:** Task 1 – Iris Classification

---

# Project Description

The Iris Classification project is a supervised machine learning classification problem that predicts the species of an iris flower based on its physical characteristics. The model uses flower measurements such as sepal length, sepal width, petal length, and petal width to classify flowers into their respective species.

This project demonstrates the complete machine learning pipeline, including data preprocessing, exploratory data analysis, model building, evaluation, and model deployment.

---

# Objective

The main objective of this project is to develop a machine learning model capable of accurately classifying iris flowers into different species. The project also aims to provide practical experience in data analysis, visualization, classification algorithms, and model evaluation.

---

# Dataset Information

The Iris dataset is one of the most popular datasets in machine learning. It contains **150 flower samples** belonging to three different species.

### Features:

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

### Target Classes:

* Iris-setosa
* Iris-versicolor
* Iris-virginica

Each class contains 50 flower samples.

---

# Data Preprocessing

The following preprocessing steps were performed:

* Dataset loading using Pandas.
* Checking data types and dataset information.
* Missing value analysis.
* Data cleaning and preparation.
* Splitting the dataset into training and testing sets.

The dataset contained no missing values, making preprocessing straightforward.

---

# Exploratory Data Analysis (EDA)

Exploratory Data Analysis was performed to understand the dataset and identify relationships between features.

The following operations were carried out:

* Dataset preview using `head()`
* Dataset information using `info()`
* Statistical summary using `describe()`
* Class distribution analysis
* Correlation analysis

---

# Data Visualization

Several visualizations were created to understand the characteristics of the iris dataset.

### Scatter Plot

Shows the relationship between petal and sepal measurements.

### Histogram

Displays the distribution of each feature.

### Pair Plot

Helps visualize relationships among all features and different species.

### Box Plot

Identifies the spread and distribution of feature values.

These visualizations helped distinguish different iris species.

---

# Machine Learning Models Used

The following classification algorithms were implemented:

### Logistic Regression

A linear classification algorithm used as a baseline model.

### K-Nearest Neighbors (KNN)

Classifies samples based on the nearest neighboring data points.

### Decision Tree Classifier

Creates decision rules based on feature values.

Among these models, **K-Nearest Neighbors (KNN)** achieved the highest accuracy.

---

# Model Training

The dataset was divided into:

* Training Data: 80%
* Testing Data: 20%

The models were trained using the training dataset and evaluated using the testing dataset.

---

# Model Evaluation

The following evaluation metrics were used:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics were used to compare the performance of different models.

---

# Model Saving

The best-performing KNN model was saved using Joblib.

```text
iris_model.pkl
```

The saved model can be reused for future predictions without retraining.

---

# Example Prediction

### Input:

* Sepal Length = 5.1 cm
* Sepal Width = 3.5 cm
* Petal Length = 1.4 cm
* Petal Width = 0.2 cm

### Predicted Output:

```text
Iris-setosa
```

---

# Learning Outcomes

Through this project, the following concepts were learned:

* Data preprocessing
* Exploratory Data Analysis
* Data visualization
* Classification algorithms
* Model evaluation techniques
* Model comparison
* Model saving and deployment

---

# Future Enhancements

* Hyperparameter tuning for improved accuracy.
* Web application deployment using Flask or Streamlit.
* Integration with real-time flower measurement systems.
* Comparison with advanced machine learning algorithms.

---

# Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

# Project Structure

```text
Iris_Classification_Project/
│
├── Iris_Classification.ipynb
├── iris.csv
├── iris_model.pkl
├── Executive_Summary.pdf
├── README.md
└── screenshots/
```

---

# Conclusion

This project successfully demonstrates the complete machine learning workflow, including data preprocessing, visualization, model training, evaluation, and model saving. The developed model accurately predicts iris flower species based on their measurements and serves as an excellent beginner-level machine learning project.

---

