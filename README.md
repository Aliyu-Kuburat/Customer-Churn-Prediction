# Customer-Churn-Prediction
Build a system that predicts if a customer will stop using a service (churn). You’ll clean and analyze data, create useful features, train models (Logistic Regression, Random Forest, XGBoost), and deploy your model with Streamlit so users can test churn predictions.

Telco Customer Churn Analysis Report

1.	Introduction
This report presents a full analysis of customer churn for a telecommunications provider. The goal is to identify why customers leave and to build a predictive model that flags at-risk customers early. Insights from this report enable more effective retention strategies, improved customer experience, and stronger revenue stability.

2.	Data Overview
The dataset contains demographic information, contract details, billing data, and service usage. The target variable is Churn, indicating whether a customer has discontinued service. Before modeling, the data was cleaned, encoded, and structured to ensure accuracy and consistency.

3.	Exploratory Insights
Several behavioral and service-related patterns were observed:
• Customers on month-to-month contracts leave more frequently.
• New customers with lower tenure show a higher churn rate.
• Higher monthly charges correlate with dissatisfaction and churn.
• Customers lacking online security, tech support, or device protection are more likely to leave.
• Fiber optic customers exhibited higher churn than DSL customers.
   These findings informed both modeling and strategy recommendations.

5.	Predictive Modeling
Three models were trained: Random Forest, Logistic Regression, and XGBoost. Random Forest achieved the strongest balance of accuracy, recall, and robustness, making it the recommended model for deployment. Logistic Regression offered the best explainability, while XGBoost performed competitively across metrics.

6.	Key Drivers of Churn
The analysis revealed major churn drivers:
• Month-to-month contract type
• Low tenure
• High monthly charges
• Lack of support services (Tech Support, Online Security)
• Fiber optic internet service
• Paperless billing
• Senior citizen customers
• Lack of device protection These factors provide the foundation for targeted retention efforts.

7.	Strategic Recommendations
Based on the insights, the following strategies are recommended:
1. Reduce month-to-month churn through incentives and loyalty programs.
2. Improve early customer experience with onboarding support.
3. Increase adoption of service bundles such as security and tech support.
4. Diagnose and address dissatisfaction among fiber optic users.
5. Offer value-based pricing to high-charge customers.
6. Improve engagement and communication for paperless billing users.
7. Provide simplified plans and dedicated support for senior citizens.
8. Promote device protection bundles to reduce service frustration.

9.	Model Deployment
The Random Forest model has been deployed using Streamlit. All encoders, the model file, and preprocessing steps have been packaged for real-time predictions. The app allows business teams to input customer attributes and instantly receive churn predictions, supporting fast, data-driven decision-making.

10.	Business Impact
    Implementing churn prediction and retention strategies will:
• Reduce customer loss and stabilize recurring revenue.
• Improve targeting for marketing and retention campaigns.
• Enhance customer satisfaction and lifetime value.
• Support strategic service improvements based on data-driven insights.
  Overall, this system empowers the business with proactive churn management capabilities.

12.	Conclusion
The churn analysis and predictive model provide a clear understanding of why customers leave and how to prevent it. Using the Random Forest model, the company can identify at-risk customers early and take effective action. This report lays the groundwork for stronger retention strategies, improved customer experience, and long-term revenue growth.

View Deployment
https://customer-churn-prediction-tele-app.streamlit.app/
