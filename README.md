# Institutional Credit Risk & Probability of Default (PD) Engine

An institutional credit risk framework built in Python to evaluate borrower default likelihood, construct explainable credit scoring cutoffs, and quantify provisioned Expected Loss (EL) aligned with Basel II/III banking standards.

---

## 📊 Credit Risk Distribution
![Score Stratification](credit_score_stratification.png)

---

## 💼 Financial & Regulatory Scope
- **Probability of Default (PD):** Trained calibrated Logistic Regression modeling debt-to-income (DTI), past delinquencies, and revolving credit utilization.
- **Model Discrimination Metrics:** Evaluated Gini coefficient, ROC-AUC, and Brier calibration score for probability accuracy.
- **Expected Loss (EL) Modeling:** Applied regulatory formula: $EL = PD \times LGD \times EAD$ assuming a standard 45% Loss Given Default on unsecured commitments.
- **Capital Provisioning:** Computed aggregate reserve requirements across an enterprise loan book.

---

## 🛠️ Tech Stack
- **Languages & Frameworks:** Python, Scikit-Learn, Pandas, NumPy, Matplotlib
- **Concepts:** Basel Framework, Credit Scorecard Engineering, Expected Loss Provisioning
