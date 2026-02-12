# Taxonomy Clustering: Hierarchical Agglomerative Analysis
Focus:Unsupervised Learning, Dendrogram Analysis, and Cluster Validation

Project Overview
This project demonstrates the application of Hierarchical Agglomerative Clustering to classify iris flower species based on morphological features. Unlike K-Means, which requires a pre-defined 'k', this method allows for a visual interpretation of the data's hierarchical structure to find the most natural groupings.

Technical Workflow
Feature Scaling: Implemented StandardScalerto ensure petal and sepal measurements were on a comparable scale, preventing larger values from biasing the distance metrics.

Dendrogram Visualization: Generated a dendrogram using the **Complete Linkage** method to identify the optimal number of clusters by observing the maximum vertical distance that does not cross any horizontal line.

Model Implementation: Utilized AgglomerativeClustering from Scikit-Learn to segment the data into 3 distinct clusters.

Validation: Calculated a Silhouette Score of (0.534), confirming that the clusters are well-defined and the separation is statistically significant.

Strategic Insights
Algorithm Selection: Hierarchical clustering was chosen specifically for its ability to reveal the sub-structures within the data, which is essential in taxonomic and biological classification.
Cluster Reliability: A Silhouette Score > 0.5 indicates a "Good" clustering fit, providing confidence that the physical features are strong predictors of species type even in an unsupervised environment.

Repository Contents
Iris_Hierarchical_Clustering.ipynb: Full analysis including dendrogram generation and model evaluation.
Iris.csv: The standardized dataset used for the analysis.
