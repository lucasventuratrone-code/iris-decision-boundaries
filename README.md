# Iris Classification – Decision Boundary Analysis

This project explores classification models applied to the Iris dataset,
with an emphasis on visualizing and comparing decision boundaries.

## Models Used
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Decision Tree Classifier
- Suport Vector Classifier
- Support Vector Classifier(SVC)

## Methodology
- Train models using all features
- Compare feature subsets (sepal vs petal)
- Evaluate accuracy
- Visualize decision boundaries

## Key Insights
- Petal features provide strong class separation.
- Multiple models achieve similar accuracy on this dataset.
- Decision boundary visualization reveals structural differences
  between algorithms beyond performance metrics.

## Example Visualization
![Decision Boundary](figures/decision_boundary_rf.png)

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
