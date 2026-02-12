**US Arrests: Dimensionality Reduction & Clustering**

Objective: 
  Uncover latent structures in US crime data to group states by risk and urbanization levels.

**Technical Key Points**

Standardization:
  Utilized StandardScaler to handle the large variance between 'Assault' numbers and 'Murder' rates.

PCA: 
  Reduced 4 variables into 2 principal components while retaining nearly 90% of original information.

Clustering: 
  Identified 3 distinct state profiles: High-Crime/Low-Urban, High-Crime/High-Urban, and Low-Crime/Low-Urban.
