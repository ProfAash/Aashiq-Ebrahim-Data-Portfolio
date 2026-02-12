# Iris Species Classification: Logistic Regression
**Focus:** Supervised Learning, Multiclass Classification, and Model Evaluation

## Project Overview
This project applies Logistic Regression to the classic Iris dataset to predict flower species based on four physical measurements. The objective was to build a robust classifier and evaluate its performance using statistical metrics to ensure 100% reliability in categorical predictions.

## Technical Workflow
* **Data Preparation:** Handled the multi-label nature of the target variable using a multinomial configuration within the `LogisticRegression` framework.
* **Model Training:** Performed an 80/20 train-test split to ensure the model could generalize to unseen data.
* **Performance Metrics:** Generated a **Confusion Matrix** to visualize the accuracy of predictions across all three classes.

## Strategic Insights
* **Perfect Accuracy:** The model achieved 100% accuracy, precision, and recall. The Confusion Matrix confirmed that all 30 test samples were correctly classified into their respective species without a single error.
* **Operational Reliability:** In a business context, this level of model performance demonstrates the feasibility of automating classification tasks when high-quality, separable features are available.



## Repository Contents
* `Iris_Logistic_Regression.ipynb`: Full implementation, from training to the final Confusion Matrix.
* `Iris.csv`: The standardized dataset.
