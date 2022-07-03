# Dimentionality Reduction Using Principal Component Analysis
Principal Component Analysis is a technique used in Machine Learning Algorithms to reduce the dimensionality of the input. A common problem faced by programmers while making a machine learning algorithm is that one or more dimensions in the dataset capture the same concept, making them redundant. For example, if height and weight are two dimensions in an algorithm, since the weight of a person increases as the height increases, they both capture the same concept. This makes the algorithm inefficient. Principal Component Analysis is a process that converts the observations of correlated features into a set of linearly uncorrelated features. For example, a 3D feature can be reduced to a 2D or 1D feature.

## Table of Contents
* [Advantages](## Advantages)
* [Methodology](## Methodology)

## Advantages
* Removes correlated features: As discussed above, the main advantage of PCA is that it removes correlated features and converts them into a set of linearly uncorrelated features.
* Improves Algorithm Performance: By removing the correlated features, the programmer has less variables to work with, thus increasing the efficiency and the performance of the algorithm.
* Reduces Overfitting: Overfitting mainly occurs when there are too many variables in the dataset. So, PCA helps in overcoming the overfitting issue by reducing the number of features.
* Improves Visualization: It is difficult to visualize and understand data in higher dimensions (3D). PCA converts this high dimension data set into a low dimension data set (2D) thus enabling easier visualization.

## Methodology
* Step 1: Read the data
* Step 2: Subtract the mean
* Step 3: Calculate covariance matrix
* Step 4: Compute eigen values and eigen vectors
* Step 5: Choosing components and forming a feature vector
* Step 6: Deriving the new dataset
