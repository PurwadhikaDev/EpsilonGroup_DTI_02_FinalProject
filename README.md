# EpsilonGroup_DTI_02_FinalProject
# E-Commerce Customer Churn Analysis and Prediction

### **Context**  
In the fast-growing e-commerce industry, customer churn is a major challenge that directly affects revenue and business sustainability. Retaining existing customers is far more cost-effective than acquiring new ones, making churn prediction a key priority for online retail companies.  

This dataset, provided by a leading e-commerce company, captures customer interactions, purchasing behaviors, and satisfaction levels. The company aims to identify customers at risk of churning and take **data-driven actions** to improve retention. The dataset includes attributes such as **customer tenure, order history, payment preferences, complaint records, and engagement time** on the platform.  

By analyzing these factors, we will uncover the key drivers of churn and build a predictive model to classify customers as **likely to churn or remain active**. This will enable the company to deploy targeted interventions—such as personalized promotions, loyalty programs, and enhanced customer support—to maximize retention and long-term profitability.  

---

### **Problem Statement**  
Customer churn is a major challenge for e-commerce businesses, leading to revenue loss and increased costs for acquiring new customers. The ability to predict which customers are likely to churn allows businesses to implement proactive retention strategies, such as personalized promotions, improved customer service, and loyalty programs.  

This project aims to analyze customer behavior data to identify patterns associated with churn. By leveraging historical data—including customer tenure, purchase frequency, preferred payment methods, satisfaction scores, and engagement levels—we seek to develop a **predictive model** that can accurately classify customers as **churned or retained**.  

The insights gained from this analysis will enable the company to:  
1. **Identify early warning signs** of churn.  
2. **Optimize retention strategies** based on data-driven decisions.  
3. **Improve customer lifetime value (CLV)** by reducing churn rates.  

By solving this problem, the e-commerce company can enhance its customer retention efforts, increase profitability, and build stronger customer relationships.  

---

### **Goals**  
The objective of this project is to **analyze customer behavior and predict churn** to help an e-commerce company reduce customer attrition and improve retention strategies. This will be achieved through the following key goals:  

1. **Understand Customer Churn Drivers**  
   - Analyze customer demographics, purchase behavior, engagement levels, and satisfaction scores.  
   - Identify key factors contributing to churn and retention.  

2. **Develop a Predictive Model**  
   - Build a **machine learning model** that accurately classifies customers as **churned or retained**.  
   - Optimize model performance using appropriate evaluation metrics.  

3. **Provide Actionable Business Insights**  
   - Deliver **data-driven recommendations** for customer retention strategies.  
   - Enable the company to implement **targeted marketing campaigns**, personalized promotions, and loyalty programs.  

4. **Maximize Customer Lifetime Value (CLV) & Revenue**  
   - Reduce churn rates and improve customer retention.  
   - Minimize customer acquisition costs by enhancing retention efforts.  
   - Strengthen customer relationships to drive long-term profitability.  

By achieving these goals, the company can **proactively address churn**, increase customer satisfaction, and enhance overall business performance.  

---

# Project Outline

## 1. Business Problem Understanding
- **Objective:** Understand the overall business, the problem encountered, and suggested solutions.
- **Description:** Analyze the business context, identify challenges, and propose actionable solutions.

## 2. Data Understanding
- **Objective:** Explore the data.
- **Description:** Dive into the dataset and import the required libraries to support the machine learning development process.

## 3. Exploratory Data Analysis (EDA)
- **Objective:** Uncover insights, patterns, and relationships within the data.
- **Description:** Utilize visualization graphs to discover insights and justify the chosen methods or approaches for subsequent sections.

## 4. Data Preprocessing
- **Objective:** Clean and prepare the raw dataset.
- **Description:** Handle duplicated values, missing values, and outliers to improve overall accuracy, as these issues can negatively affect the machine learning training process.

## 5. Feature Engineering
- **Objective:** Transform and optimize features for model input.
- **Description:** Apply encoding and scaling techniques to the dataset’s features before feeding the data into the machine learning model.

## 6. Modeling
- **Objective:** Build and optimize machine learning models.
- **Description:** Explore various machine learning models, different data approaches, and hyperparameter tuning to obtain the best fit results. Analyze each benchmark method and its potential business impact.

## 7. Conclusion and Recommendation
- **Objective:** Summarize findings and provide actionable recommendations.
- **Description:** Deliver conclusions from both business and machine learning perspectives. Offer recommendations for stakeholders to boost business profit or further improve machine learning development for better overall accuracy.

## 8. Model Export
- **Objective:** Deploy the finalized model.
- **Description:** Export the machine learning model as a `.pkl` file. This exported model will be used to generate new predictions based on user-provided features.

---

# Project Directory

- **Dataset**
  - `E Commerce Dataset.xlsx` : Raw dataset.
- **Tableau Dashboard**
  - [`E Commerce Dashboard`](https://public.tableau.com/app/profile/garnet.ezra/viz/FinalProjectEpsilonGroup/Story1) : Interactive Tableau dashboard for visualizing the E-Commerce insights.
- **Model**
  - `Ecommerce-customers-churn-clasification-Model.pkl` : Exported machine learning workflow model, including data preprocessing, feature engineering, oversampling, and prediction using the XGBoost model.
- **Notebook**
  - `Data Analysis.ipynb` : Data Analysis Jupyter Notebook.
  - `epsilon_modelling - f1.ipynb` : Modelling Jupyter Notebook

