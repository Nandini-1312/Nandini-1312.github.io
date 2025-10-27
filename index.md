<h2 id="Key Projects">Key Projects</h2>

---

- <a href="#section7" style="font-size: normal;" > Analysis of Patient Satisfaction in Healthcare: A Multiple Regression Approach Using SAS</a>
- <a href="#section6" style="font-size: normal;" > Loan Repayment Prediction Analysis</a>
- <a href="#section1" style="font-size: normal;" > Personalized Movie Recommendation System using Collaborative Filtering</a>
- <a href="#section2" style="font-size: normal;" > California Housing Data Association Rules Analysis</a>
- <a href="#section3" style="font-size: normal;" > Grocery Data Analysis and Association Rules</a>
- <a href="#section4" style="font-size: normal;" > Market Basket Analysis for RM Customer Purchase Behavior</a>
- <a href="#section5" style="font-size: normal;" >Bank of Buffalo DBMS Project</a>


---

<h4 id="section7">Analysis of Patient Satisfaction in Healthcare: A Multiple Regression Approach Using SAS</h4>

This project uses SAS to analyze patient satisfaction in a healthcare setting, focusing on factors such as age, length of stay, nurse-to-patient ratio, and medical staff visits. Using a multiple regression model, the goal was to identify significant predictors of patient satisfaction and provide actionable recommendations for healthcare administrators. The model explains 97.81% of the variation in satisfaction scores (R-squared = 0.9781) and includes key predictors like age, length of stay, the number of nurses, and the average daily staff visits, all showing significant contributions with p-values less than 0.05.

Key findings include that the number of medical staff visits per day has the strongest positive correlation with patient satisfaction, explaining about 40% of the variation in satisfaction scores. Increasing staff visits can significantly improve patient satisfaction. The number of nurses also contributes to satisfaction, albeit with a weaker impact. The analysis also suggests that while age has a negative effect on satisfaction, providing personalized care can help address the specific needs of older patients. Length of stay, however, has minimal impact on satisfaction scores, implying that quality of care and timely treatment are more important. SAS coding, including correlation analysis, regression modeling, and hypothesis testing, was used throughout to perform these analyses and generate actionable insights.

![image](https://github.com/user-attachments/assets/9e37175d-a361-4ec2-9678-5cf9ecc2a359)![image](https://github.com/user-attachments/assets/d96297d2-43d1-4f28-9ea0-964f069377da)


[Go to GitHub Repository](https://github.com/Nandini-1312/Analysis-of-Patient-Satisfaction-in-Healthcare-A-Multiple-Regression-Approach)

---

<h4 id="section6">Loan Repayment Prediction Analysis</h4>

This project aimed to develop a predictive model to assess the likelihood of loan repayment success or default risk using a supervised machine learning approach. The dataset of 37,408 records underwent comprehensive preprocessing, including handling missing values with mode-based imputation, median grouping, and proportional sampling for categorical distributions. Principal Component Analysis (PCA) reduced dimensionality while retaining 87% of the variance, ensuring computational efficiency and mitigating overfitting risks.


To address class imbalance, Synthetic Minority Oversampling Technique (SMOTE) was applied, generating synthetic samples for the minority class and balancing the dataset. Logistic regression was implemented post-SMOTE, achieving a balanced accuracy of 72.64% and an AUC of 0.78. The ROC curve demonstrated effective differentiation between repayment outcomes, minimizing false positives for loans at default risk.


This project showcased how robust preprocessing and balanced modeling can enhance prediction reliability. Insights were further explored through Power BI visualizations, with key patterns and trends available in the GitHub repository for reference.

![image](https://github.com/user-attachments/assets/ffaa9a9c-b5f5-4257-95e9-3e80b02867d4)
![image](https://github.com/user-attachments/assets/f42df8ea-ddda-457a-bab6-957149f625ac)



[Go to GitHub Repository](https://github.com/Nandini-1312/Loan-Quality-Prediction-A-Data-Driven-Approach-for-Financial-Risk-Management)

---
<h4 id="section1">Personalized Movie Recommendation System using Collaborative Filtering</h4>

This project aims to develop a personalized movie recommendation system by leveraging collaborative filtering techniques to enhance user experience. Using the MovieLens dataset, which includes approximately 100,000 ratings from 943 users on 1,664 movies, the system employs R's `recommenderlab` package to build both user-based and item-based recommendation models. Initial data exploration involves preprocessing and normalizing the ratings to prepare the dataset for modeling. The user-based collaborative filtering (UBCF) model recommends movies based on similar user preferences, while the item-based collaborative filtering (IBCF) model suggests movies similar to those previously rated by the user.

The project evaluates the performance of these models based on relevance, novelty, serendipity, and diversity of the recommendations. The user-based model demonstrated varied success in relevance, providing novel suggestions but showing limited overlap with user preferences. It also offered some serendipitous and diverse recommendations, though not across a broad temporal range. The item-based model performed better in providing consistent recommendations based on item similarity and was effective in suggesting relevant movies. Overall, the project successfully showcases the potential of collaborative filtering to deliver personalized recommendations, with room for improvement in recommendation breadth and alignment with user interests.

[Go to GitHub Repository](https://github.com/Nandini-1312/Personalized-Movie-Recommendation-System-using-Collaborative-Filtering)

---

<h4 id="section2">California Housing Data Association Rules Analysis**</h4>

This project applies association rule mining to the California Housing Data from Kaggle to uncover patterns in housing attributes. The primary goal is to analyze and understand associations between different features such as total rooms, median income, and housing values. By implementing the apriori algorithm, the project aims to identify significant rules that offer insights into housing characteristics and guide practical recommendations for potential buyers.

The analysis highlighted key insights, including that high total rooms and average population correlate with certain household configurations. It also identified that higher median incomes are associated with lower population areas. For those seeking homes near the ocean, the most favorable characteristics include an average median age, fewer bedrooms, and higher house values. In low-population areas, key features include high house values, fewer bedrooms, small household sizes, and moderate to high incomes. The project effectively demonstrated the ability to derive actionable insights from housing data, offering valuable recommendations for both potential buyers and urban planners.


[Go to GitHub Repository](https://github.com/Nandini-1312/California-Housing-Data-Association-Rules-Analysis)


---

<h4 id="section3">Grocery Data Analysis and Association Rules</h4>

This project focuses on analyzing transactional data from a grocery store to uncover item associations and purchase patterns. The primary goal is to identify patterns that can inform sales strategies and optimize product placement, with a particular emphasis on enhancing the visibility and sales of specific product categories.

Through data visualization and association rule mining, the project reveals frequent item purchases and identifies strong relationships between products. The analysis highlights key insights such as high-confidence associations and significant patterns that can drive marketing and merchandising decisions. By implementing these findings, the store can develop targeted promotions, improve product bundling strategies, and enhance inventory management, ultimately leading to increased sales and better customer satisfaction.

[Go to GitHub Repository](https://github.com/Nandini-1312/Grocery-Data-Analysis-and-Association-Rules)

---

<h4 id="section4">Market Basket Analysis for RM Customer Purchase Behavior</h4>

This project aims to analyze customer purchase behavior by examining transactional data from RM's loyalty card system. The focus is on uncovering patterns of product associations to inform pricing strategies, display optimizations, and promotional effectiveness. By leveraging market basket analysis, the goal is to provide actionable insights that can enhance RM's sales strategies and improve customer satisfaction.

The project involves preprocessing the raw transactional data to create a binary transaction matrix, where each matrix entry indicates whether a product was purchased. This matrix is used for data analysis using the Apriori algorithm to identify frequent itemsets and association rules. The analysis highlights significant product associations, which are ranked by lift to identify the strongest relationships. Insights from this analysis suggest strategic adjustments to product placements and promotional offers based on observed purchasing patterns. Recommendations include optimizing store layouts and implementing targeted promotions to align with customer buying behaviors, ultimately aiming to boost sales and enhance customer engagement.

[Go to GitHub Repository](https://github.com/Nandini-1312/Market-Basket-Analysis)

---

<h4 id="section5">Bank of Buffalo DBMS Project</h4>

This DBMS project aims to modernize and streamline the management of banking information, enhancing customer interactions and operational efficiency. The system captures comprehensive data related to the bank’s branches, employees, customers, accounts, transactions, loans, and insurance services. The primary goal is to create an intuitive and robust database where information retrieval is simplified through structured relationships and normalized tables, ensuring easy access and management for both bank staff and customers. This customer-centric approach facilitates seamless transactions and account management, improving overall service delivery.

The project involves detailed steps including data analysis, creating an Entity-Relationship (ER) diagram, and designing and normalizing database tables. The ER diagram outlines the relationships between entities such as branches, employees, and accounts, ensuring accurate data linkage and integrity. The database implementation encompasses designing tables with proper foreign key constraints to represent one-to-many relationships, such as between branches and employees or accounts and transactions. This systematic approach not only supports efficient data handling and retrieval but also enhances the bank’s ability to offer personalized services and streamlined operations.

End-to-end SQL scripts were developed from scratch, covering Data Definition Language (DDL), Data Manipulation Language (DML), and other database operations. These scripts facilitate the creation, updating, and management of the database, ensuring the integrity and accessibility of data. Queries derived from this database can generate valuable insights, such as customer transaction patterns, loan and insurance distribution, and employee performance metrics, supporting data-driven decision-making and improving overall banking operations.

[Go to GitHub Repository](https://github.com/Nandini-1312/Bank-of-Buffalo-DBMS-Project)

<h2 id="Data Stories with Power BI">Data Stories with Power BI</h2>

---

- <a href="#Vizsection1" style="font-size: normal;" > Analyzing Crime Trends in Los Angeles: A Data-Driven Perspective</a>
- <a href="#Vizsection2" style="font-size: normal;" > US Border Crossing Entry Data Analysis </a>

---


<h4 id="Vizsection1">Analyzing Crime Trends in Los Angeles: A Data-Driven Perspective</h4>

This Power BI dashboard provides a comprehensive analysis of crime trends in Los Angeles, focusing on key factors such as age groups, geographic distribution, crime types, and influencing factors. It highlights crime concentration across different age demographics, showing that elderly individuals experience the highest number of incidents, followed by children and adults. The dashboard also examines crime distribution by area, with Central LA, 77th Street, and Pacific divisions reporting the highest crime rates. Additionally, it tracks crime trends over the years, showing a steady rise from 2020 to 2024, followed by a sharp decline in 2025, which may be attributed to policy changes or law enforcement actions.

Key insights include the high association of crimes with streets (301K incidents) and residential areas, emphasizing the need for targeted public safety measures. The analysis of arrest patterns reveals that crimes like stalking and homicide significantly increase the likelihood of adult arrests. Furthermore, location-based mapping shows crime hotspots across Los Angeles, with varying gender-based victimization trends. These insights can help authorities and policymakers enhance crime prevention strategies and allocate resources more effectively to ensure public safety.

![LA Crime Dataset-1](https://github.com/user-attachments/assets/200799d9-f9fd-48ad-bbbf-6a7efadb8881)


[Go to GitHub Repository](https://github.com/Nandini-1312/Data-Stories-with-Power-B-Analyzing-Crime-Trends-in-Los-Angeles)

---


<h4 id="Vizsection2">US Border Crossing Entry Data Analysis</h4>

This visualization provides an interactive analysis of US border crossings from 1995 to 2023, highlighting trends, geographic distribution, and key state-wise entry points. The border crossing trends chart shows historical variations, while the geospatial analysis pinpoints high-traffic locations across the US-Canada and US-Mexico borders. A Sankey diagram further breaks down state-wise crossings, with Texas leading at 4.14 billion entries, followed by key ports like El Paso (1.27B) and Hidalgo (637M).

With a total of 11 billion recorded crossings, this dashboard offers valuable insights for policymakers and analysts. Users can filter data by year, state, and border type to explore cross-border movement patterns, enabling informed decision-making on immigration, trade, and security policies.

![US Border Crossing Entry Data-1](https://github.com/user-attachments/assets/92f86c7d-16b4-44a9-901e-eb2dd71f8b2a)

[Go to GitHub Repository](https://github.com/Nandini-1312/Data-Stories-with-Power-B-US-Border-Crossing-Entry-Data-Analysis/tree/main)



---

<h2 id="Education">Education</h2>

**Master of Professional Studies – Data Science and Applications**

University at Buffalo, The State University of New York, Buffalo, NY

•	Completed a rigorous, professional-level program providing advanced, hands-on experience in applying data science, analytics, and machine learning to solve real-world business and operational problems.

•	Relevant coursework: Programming and Databases, DBMS, Numerical Analysis, Probability and Data Analysis, Statistical Data Mining, Machine Learning, Cybersecurity Privacy and Ethics.

**Bachelor of Computer Applications**

Madras Christian College, Chennai, TN, India

Graduated On: June 2019


<h2 id="About Me">About Me</h2>

Hello! I’m Nandini Ethirajulu, a data professional with over 6 years of experience in analytics, business intelligence, and data engineering. At Deloitte USI Consulting, I delivered scalable data solutions for major clients like the State of Tennessee and State of Connecticut, developing optimized ETL pipelines, automated data processes, and insightful dashboards to support strategic decision-making.

I hold a Master of Science in Data Science and Applications from the University at Buffalo, which deepened my expertise in machine learning, statistical analysis, and cloud-based analytics. This advanced training, combined with my technical skills in Python, R, SQL, Tableau, and Power BI, enables me to translate complex data into clear, actionable insights that drive business impact.

<h2 id="Work Experience">Work Experience</h2>

****Community Dreams Foundation**

Role: Data Engineer

May 2025 - Present**
•	Supported the implementation of Azure-based data pipelines and models using ADF, Databricks, and Azure SQL, integrating datasets from multiple sources to improve data accessibility and analytics capability.

•	Assisted in optimizing ETL workflows and building data structures to support AI/ML initiatives and performance monitoring, ensuring reliable, well-documented, and scalable data processes

****Local Grown Salads**

Role: Data Engineer

February 2025 – April 2025**
•	Automated data extraction, transformation, and integration between Odoo ERP (MRP modules) and PostgreSQL using Python, streamlining the flow of production, customer, and quality data across farming subsystems for enhanced business visibility.

•	Designed data models and analytics-ready datasets to support performance tracking, production scheduling, and traceability dashboards, enabling proactive decision-making and operational compliance.

•	Partnered with cross-functional teams to translate process data into actionable business insights, improving efficiency, ensuring regulatory adherence, and supporting continuous process optimization through data validation and KPI monitoring.



**Deloitte USI Consulting**

**Role: Analyst 

June 2021 - July 2023
**
•	Designed and optimized 300+ SSIS ETL workflows to extract, transform, and load (ETL) high-volume data into a data warehouse, supporting business intelligence reporting for Tennessee State's Benefits System.

•	Developed a master ETL orchestration framework, enabling automated execution, logging, and error handling, reducing ETL downtime by 90% and improving data pipeline efficiency.

•	Wrote complex SQL queries, stored procedures, and views in Oracle PL/SQL, leveraging CTEs, partitioning, and indexing to process 200+ business-critical reports with enhanced performance.

•	Applied data modeling best practices to design fact and dimension tables, supporting Tableau dashboards that provided real-time insights into transactional, eligibility, and benefit issuance data.

•	Created federal compliance reports in fixed-length CSV format, integrating business logic to provide structured data submissions to the Administration for Children and Families (ACF).

•	Enhanced ETL performance by 43% through data cleansing, redundancy elimination, and transformation, ensuring accurate and efficient integration across systems.

•	Collaborated with business stakeholders, analysts, and developers to define BI reporting requirements, ensuring data accuracy, dashboard usability, and KPI tracking. Developed Tableau dashboards for executive-level reporting, providing actionable insights into Eligibility Determination, Benefits Issuance, and Claims data, increasing reporting efficiency by 29%.


****Deloitte USI Consulting**

Role: Associate Analyst

August 2019 - May 2021**

•	Extracted, transformed, and standardized multi-source datasets for a Legacy System Conversion initiative for the State of Connecticut, ensuring 98% data accuracy and alignment with business intelligence requirements. Improved ETL efficiency by refining SSIS workflows and SQL-based transformations, reducing processing time by 50% and ensuring near-zero data loss.

•	Migrated cleansed and structured data into target systems using Salesforce’s Bulk API, enhancing data accessibility, downstream analytics, and compliance reporting. Led UAT, system validation, and data reconciliation, ensuring migrated data maintained its accuracy, consistency, and traceability across business operations and BI reports.


<h2 id="Skills">Skills</h2>

<h3>Programming Languages:</h3>

Python
R
Visual Basic
Oracle PL/SQL
Java

<h3>Data Analysis and Modeling:</h3>

Machine Learning
Statistical Data Mining

<h3>Data Management and Analytics:</h3>

Oracle
MS SQL Server
SSIS ETL
Data Warehousing

<h3>Web Development:</h3>

HTML
CSS
JavaScript

<h3>Tools:</h3>

Visual Studio
Microsoft Office Suite

<h3>Visualization:</h3>

Tableau
Power BI

<h2 id="Awards">Awards</h2>

•	Outstanding Performance Award Deloitte, 2022 

•	Applause Award 	Deloitte, 2022

•	Spot Award 	Deloitte, 2021

•	Undergraduate Special Prize I	2017 and 2019
