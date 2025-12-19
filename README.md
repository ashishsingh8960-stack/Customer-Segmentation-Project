👥 Customer Segmentation using K-Means Clustering
📌 Project Overview

This project focuses on segmenting customers into distinct groups based on their annual income and spending behavior using K-Means clustering.
Customer segmentation helps businesses understand different customer types and design targeted marketing strategies.

🎯 Objectives

Analyze customer data

Identify distinct customer segments

Apply unsupervised learning (K-Means clustering)

Visualize and interpret customer groups

Derive actionable business insights

🧰 Tools & Technologies

Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning (K-Means, Scaling)

📂 Project Structure
customer-segmentation-project/
│
├── data/
│   └── customers.csv
│
├── notebook/
│   └── customer_segmentation.ipynb
│
├── README.md
└── requirements.txt

📑 Dataset Description

The dataset contains customer information with the following columns:

Column Name	Description
CustomerID	Unique customer identifier
Age	Customer age
Annual_Income	Annual income (in thousands)
Spending_Score	Spending behavior score (1–100)
🔍 Data Preprocessing

Checked data types and missing values

Selected Annual_Income and Spending_Score for clustering

Scaled features using StandardScaler to ensure fair distance calculation

📊 Exploratory Data Analysis (EDA)

Analyzed age distribution using histograms

Visualized income vs spending score using scatter plots

Observed natural groupings among customers

🤖 Machine Learning Model

Algorithm Used: K-Means Clustering

Type: Unsupervised Learning

Features Used:

Annual_Income

Spending_Score

📐 Elbow Method

Used the Elbow Method to determine the optimal number of clusters

Selected 3 clusters based on the elbow point in the WCSS curve

📈 Cluster Visualization

Customers were grouped and visualized using a scatter plot, with each cluster represented by a different color.

🧠 Business Insights

Identified high-income high-spending customers (premium segment)

Identified low-income low-spending customers (budget-conscious)

Identified moderate-income moderate-spending customers (potential growth segment)

📌 These insights can help businesses:

Design targeted marketing campaigns

Improve customer retention

Optimize product pricing strategies

🏁 Conclusion

This project demonstrates how unsupervised machine learning techniques like K-Means clustering can be used to segment customers effectively.
It enhanced my understanding of data preprocessing, clustering, visualization, and business interpretation.

🚀 How to Run the Project

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn


Open customer_segmentation.ipynb and run all cells

📌 Author

Ashish Singh

⭐ If you find this project useful, feel free to star the repository!
