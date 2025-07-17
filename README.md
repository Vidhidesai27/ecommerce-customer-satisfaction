# 🛍️ E-commerce Customer Satisfaction Analysis (SPSS)

This project analyzes customer satisfaction on an e-commerce platform using survey data from 3,900 users. Logistic regression was conducted in IBM SPSS to identify the most significant factors influencing whether a customer is satisfied based on demographics, purchase behavior, and service-related variables.

## 🧠 Objective
Determine which customer and purchase characteristics significantly influence satisfaction ratings to inform strategy and marketing.

## 🔍 Key Variables
- **Dependent Variable**: Customer Satisfaction (0 = Not Satisfied/Neutral, 1 = Satisfied)
- **Independent Variables**:
  - Age
  - Gender (Female = 1, Male = 0)
  - Purchase Amount (USD)
  - Applied Discount (Yes/No)
  - Express Shipping (Yes/No)
  - Subscription Status (Yes/No)

## 📊 Methodology
- Tool: IBM SPSS Statistics
- Technique: Binary Logistic Regression
- Classification threshold optimized (cut-off: 0.37)
- Key metrics:
  - Nagelkerke R² = 0.547
  - Model Hit Rate = 79.7%

## 📌 Insights
- Discounts have the strongest impact on satisfaction (Exp(B) = 56.06)
- Female customers are 4.19× more likely to be satisfied
- Express shipping improves satisfaction likelihood
- Subscribed users were surprisingly less satisfied than unsubscribed users

## 📁 Files Included
- `Raw Data_Customer Satisfaction_Kaggle.sav` – Raw data file (SPSS)
- `Analysis Output_Customer Satisfaction.spv` – SPSS output file
- `E-commerce Customer Satisfaction Analysis_Report.pdf` – Full report with visuals and interpretation

## 🛠 Tools Used
- IBM SPSS Statistics
- Logistic Regression Modeling
- Survey Analysis
- Categorical Variable Encoding

## 📬 Contact
Vidhi Desai  
[LinkedIn](https://www.linkedin.com/in/Vidhidesai27)  
