## Overview of the Analysis

The purpose of the analysis was to develop machine learning models to predict loan status based on financial information. 
The dataset contained information on loan applicants, including features such as credit score, income, loan amount, 
and loan term, with the target variable being loan status (either healthy loan or high-risk loan).

### Data Overview:
- The target variable, loan status, had two classes:
  - `0`: Healthy loan
  - `1`: High-risk loan
- Basic information about the target variable:
  - Value counts:
    - Healthy loan (`0`): 18,765 support
    - High-risk loan (`1`): 619 support

### Stages of the Machine Learning Process:
1. **Data Preprocessing**: This stage involved handles encoding categorical variables and scaling numerical features.
2. **Model Selection**: Logistic Regression was the model selected.
3. **Model Training and Evaluation**: Models were trained using the training dataset and evaluated using accuracy, precision, and recall metrics.

### Methods Used:
- Logistic Regression

  
## Results

* **Logistic Regression**:
  - Accuracy: 0.99
  - Precision (Healthy loan): 1.00
  - Precision (High-risk loan): 0.85
  - Recall (Healthy loan): 0.99
  - Recall (High-risk loan): 0.91

## Summary

The logistic regression model predicted healthy loans, with high precision and recall scores.
Given its strong overall performance and balance between precision and recall for both classes, the logistic regression model is recommended for predicting loan status in this analysis.
