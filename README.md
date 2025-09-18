Mall Customer Segmentation Analysis 🛍 A data-driven approach to understanding customer behavior and creating segments using the K-Means clustering algorithm. This project analyzes customer data to uncover patterns and group customers into distinct segments, providing actionable insights for targeted marketing.

🎯 Project Overview The primary goal of this project is to identify distinct customer groups within a mall's clientele based on their annual income and spending habits. By understanding these segments, the mall can tailor marketing strategies, improve customer experience, and optimize resource allocation.

This analysis involves:

Data Cleaning: Ensuring the dataset is accurate and consistent.

Exploratory Data Analysis (EDA): Visualizing the data to uncover initial trends and relationships.

Customer Segmentation: Applying the K-Means algorithm to group customers into meaningful clusters.

Insight Generation: Interpreting the clusters to create actionable business recommendations.

💾 Dataset The analysis is based on the "Mall Customers" dataset, which contains the following information:

CustomerID: Unique identifier for each customer

Gender: Customer's gender (Male or Female)

Age: Customer's age in years

Annual Income (k$): Customer's annual income in thousands of dollars

Spending Score (1-100): A score assigned by the mall based on customer spending behavior (1 = low spending, 100 = high spending).

🛠 Methodology

Exploratory Data Analysis (EDA) Initial analysis was performed to understand the distribution of data and the relationships between different features like Age, Annual Income, and Spending Score.

Determining the Optimal Number of Clusters The Elbow Method was used to determine the optimal number of clusters (k) for the K-Means algorithm. The "elbow" point on the graph, where the rate of decrease in the Within-Cluster Sum of Squares (WCSS) slows down, suggests the most appropriate value for k. For this dataset, k=5 was identified as the optimal number.

<-- Replace this with the link to your Elbow Method plot image -->

K-Means Clustering With k=5, the K-Means algorithm was trained to segment customers based on their Annual Income and Spending Score.
<-- This is where your main cluster plot goes! Replace the link -->

💡 Key Insights & Customer Segments The analysis revealed 5 distinct customer segments, each with unique characteristics:

Cluster Segment Name Characteristics Recommended Marketing Strategy 1 Target Audience High Income, High Spending Score Premium memberships, exclusive offers, luxury brand promotions. 2 Careful Spenders High Income, Low Spending Score Introduce high-value products, investment-based rewards programs. 3 Average Customers Average Income, Average Spending Score General marketing, seasonal offers, loyalty programs. 4 Budget-Conscious Low Income, Low Spending Score Discount campaigns, bundle deals, promotions on essential items. 5 Young Spenders Low Income, High Spending Score Promote trendy and affordable products, engage via social media.

💻 Technologies Used Python 3.x

Pandas for data manipulation

NumPy for numerical operations

Matplotlib & Seaborn for data visualization

Scikit-learn for implementing the K-Means algorithm

🚀 How to Run Locally To reproduce this analysis on your local machine, follow these steps:

Clone the repository:

Bash

"""git clone https://github.com/your-username/your-repository-name.git cd your-repository-name Install the required packages:"""

Bash

"""pip install pandas numpy matplotlib seaborn scikit-learn Run the analysis: Open and run the Mall_Customers.ipynb Jupyter Notebook (or your script file) to see the full analysis."""
