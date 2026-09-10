# BANKNOTE AUTHENTICATION — Machine Learning Classification

## About the Project

This project focuses on classifying banknotes as **authentic or forged** using Machine Learning algorithms.

The main aim is to apply different Machine Learning algorithms to the same dataset and compare their performance using different evaluation metrics.

The following algorithms were used:

* Naive Bayes
* K-Nearest Neighbors (KNN)
* K-Means

## Dataset

The dataset used in this project is **BANKNOTE AUTHENTICATION**.

The dataset contains numerical features extracted from banknote images. These features are used to identify whether a banknote is authentic or forged.

The main features include:

* Variance
* Skewness
* Curtosis
* Entropy

The target variable used for classification is:

* `class`

The class represents the type of banknote.

## Algorithms Used

The following algorithms were applied:

* **Naive Bayes**
* **K-Nearest Neighbors (KNN)**
* **K-Means**

Before applying the algorithms, the dataset was checked for missing values. The data was divided into training and testing sets, and feature scaling was applied using StandardScaler where required.

For KNN, different values of K were tested from **1 to 20**, and the best K value was selected based on accuracy.

K-Means was applied with **2 clusters** because the dataset contains two classes.

## Performance Comparison

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

For K-Means, additional clustering evaluation measures were used:

* Silhouette Score
* Adjusted Rand Index (ARI)
* Normalized Mutual Information (NMI)

The final performance comparison was used to identify the best-performing algorithm.

## K-Means Results

K-Means clustering was performed using two clusters.

The obtained results were:

* **WCSS / Inertia:** 3453.2919
* **Silhouette Score:** 0.3291

The silhouette score indicates that the two clusters have some separation, although the clusters are not strongly separated.

## Visualizations

The project includes different visualizations to understand and compare the model performance.

The visualizations include:

* KNN Accuracy for different K values
* Algorithm Performance Comparison
* Confusion Matrices for the classification models

These graphs help in understanding how the algorithms perform on the BANKNOTE AUTHENTICATION dataset.

## Tools Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* VS Code


## How to Run

1. Install Python on your computer.
2. Install the required libraries:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Place the dataset and Python file in the same project folder.
4. Open the project in VS Code.
5. Run the Python program.

## Objective

The main objectives of this project are:

* To understand Machine Learning classification algorithms.
* To classify banknotes using different algorithms.
* To compare Naive Bayes, KNN, and K-Means.
* To evaluate the algorithms using different performance metrics.
* To identify the best-performing algorithm for the dataset.

## Conclusion

This project demonstrates the application of Machine Learning algorithms on the **BANKNOTE AUTHENTICATION** dataset.

Naive Bayes and KNN were used as supervised learning algorithms, while K-Means was used as an unsupervised clustering algorithm. Their performance was evaluated and compared using different metrics.

The project helps in understanding the differences between supervised classification and unsupervised clustering and shows how different Machine Learning algorithms can be applied to the same dataset.

