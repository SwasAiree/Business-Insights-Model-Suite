# Business-Insights-Model-Suite
Data-driven solutions for sales forecasting, customer behaviour modelling, churn risk, and production planning.

# Business Analytics Modelling Suite

This project demonstrates a collection of practical data modelling solutions across five unique business cases, involving regression, logistic regression, interaction analysis, and time series forecasting. Each model was designed to support data-driven decisions using real-world structured data.

---

## 🎯 Overview

The project showcases how analytical models can be designed and validated to solve business problems across domains including retail forecasting, marketing effectiveness, customer behaviour prediction, employee churn, and production forecasting. The focus is on model precision, explainability, and actionable insights for decision-makers.

---

## 🔍 Business Cases and Models

### 1. **Retail Sales Forecasting – GroceryPlus**
A multivariate regression model was developed to estimate in-store sales based on wages and advertisement spend. Model refinement included:
- Handling multicollinearity using backward elimination
- Diagnostic checks for residual normality
- Model performance: Strong fit with clearly interpretable coefficients

> 🧠 *Skills Demonstrated: Correlation analysis, feature selection, model iteration, transformation (Box-Cox), linear regression*

---

### 2. **Marketing Campaign Analysis – BikeMart**
Built a model to assess the interaction between advertising spend and promotional campaign count on sales:
- Introduced interaction term
- Conducted two-way ANOVA and regression interpretation
- Verified assumptions through residual plots
<img width="940" height="554" alt="image" src="https://github.com/user-attachments/assets/b32b1dd1-4d20-4983-8e04-e9fe29e1f194" />
<img width="446" height="205" alt="image" src="https://github.com/user-attachments/assets/8305911b-6d14-4dbe-b3e2-10930644c8c9" />

> 🧠 *Skills Demonstrated: Interaction effect modelling, visual analysis, ANOVA, business communication of interaction dynamics*

---

### 3. **Customer Conversion Modelling – Gadget4U**
Developed a logistic regression model to predict the probability of a customer buying headphones after purchasing a smartphone:
- Key drivers identified: Gender and advertisement click-through rate
- Model performance: 74.66% accuracy, AUC: 73.52%

> 🧠 *Skills Demonstrated: Binary classification, backward elimination, odds ratio interpretation, AUC evaluation*
<img width="613" height="306" alt="image" src="https://github.com/user-attachments/assets/04647cc1-d05a-42cd-ba52-ec39e06cfa76" />

---

### 4. **Employee Resignation Risk – CosmeticChain**
A logistic model was constructed to estimate the resignation likelihood of store managers based on age, gender, and experience:
- Delivered both regression model and probability visualisations
- Found that resignation likelihood increases significantly with experience and is higher for males

> 🧠 *Skills Demonstrated: Logistic regression, dummy variable encoding, probability modelling, predictive visualisation*
<img width="786" height="422" alt="image" src="https://github.com/user-attachments/assets/ac7e4a88-ed68-4a27-a501-353054be370a" />

---

### 5. **Production Forecasting – MoonlightAle**
Built a seasonal time series forecasting model to predict quarterly Pale Ale production:
- Applied 4-period moving average smoothing
- Deseasonalised and re-seasonalised trend modelling
- Forecast Accuracy: 96.34% (Average APE: 3.66%)
<img width="940" height="466" alt="image" src="https://github.com/user-attachments/assets/1a393310-39ae-4129-a14d-7e6f9060dbd1" />

> 🧠 *Skills Demonstrated: Time series decomposition, seasonal index, trend modelling, forecast validation*

---

## 📈 Techniques Used

- Multiple Linear Regression (with diagnostics)
- Logistic Regression & Classification Metrics (Accuracy, AUC)
- Interaction Effect & ANOVA
- Odds Ratio & Probability Visualisation
- Time Series Smoothing and Seasonal Forecasting
- Residual Analysis, Backward Elimination, and Model Tuning

---

## 📁 Files Included

- `A2.docx`: Final technical report with detailed modelling insights
- `A2.xlsx`: Excel workbook with all model iterations and diagnostics

---

## 🧠 Key Takeaways

- Predictive modelling is most effective when supported by diagnostic rigor and business interpretability
- Visual communication of results (like probability plots or interaction charts) enhances stakeholder understanding
- Combining statistical methods with business logic creates stronger recommendations

---

## 🛠 Tools & Technologies

- Microsoft Excel (Advanced analytics & modelling)
- Visual plotting and regression tools
- Statistical frameworks (logistic regression, time series, ANOVA)

---

## 👤 Author

**Swas Airee**  
Business Analyst | Data Modelling | Predictive Forecasting  

---

*This project was completed as part of an academic coursework assignment.*
