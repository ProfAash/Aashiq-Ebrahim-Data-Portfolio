# High-Dimensional Data Analysis: 3D PCA Projections
**Focus:** Principal Component Analysis (PCA), Feature Redundancy, and 3D Visualisation

## Project Overview
As datasets grow in complexity, "The Curse of Dimensionality" becomes a significant hurdle. This project demonstrates how to use Principal Component Analysis (PCA) to reduce 4D morphological data (Iris dataset) into 3 dimensions while retaining the essential variance required for species classification.

## Technical Workflow
* **Preprocessing:** Standardised features to ensure that variables with different scales (e.g., petal length vs. sepal width) contribute equally to the variance analysis.
* **Dimensionality Reduction:** Utilised `Scikit-Learn` to decompose the data into three principal components.
* **3D Visualisation:** Developed a 3D scatter plot using `Matplotlib` to project the transformed data, revealing clear spatial separation between the *Setosa*, *Versicolor*, and *Virginica* species.

## Strategic Insights
* **Information Retention:** The 3D projection confirms that PCA preserved the discriminative structure of the original 4D data. Setosa remains perfectly isolated, while the overlap between the other two species is minimised.
* **Efficiency:** This technique proves that analysts can simplify models and reduce computational load without losing the predictive power of the dataset.



## Repository Contents
* `Iris_3D_PCA_Projection.ipynb`: Python notebook featuring the PCA pipeline and 3D Matplotlib plots.
* `Iris.csv`: The source dataset.
