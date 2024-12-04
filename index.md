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



<h2 id="Education">Education</h2>

**Master of Professional Studies – Data Science and Applications**

University at Buffalo, The State University of New York, Buffalo, NY

Relevant coursework: Programming and Databases, DBMS, Numerical Analysis, Probability and Data Analysis, Statistical Data Mining, Machine Learning, Cybersecurity Privacy and Ethics

Expected Graduation: January 2025

**Bachelor of Computer Applications**

Madras Christian College, Chennai, TN, India

Graduated On: June 2019


<h2 id="About Me">About Me</h2>

Hello! I’m Nandini Ethirajulu, a dedicated data scientist currently pursuing a Master’s in Data Sciences and Applications at the University at Buffalo. With a robust background in computer applications and data science, I have cultivated a diverse skill set encompassing programming, data analysis, machine learning, and data management.

My professional journey commenced at Deloitte USI Consulting, where I served as an Analyst and Associate Analyst. During my tenure, I spearheaded the development of advanced ETL packages, optimized data integration processes, and crafted sophisticated data visualizations using Tableau. My efforts have consistently aimed at enhancing data integrity, minimizing process downtime, and improving user experience.

In addition to my professional experience, I have undertaken various academic projects that have sharpened my technical skills. From conducting market basket analysis to designing comprehensive DBMS systems, I have applied my expertise to solve complex data problems and deliver actionable insights. My coursework has spanned a broad spectrum of topics, including machine learning, statistical data mining, cybersecurity, and ethics, providing me with a solid foundation in both theory and practice.

I am continually eager to embrace new challenges and contribute to innovative projects. My objective is to leverage my skills and experience to drive data-driven decision-making and create a meaningful impact within any organization I join. Feel free to connect with me on [LinkedIn](www.linkedin.com/in/nandini-ethirajulu) or explore my projects on [GitHub](https://github.com/Nandini-1312).

<h2 id="Work Experience">Work Experience</h2>

**Deloitte USI Consulting**

Role: Analyst 

June 2021 - July 2023

•	Spearheaded the development of 200+ advanced SSIS ETL packages for a US State Government project, ensuring seamless ETL of data from the source Application Database to an intermediate Staging Layer Database with a focus on Data Integrity.

•	Architected and optimized ETL packages to facilitate both full data loads during initial runs and highly efficient incremental data loads during subsequent daily runs, resulting in remarkable improvement in ETL performance and eliminating data redundancy.

•	Crafted intricate Oracle PL/SQL stored procedures to extract and transform data for over 200+ customized client reports and dashboards. Developed reusable ETL packages for executing these procedural scripts at diverse reporting frequencies (Daily, Monthly, Annual), and leveraging Tableau for sophisticated data visualization, increasing user experience by 30%.

•	Engineered a robust restart and error tracking mechanism across the ETL process, ensuring swift identification and resolution of data discrepancies. This mechanism facilitated the targeted rerunning of errored ETL packages, thereby achieving a 90% reduction in ETL process downtime. Additionally, automated archival processes were implemented to boost operational efficiency and ensure compliance, preserving data integrity and accessibility at all times.

**Deloitte USI Consulting**

Role: Associate Analyst

August 2019 - May 2021

•	Led the extraction and preprocessing of data from diverse sources including application systems, files, and databases for a critical Legacy System Conversion initiative. Standardized data format, structure, and quality, achieving data accuracy and ensuring compliance with industry standards.

•	Implemented SSIS ETL jobs and procedural scripts to efficiently stage, integrate, and transform data, resulting in a 50% reduction in data processing time and minimized information loss to less than 0.2%. Completed complex data transformations ahead of schedule to meet project deadlines.

•	Utilized Salesforce’s bulk data loading utility to seamlessly migrate transformed data into the target database, improving operational efficiency and maintaining high data integrity and accessibility throughout the conversion process.

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
