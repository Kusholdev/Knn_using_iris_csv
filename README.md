# Iris Flower Classification using K-Nearest Neighbors (KNN)

## Project Overview

This project demonstrates a machine learning classification task using the famous Iris Dataset. The objective is to classify iris flowers into three species based on their sepal and petal measurements using the K-Nearest Neighbors (KNN) algorithm.

## Dataset

**Dataset Name:** Iris Dataset

**Source:** Kaggle

Dataset Link: https://www.kaggle.com/datasets/uciml/iris

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Classes

* Iris-setosa
* Iris-versicolor
* Iris-virginica

## Project Tasks

The following steps were performed:

1. Loaded the dataset using Pandas.
2. Separated features (X) and target (y).
3. Split the dataset into training and testing sets.
4. Trained a K-Nearest Neighbors (KNN) classifier with **K = 3**.
5. Predicted the labels of the test dataset.
6. Evaluated the model using Accuracy Score.
7. Generated a Confusion Matrix.
8. Generated a Classification Report including Precision, Recall, and F1-Score.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib (optional)
* Seaborn (optional)

## Machine Learning Workflow

### Data Loading

The dataset was loaded using the Pandas library and inspected for structure and data quality.

### Data Preparation

* Features and target variables were separated.
* The dataset was split into training and testing sets using an 80-20 ratio.

### Model Training

A KNN classifier was created with:

```python
KNeighborsClassifier(n_neighbors=3)
```

### Model Evaluation

The trained model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report

## Evaluation Metrics

### Accuracy Score

Measures the percentage of correctly classified instances.

### Confusion Matrix

Displays the number of correct and incorrect predictions for each class.

### Classification Report

Provides:

* Precision
* Recall
* F1-Score
* Support

## How to Run

1. Clone the repository:

```bash
git clone <your-repository-link>
```

2. Install required packages:

```bash
pip install pandas numpy scikit-learn
```

3. Run the Python script:

```bash
python iris_knn.py
```

## Expected Output

* Model Accuracy
* Confusion Matrix
* Classification Report

## Learning Outcomes

Through this project, I learned:

* Data preprocessing using Pandas
* Train-test splitting
* K-Nearest Neighbors (KNN) algorithm
* Model evaluation techniques
* Classification performance analysis using Confusion Matrix and Classification Report

## Author

Kushol

## License

This project is for educational and practice purposes.
