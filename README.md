# FUTURE_DS_02
# Customer Support Data Analysis - Project Summary

**Intern Name:** Thoulath Irfana M  
**Company:** Future Interns  
**Project Title:** Customer Support Data Analysis & Ticket Resolution  
**Project Type:** Data Science & Analytics  

## 🎯 Objective
The objective of this project was to explore, analyze, and model customer support ticket data to uncover patterns and trends affecting customer satisfaction and resolution times. The goal was to derive actionable insights and build predictive models to improve ticket resolution and customer experience.

---

## 📊 Dataset Overview
- **Total Records:** 2769
- **Key Variables Analyzed:**
  - **Customer Age**
  - **First Response Time**
  - **Time to Resolution**
  - **Ticket Priority**
  - **Ticket Type**
  - **Customer Satisfaction Rating**

---

## 🔍 Key Insights & Trends

### **Satisfaction by Ticket Type:**
| Ticket Type               | Avg. Satisfaction |
|---------------------------|-------------------|
| 💳 Billing Inquiry         | 3.03              |
| ❌ Cancellation Request    | 3.03              |
| 📦 Product Inquiry         | 3.02              |
| 💸 Refund Request          | 2.93              |
| 🛠 Technical Issue         | 2.96              |

- **Billing and Cancellation** requests tend to result in higher satisfaction compared to other ticket types.

### **Satisfaction by Ticket Priority:**
| Priority      | Avg. Satisfaction |
|---------------|-------------------|
| 🟢 Low         | 3.05 *(Highest)*  |
| 🔴 Critical    | 2.96 *(Lowest)*   |

- **Low-priority tickets** generally lead to **higher satisfaction**.

### **Resolution Time & Satisfaction:**
- A **downward trend** was observed between resolution time and customer satisfaction.
- Longer **resolution times** generally lead to **lower customer satisfaction**.

### **Correlation Matrix Findings:**
- There is a **weak negative correlation** between Time to Resolution and Satisfaction (**-0.08**).
- No strong linear relationships were found in the current dataset.

---

## 🤖 Model Development: Ridge Regression

### **Model Summary:**
- **Raw Mean Squared Error (MSE):** 2.30
- **Scaled Mean Squared Error (MSE):** 2.07
- **R-squared (Scaled):** -0.05

### **Model Interpretation:**
- The **Ridge Regression** model did not generalize well, as indicated by the negative R-squared value.
- The model suggests **non-linear patterns or insufficient features**.
- For better performance, more advanced models such as **Random Forest** or **XGBoost** should be considered.

---

## 💡 Recommendations:

1. **Integrate Text Analysis:** Perform sentiment analysis on customer feedback to gain deeper insights.
2. **Try Advanced Models:** Explore smarter models like **Random Forest** or **Neural Networks** for better accuracy.
3. **Focus on Key Factors:** Investigate the resolution of low-priority tickets to improve satisfaction.
4. **Feature Engineering:** Derive additional features from ticket descriptions and response logs.

---

## 📝 Conclusion
- **Quick resolutions** and **low-priority tickets** lead to **higher satisfaction**.
- **Billing and Cancellation** tickets tend to have higher ratings.
- The current **Ridge Regression** model is limited and does not capture complex patterns; **further data enrichment** and **advanced models** are needed.

---

**Intern Name:**  
Thoulath Irfana M  
Data Science Intern, Future Interns
