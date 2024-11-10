---

### **Project: Loan Eligibility Prediction for Dream Housing Finance**

---

dd

### **Project Description:**

This project focuses on analyzing loan application data from Dream Housing Finance to predict loan eligibility for customers. The aim is to develop a machine learning model that can automate the process of determining whether a loan application is likely to be approved, based on a range of customer attributes and financial details.

By analyzing factors such as:

- **Applicant and coapplicant income**
- **Credit history**
- **Loan amount**
- **Demographic details (e.g., gender, marital status, dependents, property area)**

we aim to create a predictive solution that can help the company streamline its loan approval process and efficiently target eligible customers.

---

### **Objectives:**

1. **Data Cleaning:**

   - Handle missing values and outliers to ensure a clean dataset for analysis and modeling.

2. **Data Visualization:**

   - Create visualizations to identify key trends and patterns in the loan application data, focusing on factors that influence loan eligibility.

3. **Correlation and Feature Analysis:**

   - Explore the relationships between various features such as income, credit history, and property area to determine their impact on loan approval.

4. **Encoding and Normalization:**

   - Prepare the dataset by encoding categorical variables and normalizing numerical data for further predictive modeling.

---

### **Dataset Overview:**

The dataset consists of loan application records from Dream Housing Finance, including details such as:

- **Loan ID**: Unique identifier for each loan application.
- **Gender**: Gender of the applicant (Male/Female).
- **Marital Status**: Whether the applicant is married (Yes/No).
- **Dependents**: Number of dependents.
- **Education**: Education level of the applicant (Graduate/Undergraduate).
- **Self-Employed**: Employment status of the applicant (Yes/No).
- **ApplicantIncome**: Income of the applicant.
- **CoapplicantIncome**: Income of the coapplicant.
- **LoanAmount**: Loan amount requested (in thousands).
- **Loan_Amount_Term**: Loan term duration (in months).
- **Credit_History**: Indicator of credit history (meets guidelines or not).
- **Property_Area**: Type of property area (Urban/Semi-Urban/Rural).
- **Loan_Status**: Target variable indicating loan approval status (Yes/No).

This comprehensive data provides a solid foundation for analyzing loan eligibility factors and building a robust prediction model.

---

### **Analysis Steps:**

⓵ **Data Cleaning:**

   - Handle missing values and detect outliers to ensure data quality.

⓶ **Data Exploration and Visualization:**

   - Analyze demographic and financial variables to identify patterns influencing loan eligibility.

⓷ **Feature Engineering and Encoding:**

   - Transform categorical variables and normalize numerical data for accurate analysis and model training.

⓸ **Answer Key Business Questions:**

   ### **Business Questions:**


  1. **What is the relationship between the applicant’s income and the requested loan amount?**
    - Does an increase in the applicant’s income correlate with a higher loan amount requested?

  2. **What is the impact of credit history on the likelihood of loan approval?**
    - Do loans with applicants who have a good credit history have a higher chance of being approved?

  3. **Which geographical regions have higher approval rates for loans?**
    - Are urban areas more likely to have loan approvals compared to semi-urban or rural areas?


   
---

### **Required Libraries:**

- **pandas**
- **matplotlib**
- **seaborn**
- **sklearn**

---
