# 📊 Customer Behavior Prediction using Machine Learning
# 📌 Project Overview
* This project focuses on analyzing customer transaction data and building a supervised machine learning model to predict customer behavior.
*  The goal is to identify whether a customer is likely to make a repeat purchase, helping businesses improve customer retention strategies and decision-making.
# 🎯 Objective
1. Predict  sales per order
2. Understand key drivers of customer loyalty
3. Provide insights for business decision-making
4. Prepare data outputs for visualization in Power BI
# 🧠 Machine Learning Approach
# This project uses supervised learning, where the model is trained on labeled data.
 - Model Used:
 - Random Forest Classifier
 - Linear Regression
 - KMeans Clustering
# 📊 Features Used
- Number of Orders
- Total Spend per Customer
* These features were derived from transactional data using aggregation techniques.
# ⚙️ Project Workflow
* Feature Engineering (Customer-level aggregation)
* Creation of Target Variable (Repeat Customer)
* Train/Test Split
* Model Training (Random Forest)
* Prediction and Evaluation
* classification/ Segmentation.
* Export of Results for Visualization
# 📈 Tools & Technologies
* Python
* Pandas
* Scikit-learn
* NumPy
* Power BI (for visualization)
# 📉 Model Output
The model predicts:
* Whether a customer will make a repeat purchase
* Customer behavior classification for business insights
# 📊 Business Value
* Improves customer retention strategies
* Identifies loyal vs at-risk customers
* Supports targeted marketing campaigns
* Enhances revenue forecasting
# 📁 Output Files
* customer_behavior_prediction.csv → Final dataset with predictions
# 🚀 Future Improvements
Add churn prediction model
Include probability scoring (likelihood of repeat purchase)
Expand features using RFM analysis
Deploy model as API or dashboard integration



# POWERBI CUSTOMER BEHAVIOIRAL SEGMENTAION AND BUSINESS INSIGHTS

# Key Insights
# Project Overview
This dashboard presents the results of a behavioral customer segmentation analysis, providing insights into customer distribution, revenue contribution, and purchasing behavior across three customer segments: High Value, Medium Value, and Low Value. The objective is to understand how different customer groups contribute to business performance and support data-driven decision-making.

# Key Findings
Customer Distribution: The Medium Value segment represents the largest customer group with 630 customers (52.99%), followed by the Low Value segment with 548 customers (46.09%). The High Value segment consists of 11 customers (0.93%), making it the smallest customer group.
Revenue Contribution: The Low Value segment generated the highest revenue (approximately 0.92M), while the Medium Value segment contributed approximately 0.33M. The High Value segment generated the lowest overall revenue due to its relatively small customer base.
Overall Purchase Activity: The Medium Value segment recorded the highest total purchase frequency (630), indicating that this group contributes the greatest overall purchasing activity. The Low Value segment followed closely with a frequency of 543, while the High Value segment recorded 22 total purchases.
Average Customer Engagement: Although the High Value segment contains the fewest customers, it achieved the highest average purchase frequency (2 purchases per customer), compared to an average frequency of 1 for both the Medium and Low Value segments. This suggests that High Value customers are more engaged on an individual basis.

# Business Insights
The analysis reveals distinct purchasing behaviors across customer segments:
The Medium Value segment forms the core customer base, driving consistent purchasing activity through its large customer population.
The Low Value segment contributes the largest share of total revenue, demonstrating that customer volume can significantly influence business performance.
The High Value segment, while small in size, exhibits the highest average purchasing frequency, indicating strong customer engagement and potential for targeted retention strategies.

# Conclusion
This dashboard demonstrates how customer segmentation can uncover meaningful behavioral patterns beyond overall sales figures. By comparing customer distribution, revenue contribution, and purchasing frequency, businesses can identify high-potential customer groups, optimize marketing strategies, and develop more effective customer retention initiatives.

