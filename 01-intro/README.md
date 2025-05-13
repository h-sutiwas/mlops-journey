# NYC Taxi Duration Prediction Project
Project Summary:
---
This project builds a predictive machine learning model to estimate taxi journey times in New York City using the NYC Yellow Taxi Trip dataset in 2023 (From January to February). The model estimates anticipated travel duration based on origin and destination points.

Technical Execution
---
### Data Handling
- Information Source: NYC Yellow Cab Journey Records from January and February 2023.
  - Derived journey durations (in minutes) from origin and destination timestamps.
  - Eliminated anomalies by selecting trips lasting between 1-60 minutes.
  - Transformed location identifiers (pickup and dropoff IDs) to categorical variables using one-hot encoding.

### ML Model Development
  **Feature Engineering**
  - Processed origin and destination location identifiers using `DictVectorizer`.
  - Generated sparse matrix format for computational efficiency.

  **Model Development**
  - Utilized Linear Regression as an initial benchmark.
  - Employed scikit-learn's framework for reproducibility.

  **Performance Metrics**
  - Assessed algorithm accuracy using Root Mean Square Error (RMSE).
  - Confirmed results across both training (January) and validating (February) datasets.

### Princippal Insights
- Showcased successful data cleaning strategies for sequential information.
- Applied feature engineering for categorical variables.
- Utilized time-based validation splitting.
- Acquired hands-on knowledge with scikit-learn's ML workflow.

### Tools Utilized
- **Python:**
  - `pandas` for data manipulation
  - `scikit-learn` for predictive modeling
  - Jupyter Notebook for code development

This project is part of the MLOps Zoomcamp 2025 coursework, focusing on practical machine learning implementation and operations. For the first assignment, I have 2 different versions, one for submission while the other is for automation implementation.
[Link to the repository.](https://github.com/h-sutiwas/mlops-journey)
