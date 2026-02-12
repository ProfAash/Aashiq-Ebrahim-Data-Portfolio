**Project Overview**
  This project applies unsupervised learning techniques to categorize 167 countries based on socio-economic and health indicators (GDPP, child mortality, inflation, etc.). The goal is to identify distinct clusters of development to help organizations prioritize aid or investment.

**Technical Workflow**

Data Preprocessing: 
  Standardized features using MinMaxScaler to ensure that variables with different scales (e.g., GDPP vs. Inflation) contributed equally to the model.

Optimization: 
  Utilized the Elbow Method and Silhouette Scoring to determine the optimal number of clusters (k=3).

Cluster Assignment: 
  Implemented the K-Means algorithm to segment countries into three tiers: Least Developed, Developing, and Developed.

Visualization: 
  Created scatter plots (e.g., GDPP vs. Child Mortality) to validate the separation and characteristics of each cluster.

**Strategic Insights**

The Development Gap: 
  The "Least Developed" cluster was characterized by significantly higher child mortality (92.9 mean) and lower GDPP ($1922 mean) compared to the "Developed" tier.

Investment Risk: 
  By analyzing inflation trends across clusters, this model identifies regions with high economic volatility, which is critical for risk-assessment roles.

Feature Importance: 
  The analysis confirms that GDPP and Child Mortality remain the strongest predictors of a nation's overall development category.
