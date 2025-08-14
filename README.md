# 📞 Telco Customer Churn

## 📚 About The Data
This project uses the [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) dataset from Kaggle.
The dataset contains 7,043 customer records and 21 features detailing demographic information, customer account details, subscribed services, and whether the customer churned (Yes/No).

Key fields include:
- Churn – Target variable indicating if a customer left the company.
- Tenure – Number of months a customer has stayed.
- Contract – Month-to-month, one-year, or two-year agreements.
- PaymentMethod – Billing method used.
- MonthlyCharges & TotalCharges – Billing amounts.
- Service-related features such as InternetService, OnlineSecurity, TechSupport, StreamingTV, and MultipleLines.

## 📊 Visulization
The [Churn Rate Dashboard](https://public.tableau.com/app/profile/alesia.miloshevsky/viz/ChurnRateDashboard_17549280197830/ChurnRateDashboard) was created using Tableau.

<img width="2559" height="1412" alt="Churn Rate Dashboard" src="https://github.com/user-attachments/assets/ac6b364b-28ff-4ffe-abea-5e72be5a09ca" />

## 🔍 Key Insights
- **Month-to-month contract** customers show the highest churn rates, especially with short tenure and higher monthly charges.
- **Longer tenure** significantly reduces churn, indicating increased loyalty over time.
- Customers paying via **electronic check** have a higher churn rate than those using credit card or bank transfers.
- Customers with higher **TotalCharges** (long-term customers) tend to churn less, even when monthly charges are high.

## 💡 Recommendations
- Offer **incentives** to move month-to-month customers to yearly or two-year contracts.
- Create **loyalty rewards** for customers who reach specific tenure milestones.
- Promote **more secure and convenient payment methods** to electronic check users.
- Engage **new customers early** with personalized offers to prevent early churn.
