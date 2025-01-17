# Mall-Customer-Segmentation

# Customer Segmentation Report
1. Introduction
The aim of this report is to analyze customer data from a supermarket mall. The goal is to identify target customer segments that the marketing team can focus on, enabling them to design effective strategies. The dataset used consists of basic customer information derived from membership cards, including Customer ID, age, gender, annual income, and spending score.

# 2. Dataset Overview
+ **Number of Records**: 200
+ **Data Fields**:
+ **CustomerID**: Unique identifier for each customer (integer).
+ **Gender**: Gender of the customer (male/female).
+ **Age**: Age of the customer (integer).
+ **Annual Income (k$)**: Annual income in thousands of dollars (integer).
+ **Spending Score (1-100)**: Score assigned based on customer behavior and purchasing data (integer).
# 3. Data Exploration
## 3.1 Descriptive Statistics
The dataset consists of 200 entries and 5 columns without any missing values.
**Gender Distribution**: Approximately 56% female and 44% male.
## 3.2 Graphical Analysis
+ **Age Distribution:** Skewed to the right, indicating more younger customers, predominantly between 30 and 40 years old.
+ **Annual Income Distribution:** Roughly normal, with most customers earning between 40k and 90k
+ **Spending Score Distribution:** Uniformly spread between 1 to 100, with a slight peak around 50.
## 3.3 Correlations
+ **Age vs. Annual Income:** Negligible correlation for both genders.
+ **Age vs. Spending Score:** Weak negative correlation for both genders.
+ **Annual Income vs. Spending Score:** Weak negative correlation for both genders.
# 4. Customer Segmentation Analysis
## 4.1 K-Means Clustering
Using K-Means clustering with different values for K:

+ **K=5 Clusters:**

Low annual income & high spending score.
Medium annual income & medium spending score.
High annual income & low spending score.
High annual income & high spending score.
Low annual income & low spending score.

+ **K=6 Clusters:**

Younger clients with medium annual & spending scores.
High annual income & low spending score.
Younger clients with medium annual & spending scores.
High annual income & high spending score.
Low annual income & low spending score.
Low annual income & high spending score.
## 4.2 DBSCAN Clustering
DBSCAN identified 5 clusters plus a cluster for outliers:
+ **Cluster Sizes:** Sizes vary significantly, with some clusters containing only a few observations and 18 identified outliers.
## 4.3 Cluster Characteristics
Cluster analysis showed the diversity in customer behavior based on income and spending scores rather than age segmentation.
# 5. Conclusion
The analysis of the customer data has successfully identified distinct segments based on spending behaviors and income levels. This information can guide marketing strategies to better target specific customer groups.

# 6. Recommendations
+ The marketing team should tailor campaigns to address the needs and preferences of each identified cluster.
+ Continuous monitoring of customer behavior is essential for adapting marketing strategies to changing consumer patterns.
