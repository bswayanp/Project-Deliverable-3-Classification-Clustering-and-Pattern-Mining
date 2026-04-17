# Project Deliverable 3: Classification, Clustering, and Pattern Mining

## Overview
This project aims to build classification and clustering models, apply hyperparameter tuning, and perform association rule mining to identify patterns in the data.

## Classification Models
- **Decision Tree** and **Naïve Bayes** were developed and evaluated using confusion matrix, ROC curve, and F1 score.
- Hyperparameter tuning was performed on the **Decision Tree** model using `GridSearchCV`.

## Clustering Model
- **K-Means** clustering was applied to group the data into clusters.
- The clustering results were visualized using a scatter plot.

## Association Rule Mining
- **Apriori** algorithm was used to identify patterns in the transactional data.
- Insights on how these patterns can be used for cross-selling in retail.

## Challenges
- One challenge was dealing with missing data in the dataset. This was addressed by performing imputation techniques using `SimpleImputer` from `sklearn`.
- Another challenge was ensuring that the clustering results were interpretable. PCA was used to reduce the dimensions before visualizing the clusters.
