# Data Science Project: StackExchange Questions Classification

## Overview
This project involves exploring, classifying, clustering, and validating a dataset sourced from StackExchange, particularly the Stats stack exchange. The dataset contains questions, and the objective is to predict the popular topics to which these questions belong.

## Data Exploration 

### Outputs:
- **Data Summary**: The dataset was extensively profiled to understand its structure, missing values, and general statistics.
- **Data Balance Analysis**: Visualized the label distribution to assess the balance of data across various labels.
- **Pairwise Relationships**: Analyzed the pairwise relationships between all numerical columns in the dataset.

## Classification

### Outputs:
- **Model Performance**: Evaluated the performance of classification models using metrics like accuracy, precision, recall, etc.
- **Feature Importance**: Identified the significant features that influence model predictions.
- **Confusion Matrix**: Visualized the true positives, false positives, true negatives, and false negatives made by the model.

## Clustering

### Outputs:
- **Cluster Visualization**: Graphically represented the clustering of the dataset, showing data points distribution across various clusters.
- **Cluster Metrics**: Calculated metrics to understand the quality of clusters formed.
- **Data Labeling**: Labeled data points based on clustering results.

## Test Classification

### Outputs:
- **Random Forest (Body Column)**: Achieved an average F1 score of approximately `0.7291`.
- **Random Forest (Title Column)**: Achieved an average F1 score of approximately `0.6932`.
- **Linear SVC (Body Column)**: Achieved an average F1 score of approximately `0.7396`.

