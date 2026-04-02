Customer Retention & Churn Analysis System

Project Overview

Customer retention is a key factor in the success of any business. When customers discontinue a service or stop purchasing products, it is known as customer churn. High churn rates can negatively affect revenue, brand value, and growth.

In industries like banking, telecom, and e-commerce, companies collect large volumes of customer data. However, analyzing this data manually is inefficient and often restricted due to privacy concerns.

This project addresses these challenges by building a Customer Churn Analysis System using synthetic data. The dataset is generated using the Faker library, enabling safe and realistic data simulation. The system then applies data analysis techniques to uncover patterns that influence customer churn.

Project Goals

This project aims to:

Create a realistic synthetic dataset for churn analysis Simulate customer behavior in a business environment Clean and preprocess raw data effectively Perform Exploratory Data Analysis (EDA) Identify key factors affecting customer churn Analyze relationships between different variables Visualize insights using graphs and charts Suggest strategies to improve customer retention

Dataset Overview

The dataset contains 100,000 synthetic customer records, each representing different behavioral and financial attributes.

Column Name Description Customer_ID Unique customer identifier Age Age of the customer (18–70) Gender Male / Female Tenure Years with the company Balance Account balance CreditScore Credit score (300–900) EstimatedSalary Annual salary NumOfProducts Number of products used IsActiveMember Activity status (0/1) Churn Target variable (0 = No, 1 = Yes)

Technologies Used

Python Pandas NumPy Matplotlib Seaborn Faker

Project Workflow

Data Simulation Generated synthetic customer data using Faker Applied realistic constraints and distributions Data Preparation Checked for null and duplicate values Corrected data types and ensured consistency Exploratory Data Analysis (EDA) Calculated statistical metrics Studied feature distributions Detected outliers Churn Analysis Compared churned vs retained customers Identified high-risk groups Segmentation Analysis Age group vs churn Gender vs churn Active members vs churn Product usage vs churn Correlation Analysis Balance vs churn Credit score vs churn Tenure vs churn Data Visualization Bar charts Pie charts Histograms Box plots Scatter plots Heatmaps

Key Findings

Customers with low balances are more likely to churn Lower credit scores are linked to higher churn Inactive users show the highest churn rate Customers using multiple products are more loyal Higher engagement leads to better retention Long-term customers (higher tenure) tend to stay

How to Run the Project

Step 1: Install Dependencies pip install pandas numpy matplotlib seaborn faker Step 2: Run the Code

You can execute the project using:

Jupyter Notebook Google Colab VS Code

Project Structure

Customer-Churn-Analysis/ │ ├── churn_analysis.py ├── customer_data.csv ├── README.md └── visualizations/

Future Enhancements

Build Machine Learning models (Logistic Regression, Decision Tree) Develop a churn prediction system Create interactive dashboards using Power BI or Tableau Deploy as a web application using Flask or Django

Output Preview
Histogram
<img width="783" height="565" alt="image" src="https://github.com/user-attachments/assets/e9908318-ad0e-40f9-aa16-f0bcdf2379c3" />
Pie Chart
<img width="540" height="512" alt="image" src="https://github.com/user-attachments/assets/5b04f5a6-59e9-482b-b42a-2e052d30d0a7" />
Scatter Plot
<img width="807" height="585" alt="image" src="https://github.com/user-attachments/assets/fe542853-75d3-4857-ac3b-369508f78d1d" />
Heatmap
<img width="1027" height="714" alt="image" src="https://github.com/user-attachments/assets/72a62aec-adba-41a9-b309-c9746170db89" />




Customer distribution charts Churn comparison graphs Correlation heatmap Trend visualizations

Outout Overview
