# **Pig E. Bank - Customer Churn Analysis**  

## **Objective**  
This analysis aims to identify the leading **risk factors** contributing to customer churn at Pig E. Bank. By leveraging client attribute data, we seek to provide actionable insights to reduce attrition and improve customer retention.

---

## **Key Findings**  

### **1. Inactive Membership is the Strongest Churn Indicator**  
- **70% of customers who left were inactive members**, compared to only **44% of inactive customers who stayed**.

<img width="549" alt="image" src="https://github.com/user-attachments/assets/c2e227b0-2787-42a2-a5b3-b58ada939ddd" />
  
- Active membership significantly correlates with customer retention, making engagement a critical area for intervention.

### **2. Older Customers Are More Likely to Leave**  
- **Median age of customers who left: 45 years**  
- **Median age of customers who stayed: 36 years**

<img width="549" alt="image" src="https://github.com/user-attachments/assets/0c67f0ba-22a6-4ed3-b342-bfc48e187b52" />
  
- Retention strategies should focus on engaging older clients, possibly through personalized financial products or customer support initiatives.

### **3. Number of Products and Customer Churn**  

  <img width="361" alt="image" src="https://github.com/user-attachments/assets/4cac92ef-3302-4a46-846e-1532b26a81e4" />


- **70% of customers who left had only one product**, whereas **customers with multiple products exhibited significantly lower churn rates (47%)**.  
- Encouraging cross-selling strategies or bundling services could improve customer loyalty.

### **4. Credit Score as a Churn Indicator**  
- Customers who left had a **lower mean credit score (637)** compared to those who stayed (**652**).  
- Lower credit scores may indicate **financial instability** or **a lack of engagement with the bank’s financial offerings**.  
- Monitoring and proactively engaging customers with lower credit scores could mitigate churn risk.

  <img width="869" alt="Screenshot 2025-02-14 at 17 22 07" src="https://github.com/user-attachments/assets/488779ad-515d-4d00-8b2f-281aa609e991" />
---

### **Decision Tree Flow**  
1. **Is the customer an active member?**  
   - If **yes** → Having more than one product leads to the **lowest risk of leaving**.  
   - If **no** → The number of products, age, and credit score significantly impact churn risk.  

2. **Number of products held**  
   - Customers with **more than one product** are less likely to leave.  
   - Customers with **only one product** face higher churn risk, especially if they are **inactive** or have **low credit scores**.  

3. **Age and Credit Score Segmentation**  
   - **Older customers (45+)** who are inactive and have only one product show **higher churn tendencies**.  
   - **Credit score below 650** is a critical risk indicator, further increasing churn likelihood.  

![image](https://github.com/user-attachments/assets/2701d4df-3eee-49cd-bb28-cb16827ea758)

  
---

## **Data-Driven Recommendations**  

### **1. Improve Active Membership Rates**  
- Implement **loyalty programs** that encourage customers to remain engaged.  
- Offer **personalized incentives** for active usage, such as fee waivers for frequent transactions.

### **2. Target High-Risk Age Groups with Retention Campaigns**  
- Provide **customized banking products** that cater to customers aged 40+.  
- Enhance digital onboarding and financial advisory services to improve engagement.

### **3. Increase Product Offerings to Reduce Single-Product Customers**  
- Promote **multi-product bundling** (e.g., pairing credit accounts with investment products).  
- Launch targeted marketing campaigns to **educate customers** on additional services.

### **4. Monitor Customers with Low Credit Scores**  
- Offer **financial advisory sessions** for customers with lower scores.  
- Implement **early intervention strategies**, such as tailored loan products or credit-building programs.

---

## **Next Steps**  
1. **Develop a Predictive Model**: Implement a **decision tree** to classify customers based on their likelihood of churning.  
2. **Enhance Customer Retention Dashboard**: Build a **Tableau or Power BI dashboard** to continuously monitor high-risk customers.  
3. **A/B Testing for Retention Strategies**: Test personalized retention strategies to measure their effectiveness.  

By implementing these **data-backed strategies**, Pig E. Bank can enhance customer engagement, reduce churn, and optimize long-term client retention.  

