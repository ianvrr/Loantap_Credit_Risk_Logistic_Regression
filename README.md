# 🏦 Loan Default Prediction

## 📖 Project Overview

This project aims to predict loan defaults for a financial institution, balancing the goal of approving loans profitably while minimizing non-performing assets (NPAs). By analyzing key factors, the model assists in identifying defaulters, helping lenders make informed loan approval decisions.

## 📊 Dataset

- **Dataset**: Loan default dataset (internal)
  
### Column Description:
- **Customer ID**: Unique identifier for each loan applicant
- **Loan Amount**: Amount of the requested loan
- **Interest Rate**: Loan interest rate assigned
- **Credit Score**: Applicant's credit score
- **Income**: Applicant's annual income
- **Employment Length**: Number of years at current job
- **Purpose**: Reason for the loan
- **Default Status**: Binary indicator for default (1 = default, 0 = non-default)

## 🧠 Key Concepts

- **Exploratory Data Analysis (EDA)**: Examined patterns and key variables to gain insights into factors influencing loan defaults.
- **Feature Engineering**: Removed multicollinear features and balanced classes using SMOTE.
- **Logistic Regression**: Model built with class weights to prioritize identifying actual defaulters.

## 🔍 Analysis and Findings

1. **EDA**:
   - Analyzed variable distributions and correlations.
   - Visualized key patterns in loan purpose, credit score, and default rates.

2. **Model Building**:
   - Implemented **Logistic Regression** with SMOTE to address class imbalance.
   - Adjusted the decision threshold to **0.65** based on the Precision-Recall curve for optimal precision-recall trade-off.
   - Evaluated performance with accuracy, precision, recall, and F1-score.

3. **Actionable Insights**:
   - **Threshold Adjustment**: Increased threshold to prioritize reliable defaulter detection.
   - **Cost-sensitive Strategy**: Increased penalty for false negatives to reduce high-risk loan approvals.

## 📝 Conclusion

This model enables better loan approval decisions by reducing NPAs and balancing profitable opportunities with risk management. The results show that careful threshold tuning and class weighting improve defaulter detection without excessive false positives.

## 💡 Future Work

- Experiment with **Advanced Models** (e.g., Random Forest, Gradient Boosting) for improved accuracy.
- Consider adding **additional borrower data** for more robust predictions.
- Deploy the model in a real-world application to support loan approval decisions dynamically.

## 📧 Contact

For more information or collaboration, feel free to reach out:

- **Email**: anvrr@yahoo.com
- **LinkedIn**: [Anwar](https://www.linkedin.com/in/ianvrr/)
