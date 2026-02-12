**Titanic Survival Prediction: Decision Tree Classifier**
Objective: 
Build a predictive model to determine passenger survival based on demographic and socio-economic features.

Technical Key Points:

Feature Engineering: 
Preprocessed categorical variables (Sex, Embarked) and handled missing age values to prepare the data for the Scikit-Learn classifier.

Hyperparameter Tuning: 
Conducted a sensitivity analysis on max_depth to balance model complexity and generalization, identifying Depth 6 as optimal.

Evaluation: Utilized a split of Train, Development, and Test sets to ensure the final accuracy of ~77% was robust and not a result of overfitting.
