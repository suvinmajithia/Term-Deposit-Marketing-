Term Deposit Subscription Prediction
Smart Marketing Targeting for European Banking Clients

🚀 Overview
This project builds a predictive model to determine whether a customer will subscribe to a term deposit, based on direct marketing campaign data. By leveraging classification techniques, the model helps banking teams prioritize leads and optimize campaign strategies.

🧠 Objective
Predict customer subscription decisions and uncover key behavioral and demographic patterns that influence outcomes.

🛠 Technologies Used
Python
Scikit-learn
Pandas / NumPy
Matplotlib
Jupyter Notebook

🧬 Methodology
1. Data Understanding
   Explore customer attributes like job, balance, contact method, loan status, and previous campaign outcomes.

2. Preprocessing & Feature Engineering
   Encode categorical features
   Handle class imbalance
   Scale numerical features

3. Modeling
   Train classification models (Logistic Regression, Random Forest, etc.)
   Evaluate using 5-fold cross-validation

4. Interpretability
   Identify which features (e.g., contact type, previous outcome, balance) most influence deposit subscription decisions.

📊 Dataset
Source: Direct marketing campaign data from a European bank
Target:
y — Whether the client subscribed to a term deposit (yes/no)
Key Features:
Demographics (age, job, marital, education)
Financials (balance, housing/personal loan)
Campaign interaction (contact type, duration, outcome)


✅ Goals
1. Improve marketing efficiency with accurate lead prediction.
2. Highlight customer segments with high conversion likelihood.
3. Assist marketing teams in targeting the right users at the right time.

📈 Success Metrics
1. Achieve >81% accuracy via cross-validation.
2. Precision/recall on subscribed vs. non-subscribed customers.
3. Actionable feature importance for business decision-making.

🔁 Future Extensions
1. Deploy model as a REST API for real-time call center support.
2. Integrate SHAP for explainable predictions.
3. Build interactive dashboards for business teams.
