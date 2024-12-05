Strategic Business Decision-Making in Banking: Analyzing Customer Churn Using Machine Learning Models
 - Michael Anggi .G.A
The banking industry has become increasingly competitive in recent years. Various products and services are continuously being developed to ensure customers feel comfortable and remain loyal to the bank's offerings. Massive marketing strategies and product development efforts are being implemented to align with market trends and the latest technological advancements. One of the major challenges in this context is the discontinuation of services by customers, who may switch to other banks offering more appealing services.
Background
There are numerous factors that influence customers' decisions to cease using a bank's products or services. These include the quality of service - both online and offline - as well as the level of trust, which can be affected by economic and market dynamics. The phenomenon of customers discontinuing their use of banking services is known as Customer Churn. Strategically and from a business perspective, this phenomenon can significantly impact the long-term relationship between a bank and its customers. With the increasing prevalence of social media, customer churn can also influence public perception of the bank, potentially eroding trust levels. For these reasons, understanding customer churn is critical. The goal is to identify the key factors that lead customers to discontinue the use of a bank's products and services.
Objectives
To identify the primary factors contributing to customer churn.
To understand the aspects that need improvement to reduce customer churn.

Data
The data used for this analysis is sourced from an open-source dataset available at https://mavenanalytics.io/. The dataset contains the following variables:
Customer ID
Age
Gender
Geography/Country
Credit Score
Tenure
Account Balance
Products Held
Credit Card Ownership
Estimated Salary
Customer Status

Methods
The methods employed for the customer churn analysis include descriptive statistics, inferential statistics, parametric statistics, and multivariate statistics, supported by machine learning models.
Methodology
Collect open-source data of a European bank from https://mavenanalytics.io/.
Perform descriptive and inferential statistical analysis on the available dataset.
Develop machine learning models and evaluate their performance.
Conduct parametric and multivariate statistical analyses using the evaluated machine learning models.
Predict the factors that significantly influence customer churn.

Data Information
The dataset used is preprocessed and consists of 3,278 rows and 13 columns. The available data types include int64, float64, and object.
Data Preprocessing
The preprocessing steps applied to the data include:
Converting data types from int64 to float64 for specific columns.
Handling missing values (NaN) in certain columns.
Managing duplicate records in the dataset.
Selecting active customers with a current balance greater than zero.

DATA ANALYSIS
Descriptive Statistic
This dataset provides critical insights for customer churn prediction cases, with an average credit score of 654.06, an average age of 39.84 years, an average balance of 119,229.00, and an annual income of 99,955.77. There is significant variation in income (Std: 57,237.88) and balance (Std: 30,344.13). Customers with credit scores between 590–720, aged 32–45 years, and balances and incomes in the interquartile range tend to be more stable and exhibit lower churn risk. However, extreme values, such as a minimum credit score of 350, a maximum age of 92 years, a maximum balance of 250,898.00, and a minimum income of 11.00, warrant special attention as these customers may have higher risk profiles. As shown in Table-1, a detailed analysis, such as clustering and pattern/matrix exploration, is essential to gain deeper insights into the data.

EXPLORATORY DATA ANALYSIS

MACHINE LEARNING MODEL

Building Model

Model Evaluation

PREDICTION

SENSITIVTY

CONCLUSION
1.Over the next 10 months, there will be a significant reduction in customers due to churn
2. The business strategy to reduce churn based on this analysis could include:
•Optimizing Products 1 and 2 and promoting them to customers, as well as expanding their reach in each country.
•Reevaluating Products 3 and 4 to identify potential issues related to relevance, which may be making them less appealing to customers.
•Enhancing the analysis of product usage reviews, particularly for products 3 and 4, to gain further insights into customer preferences and improve these products.
