# Amazon Diwali India Sales Analysis (2025) 📊

## An Exploratory Data Analysis (EDA) and Business Intelligence Project

**Project Type:** Data Analytics and Business Intelligence

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Microsoft Excel, Power BI, GitHub

**Dataset:** Amazon Diwali India Sales Dataset (2025)

**Domain:** E-commerce | Data Analytics | EDA | Business Intelligence

---
## 📌 Table of Contents
---
- [Project Overview](#-project-overview)
- [Project Objectives](#-project-objectives)
- [Dataset Description](#-dataset-description)
- [Dataset Information](#-dataset-information)
- [Tools and Technologies](#-tools-and-technologies)
- [Project Workflow](#-project-workflow)
- [Data Cleaning and Preprocessing](#-data-cleaning-and-preprocessing)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Performance Indicators (KPIs)](#-key-performance-indicators-kpis)
- [Important Columns](#-important-columns)
- [Power BI Dashboard](#-power-bi-dashboard)
- [Key Business Insights](#-key-business-insights)
- [Business Recommendations](#-business-recommendations)
- [Conclusion](#-conclusion)

  ---
   ## 📖 Project Overview
  ---
The **Amazon Diwali India Sales Analysis (2025)** project focuses on analyzing e-commerce sales transactions to understand customer purchasing behavior, product performance, payment preferences, delivery status, and customer feedback.

The dataset was downloaded from Kaggle and cleaned and preprocessed using Python. Exploratory Data Analysis (EDA) was performed to understand the data and identify meaningful patterns and trends.

After data cleaning and analysis, Power BI was used to develop an interactive dashboard to visualize important sales metrics and business performance.

This project demonstrates how Python and Power BI can be used to transform raw e-commerce data into meaningful business insights.

---
## 🎯 Project Objectives
---

- Analyze overall e-commerce sales performance.
- Identify top-performing product categories.
- Understand customer purchasing behavior.
- Analyze payment method preferences.
- Track delivered, returned, and pending orders.
- Evaluate customer ratings and feedback.
- Analyze state-wise sales performance.
- Identify important sales trends and patterns.
- Develop an interactive Power BI dashboard.
- Generate meaningful business insights for decision-making.
---
 ## 📂 Dataset Description
---

The **Amazon Diwali India Sales Dataset (2025)** is a synthetic e-commerce dataset containing **15,000 transactions**.

It simulates Amazon India sales activities and includes information about customer purchases, product categories, pricing, payment methods, delivery status, and customer reviews.

The dataset is useful for practicing data cleaning, exploratory data analysis, and business intelligence reporting.

---
### Dataset Information
---

| Dataset Attribute  | Description                              |
| :----------------- | :--------------------------------------- |
| Dataset Name       | Amazon Diwali India Sales Dataset (2025) |
| Data Source        | Kaggle                                   |
| File Format        | CSV                                      |
| Total Records      | 15,000 Transactions                      |
| Data Type          | Synthetic E-commerce Data                |
| Domain             | E-commerce and Retail                    |
| Country            | India                                    |
| Currency           | Indian Rupees (INR)                      |
| Data Analysis Tool | Python                                   |
| Dashboard Tool     | Power BI                                 |

---
## 🛠️ Tools and Technologies
---
| Tools           | Purpose                   | Application                          |
|:----------------|:--------------------------|:-------------------------------------|
| Python          | Programming Language      | Data cleaning and analysis           |
| Pandas          | Data Manipulation         | Handling and analyzing data          |
| NumPy           | Numerical Operations      | Performing numerical calculations    |
| Matplotlib      | Data Visualization        | Creating charts and graphs           |
| Seaborn         | Statistical Visualization | Visualizing data patterns            |
| Microsoft Excel | Data Inspection           | Checking and validating data         |
| Power BI        | Business Intelligence     | Developing interactive dashboards    |
| GitHub          | Version Control           | Project documentation and management |

---
## 🔄 Project Workflow
---
| Step | Workflow              | Description                                                              |
|:----:|:----------------------|:-------------------------------------------------------------------------|
| 1    | Data Collection       | Downloaded the dataset from Kaggle.                                      |
| 2    | Data Understanding    | Examined dataset structure, columns, and data types.                     |
| 3    | Data Cleaning         | Identified and handled missing values, duplicates, and inconsistencies. |
| 4    | Data Preprocessing    | Prepared the dataset for further analysis.                               |
| 5    | Data Analysis         | Analyzed sales, customers, and product performance using Python.         |
| 6    | Data Visualization    | Created charts and graphs to understand patterns and trends.             |
| 7    | Dashboard Development | Developed an interactive dashboard using Power BI.                       |
| 8    | Insights Generation   | Identified meaningful business insights.                                |

---
## 🧹 Data Cleaning and Preprocessing
---
Data cleaning and preprocessing were performed using Python to improve data quality and prepare the dataset for analysis.

---
### Data Cleaning Activities
---
- Checked missing and null values.
- Identified duplicate records.
- Checked and corrected data types.
- Converted the Date column into the appropriate date format.
- Checked numerical columns for invalid values.
- Validated Quantity, Unit Price, and Total Sales.
- Examined inconsistent Delivery Status values.
- Reviewed customer ratings and review text.
- Examined missing review information according to delivery status and dataset limitations.

---
### Data Preprocessing Activities
---
- Prepared numerical and categorical columns for analysis.
- Checked relationships between Quantity, Unit Price, and Total Sales.
- Organized data for exploratory analysis.
- Prepared the cleaned dataset for Power BI visualization.

---
## 📊 Exploratory Data Analysis (EDA)
---
Exploratory Data Analysis (EDA) was performed to understand the dataset, discover patterns, identify trends, and examine relationships between different variables.

---
### EDA Analysis Areas
---
| S.No. | Analysis              | Description                                  | Purpose                                        |
|:-----:|:----------------------|:---------------------------------------------|:-----------------------------------------------|
| 1     | Sales Analysis        | Examined sales values and order performance. | Understand overall sales performance.          |
| 2     | Product Analysis      | Analyzed product names and categories.       | Identify popular products and categories.      |
| 3     | Customer Analysis     | Examined customer purchasing information.    | Understand customer behavior.                  |
| 4     | Payment Analysis      | Analyzed different payment methods.          | Identify payment preferences.                  |
| 5     | Delivery Analysis     | Examined delivery status.                    | Track delivered, returned, and pending orders. |
| 6     | Geographical Analysis | Analyzed state-wise sales distribution.      | Compare sales across Indian states.            |
| 7     | Review Analysis       | Examined ratings and customer feedback.      | Understand customer satisfaction.              |

---
## 📈 Key Performance Indicators (KPIs)
---
Key Performance Indicators (KPIs) are measurable values used to evaluate business performance and support decision-making.

---
### KPI Description and Purpose
---
| KPI                       | Description                                | Purpose                          |
|:--------------------------|:-------------------------------------------|:---------------------------------|
| Total Orders              | Total number of order records.             | Measures overall order volume.   |
| Total Sales               | Sales value of eligible completed orders.  | Measures sales performance.      |
| Total Delivered           | Number of successfully delivered orders.   | Tracks successful deliveries.    |
| Total Returned            | Number of returned orders.                 | Measures return activity.        |
| Total Pending             | Number of pending orders.                  | Tracks incomplete orders.        |
| Average Order Value (AOV) | Average value of eligible orders.          | Measures average order spending. |
| Total Quantity Sold       | Total quantity of eligible sold products.  | Measures product sales volume.   |
| Average Review Rating     | Average customer review rating.            | Measures customer satisfaction.  |

---
### KPI Calculation
---
| KPI                   | Calculation                                       |
|:----------------------|:--------------------------------------------------|
| Total Orders          | Count of Order_ID                                 |
| Total Sales           | Sum of eligible Total_Sales_INR                   |
| Total Delivered       | Count of orders where Delivery_Status = Delivered |
| Total Returned        | Count of orders where Delivery_Status = Returned  |
| Total Pending         | Count of orders where Delivery_Status = Pending   |
| Average Order Value   | Eligible Sales / Eligible Orders                  |
| Total Quantity Sold   | Sum of eligible Quantity                          |
| Average Review Rating | Average of valid Review_Rating values             |

**Note:** Returned orders are tracked separately from currently delivered orders. If historical delivery events are unavailable, a returned order should not automatically be added to the current Delivered count.

---
## 📋 Important Columns
---
The dataset contains important columns used for data analysis, preprocessing, and dashboard development.

| Column           | Description                                             |
|:-----------------|:--------------------------------------------------------|
| Order_ID         | Unique identification number associated with an order. |
| Date             | Date of the transaction.                                |
| Customer_ID      | Unique identification number of each customer.          |
| Product_Category | Category of the purchased product.                      |
| Product_Name     | Name of the purchased product.                          |
| Quantity         | Number of units ordered.                                |
| Unit_Price_INR   | Price of one product in Indian Rupees.                  |
| Total_Sales_INR  | Total transaction value in Indian Rupees.               |
| Payment_Method   | Payment method used by the customer.                    |
| Delivery_Status  | Current delivery status of the order.                   |
| Review_Rating    | Rating provided by the customer.                        |
| Review_Text      | Written customer feedback.                              |
| State            | Indian state associated with the transaction.           |
| Country          | Country associated with the transaction.                |

---
## 📊 Power BI Dashboard
---
An interactive Power BI dashboard was developed to visualize important sales metrics, customer behavior, product performance, and delivery information.

The dashboard helps users explore business performance through visual reports and interactive filters.

---
### Dashboard Analysis Includes
---
- Overall sales performance.
- Total order analysis.
- Product category performance.
- State-wise sales distribution.
- Payment method analysis.
- Delivery status analysis.
- Customer ratings and reviews.
- Product-wise sales performance.

---
  ### Dashboard KPIs
---
| KPI             | Dashboard Purpose                         |
|:----------------|:------------------------------------------|
| Total Orders    | Displays the total number of orders.      |
| Total Sales     | Displays eligible completed sales value.  |
| Total Delivered | Displays successfully delivered orders.   |
| Total Returned  | Displays returned orders.                 |
| Total Pending   | Displays pending orders.                  |

---
## 💡 Key Business Insights
---
The analysis focuses on identifying important business patterns and insights.

1. **Sales Performance:** Understand overall sales performance and order value.
2. **Product Performance:** Identify products and categories contributing to sales.
3. **Customer Behavior:** Understand customer purchasing patterns and preferences.
4. **Payment Preferences:** Identify commonly used payment methods.
5. **Delivery Performance:** Evaluate delivered, returned, and pending orders.
6. **Geographical Performance:** Compare sales across different Indian states.
7. **Customer Satisfaction:** Analyze customer ratings and feedback.

---
## 🚀 Business Recommendations
---
- Focus on high-performing product categories to improve sales.
- Improve inventory management based on customer purchasing patterns.
- Analyze product returns to identify possible quality and delivery issues.
- Improve delivery operations to reduce pending orders.
- Monitor customer payment preferences.
- Improve customer experience using customer feedback and review analysis.
- Use sales trends to support better business decisions.

---
  ## 📝 Conclusion
---
The Amazon Diwali India Sales Analysis (2025) project demonstrates the practical application of Python and Power BI in e-commerce data analysis.

Python was used for data cleaning, preprocessing, and exploratory data analysis, while Power BI was used to develop an interactive dashboard for visualizing important business metrics.

The project provides an understanding of customer purchasing behavior, product performance, sales trends, payment preferences, delivery status, and customer feedback.

Overall, this project demonstrates how data analytics and visualization can transform raw e-commerce data into meaningful business insights and support data-driven decision-making.
