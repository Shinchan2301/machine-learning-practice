Machine Learning Algorithms and Projects

A hands-on collection of machine learning implementations created with Python and Jupyter Notebook. This repository brings together core supervised and unsupervised learning algorithms, ensemble techniques, dimensionality reduction, anomaly detection, and small end-to-end projects.

The goal is to strengthen practical understanding by exploring each algorithm through data preparation, model training, evaluation, visualization, and interpretation.

Repository Contents

Area

Implementations

Regression

Simple Linear Regression, Multiple Linear Regression, Polynomial Regression, Support Vector Regression, Random Forest Regression

Boosting

AdaBoost Regression, Gradient Boosting Regression, XGBoost Regression

Classification

Logistic Regression, Multiclass Logistic Regression, Imbalanced Classification, K-Nearest Neighbours, Decision Tree, Random Forest, Support Vector Classifier, Naive Bayes

Clustering

K-Means, Hierarchical Clustering, DBSCAN

Dimensionality Reduction

Principal Component Analysis (PCA)

Anomaly Detection

Isolation Forest

Applied Projects

Algerian Forest Fire Prediction, Diabetes Prediction, California Housing

Repository Structure

.
├── 01_simple_linear_regression/
├── 02_multiple_linear_regression/
├── 03_polynomial_regression/
├── 04_algerian_forest_fire_project/
├── Adaboost+Regression+Implementation.ipynb
├── DBSCAN+Implementation.ipynb
├── Decision_tree_classifier_implementation.ipynb
├── Gradientboost+Regression+Implementation.ipynb
├── Hierarchical+Clustering+Implementation.ipynb
├── Isolation+Anomaly+Detection.ipynb
├── K+Means+Clustering+Algorithms+implementation.ipynb
├── K_nearest_neighbour_classifier.ipynb
├── Logistic_Regression_multiclass.ipynb
├── Logistic_regression_Implementation.ipynb
├── Naive_bayes_Algorithm_Implementation.ipynb
├── Principal+Component+Analysis+(PCA)+Implementation.ipynb
├── Random_forest_classification.ipynb
├── Support_vector_regression.ipynb
└── README.md

Additional notebooks cover imbalanced datasets, Support Vector Classification, Random Forest Regression, XGBoost Regression, and dataset exploration.

Typical Notebook Workflow

Most notebooks follow this practical workflow:

Import and inspect the dataset.

Perform data cleaning and exploratory analysis.

Prepare features and target variables.

Split the data into training and testing sets.

Apply preprocessing such as encoding or feature scaling when required.

Train the machine learning model.

Evaluate performance using suitable metrics.

Visualize and interpret the results.

Tools and Technologies

Python

Jupyter Notebook / Google Colab

NumPy

pandas

Matplotlib

Seaborn

scikit-learn

XGBoost

Getting Started

Option 1: Google Colab

Open any .ipynb file on GitHub and select Open in Colab. This is the quickest way to run a notebook without configuring a local environment.

Option 2: Run Locally

Clone the repository and open it in Jupyter:

git clone <repository-url>
cd <repository-folder>

python -m venv .venv
source .venv/bin/activate

pip install numpy pandas matplotlib seaborn scikit-learn xgboost jupyter
jupyter notebook

On Windows, activate the environment with:

.venv\Scripts\activate

Some notebooks may require a dataset file or an additional package. Check the first few cells of the selected notebook before running all cells.

Evaluation Methods

Depending on the problem, the notebooks use or demonstrate metrics such as:

Mean Absolute Error, Mean Squared Error, and R² score for regression

Accuracy, precision, recall, F1-score, and confusion matrix for classification

Silhouette score and cluster visualization for clustering

Learning Objectives

This repository is designed to help with:

Understanding how classical machine learning algorithms work

Selecting suitable preprocessing and evaluation techniques

Comparing models across regression and classification tasks

Building reusable experimentation habits in Jupyter Notebook

Developing a practical machine learning portfolio

Planned Improvements

Standardize notebook names and folder organization

Add a shared requirements.txt

Document dataset sources in every notebook

Add model comparison and hyperparameter-tuning notebooks

Include consistent conclusions and key findings for each experiment

Expand into deep learning and healthcare AI projects

Author

Created and maintained by Shinchan2301.

If you find this repository useful, consider giving it a star.
