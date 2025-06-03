#/Task-6-K-Nearest-Neighbors-KNN-Classification

# KNN Classifier - Iris Dataset
This repository implements a K-Nearest Neighbors (KNN) classifier on the Iris dataset using `scikit-learn`.

##  Steps Followed

- Loaded and normalized the dataset using `StandardScaler`.
- Split into train and test sets.
- Trained KNN models with different values of K (1–20).
- Selected the best K based on accuracy.
- Evaluated the final model using a confusion matrix and accuracy.
- Visualized results.

## Key Concepts
- **KNN** is an instance-based, lazy learning algorithm.
- Normalization is essential due to distance-based calculations.
- Euclidean distance is used as the default metric.

##  Output

- Best K value (selected based on test accuracy).
- Accuracy vs K plot.
- Confusion matrix visualization.

##  Libraries Used

- numpy
- pandas
- matplotlib
- scikit-learn

