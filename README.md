# Data-Modeling-and-Analysis-using-Python-and-Scikit-learn-on-StackExchange-Data
# Data Modeling and Analysis using Python and Scikit-learn on StackExchange Data

## Overview
This project involves data exploration, classification, clustering, and classification on unseen data using Python's Scikit-learn library. The dataset originates from StackExchange, particularly the Stats stack exchange (Cross Validated). The main objective is to model the data in the training set to predict topics for the questions in the test set.

## Notebooks

### 1. Data Exploration
- **Objective**: Understand the structure and characteristics of the data.
- **Key Tasks**:
  - Summarize the dataset.
  - Check data balance for labels.
  - Plot pairwise relationships between numerical columns.
  - Plot central tendency per label.

### 2. Classification
- **Objective**: Develop and evaluate classification models.
- **Key Tasks**:
  - Split the data into training and validation sets.
  - Fit and evaluate a decision tree classifier.
  - Fit and evaluate a KNN classifier.
  - Extract features from the 'Title' column and train classifiers.
  - Optimize classifier parameters for better accuracy.

### 3. Clustering
- **Objective**: Perform data clustering and interpret the results.
- **Key Tasks**:
  - Convert the 'Title' column into a tf-idf vector.
  - Cluster data using KMeans and DBSCAN algorithms.
  - Analyze the K-distance graph for DBSCAN.
  - Visualize WCSS and V-measure for various k values.

### 4. Classification on Unseen Data
- **Objective**: Classify data in the test set using the best model from the training phase.
- **Key Tasks**:
  - Generate predictions for the test set.
  - Ensure reproducibility of the solution.

## Results

- Refer to individual notebooks for detailed outputs and interpretations.
- Prediction files are generated as per the specified format.

## Usage

- Set up an Anaconda environment with Python 3.8.x.
- Install the required packages as provided in the `requirements.txt` file.
- Ensure the RANDOM SEED is set to achieve reproducible results.
- Execute notebooks in the order: Data Exploration, Classification, Clustering, and Classification on Unseen Data.

---

**Note**: Do not modify the structure of the notebooks. Ensure the notebooks run without errors for reproducibility.
