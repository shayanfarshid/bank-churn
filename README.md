# bank-churn

![Project Title Image](https://img.shields.io/badge/Customer%20Churn%20Prediction%20Model-blue?style=for-the-badge)


## Introduction
In this project, we explore and predict customer churn for a banking institution using machine learning models. Our goal is to understand customer demographics, identify predictive features, and apply predictive models to develop actionable insights.

## Business Questions
1. **Question 1:** What are the detailed demographics of the people likely to churn?
2. **Question 2:** How well can different predictive models forecast customer churn?


## Exploratory Data Analysis
1. **Correlation Matrix**:
   - Identifies no multicollinearity issue among features.

2. **Age Distribution Analysis**:
   - The graph suggests mid-aged individuals are more likely to churn.

3. **Nationwide Distribution of Churn**:
   - Churn rates are highest in Germany, followed by France.

4. **Churn Population**:
   - 20.4% of customers in the dataset are churning compared to 79.6% who are not.

## Predictive Analytics & Models
1. **Logistic Regression**:
   - **Accuracy**: 81.2%  
   - **ROC AUC**: 0.5975  
   - **Confusion Matrix**:  
   - **Precision**: 0.78 (weighted F1 score)

2. **Support Vector Machine (SVM)**:
   - **Accuracy**: 86.3%  
   - **ROC AUC**: 0.7013  
   - **Confusion Matrix**:  
   - **Precision**: 0.85 (weighted F1 score)

3. **Random Forest**:
   - **Accuracy**: 87.05%  
   - **ROC AUC**: 0.7401  
   - **Confusion Matrix**:  
   - **Precision**: 0.86 (weighted F1 score)

## Business Actions
1. **Targeted Retention Strategies**:
   - Implement strategies tailored for the younger demographic, who are more prone to churn.
   
2. **Predictive Model Integration**:
   - Deploy the Random Forest model into the customer service workflow to flag high-risk churn customers for intervention.

## Business Outcomes
1. **Increased Customer Loyalty**:
   - Reduction in churn, particularly among younger customers.
   
2. **Resource Optimization**:
   - Efficient allocation of customer retention resources.

## Conclusion
- Deploy retention strategies focused on younger demographics.
- Enhance customer experience in selective high-churn regions.
- Utilize Random Forest for proactive customer engagement.

## Key Takeaways
- **Model Selection**: Random Forest leads with an accuracy of 87.05% and an F1 score of 0.86, outperforming Logistic Regression and SVM.
