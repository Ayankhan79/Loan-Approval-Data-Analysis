

## 🔍 **Insights i Gained From the Loan EDA**



#### **1. Credit history is the biggest deciding factor**

Applicants with a **good credit record (1)** were approved far more often.
Even high-income applicants with **bad credit (0)** faced rejection.

---

#### **2. High income ≠ Guaranteed loan approval**

Income alone didn’t influence approval strongly.
Banks clearly prioritize **repayment behaviour** over salary.

---

#### **3. Very high loan amounts had lower approval**

Moderate loan requests were approved more.
Large loan amounts increased the chance of rejection.

---

#### **4. Property area affects approval rates**

**Semi-Urban** applicants had the highest approval.
Rural areas had the lowest, possibly due to repayment risk.

---

#### **5. Married applicants had slightly better approval**

Marriage showed a small advantage—likely because of **combined income** or stability.

---

#### **6. Graduates were approved more often**

Being a **Graduate** gave a slight advantage over Non-Graduates.

---

#### **7. Self-employed applicants had similar approval rates**

Employment type didn’t drastically affect outcomes.

---

#### **8. More dependents → slightly lower approval**

Applicants with **3+ dependents** had lower approval, likely due to higher expenses.

---

#### **9. Income features had outliers and skewness**

ApplicantIncome and LoanAmount showed **extreme values** and right-skewness,
important for transformation in ML models.

---

#### **10. Numerical features weren’t highly correlated**

No strong multicollinearity.
Applicant and Coapplicant incomes added different information.

---

#### **11. Total Income was more meaningful**

The engineered **Total_Income** feature showed clearer patterns than individual incomes,
especially when paired with credit history.

---



