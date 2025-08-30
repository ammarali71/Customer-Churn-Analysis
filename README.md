# Telco Customer Churn Analysis

## 🔍 Project Overview
This project analyzes customer churn in a telecom company dataset to uncover why customers leave and how to retain them. Using Python and data visualization, we identified key churn drivers and provided actionable recommendations.

---

## 📊 Key Findings
- **Overall Churn Rate:** 26.54% (approx. 1 in 4 customers)

### **1. By Contract Type**
- Month-to-month: **42.7% churn**
- One-year: **11.3% churn**
- Two-year: **2.8% churn**

### **2. By Payment Method**
- Electronic check: **45.3% churn** (highest)
- Bank transfer: **16.7% churn**
- Credit card: **15.2% churn**
- Mailed check: **19.1% churn**

### **3. By Senior Citizen**
- Seniors: **41.7% churn**
- Non-seniors: **23.6% churn**

### **4. By Tenure**
- 0-12 months: **47.7% churn**
- 49-72 months: **9.5% churn**

---

## 📷 Visual Insights
![Churn by Contract](charts/churn_by_contract.png)
![Churn by Payment](charts/churn_by_payment.png)
![Churn by Senior Status](charts/churn_by_senior.png)
![Churn by Tenure](charts/churn_by_tenure.png)

---

## 📝 Recommendations
- **Promote long-term contracts** with discounts and incentives.
- **Target new customers** with loyalty benefits to reduce early churn.
- **Encourage auto-pay options** to reduce reliance on electronic checks.
- **Bundle value-added services** like Online Security and Tech Support.

---

## 🛠 Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook

---

## 🗂 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Telco-Customer-Churn-Analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Telco-Customer-Churn-Analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the notebook:
   ```bash
   jupyter notebook notebooks/TCA.ipynb
   ```

---

## 🔗 Links
- **Executive Summary PDF:** [reports/Telco Customer Churn Analysis.pdf](reports/Telco%20Customer%20Churn%20Analysis.pdf)
- **Dataset:** [data/Customer_Churn.csv](data/Customer_Churn.csv)

---

### 💡 Business Impact
By implementing these strategies, companies can significantly **reduce churn from 26.5% to below 15%**, improving customer lifetime value and revenue stability.
