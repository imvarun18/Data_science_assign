# Task 1: Exploratory Data Analysis (EDA) on Customer Data
This project focuses on Exploratory Data Analysis (EDA) of customer transactional data, uncovering key patterns and insights to inform business strategies. The analysis includes detailed visualizations to explore spending trends, transaction distributions, and customer behavior.

## Key Features:
Data Cleaning and Preparation: Handles missing values and ensures data quality for analysis.
Spending Patterns: Visualizations to identify high, medium, and low spenders.
Transaction Insights: Analysis of transaction frequency and its relationship with total spending.
Segmentation Insights: Provides a foundation for grouping customers by behavior.

## Visualizations:
Spending distributions
Correlations between variables (e.g., transaction counts vs. spending)
Box plots and scatter plots to highlight customer variability

## Tech Stack:
Python: Pandas, NumPy, Matplotlib, Seaborn
Jupyter Notebook: Interactive notebook for clear and structured analysis


# Task 2: Building a Lookalike Model for Customer Recommendation
This project implements a Lookalike Model to recommend similar customers based on user profiles and transaction histories. By leveraging customer and product data, the model identifies the top three lookalike customers for each user and provides similarity scores for these recommendations.

## Objective:
To enhance customer targeting and personalization by identifying users with similar behavior or profiles to a given customer.

## Key Features:
Similarity-Based Recommendations: Recommends the top 3 lookalike customers for each input user, based on transaction history and profile similarity.
Similarity Scoring: Assigns a score to each recommended customer to quantify similarity.
Integration of Data: Combines customer and product information for a comprehensive analysis.

## Results:
Generated a Lookalike.csv file mapping customers to their top 3 lookalikes with similarity scores.

## Tech Stack:
Python: Pandas, NumPy, Scikit-learn
Recommendation Framework: Cosine similarity for scoring and nearest neighbor methods
Visualization: Matplotlib and Seaborn for data insights
Output Storage: CSV file for final mappings

# Task 3: K-Means Clustering for Customer Segmentation
This project uses K-Means Clustering to divide customers into groups based on transactional data, enabling personalized marketing and better customer understanding. The analysis builds on insights from Task 1 and evaluates clustering quality using standard metrics.

## Key Features:
Clustering Implementation: Groups customers into clusters using K-Means.
Cluster Evaluation: Uses the Davies-Bouldin Index (DBI) and other metrics to measure performance.
Cluster Insights: Detailed analysis of cluster characteristics, including spending habits and transaction frequency.

## Results:
Number of Clusters: 5
Best DBI Value: 0.602
Cluster Distribution:
Cluster 0: 12 high-value customers
Cluster 1: 71 medium-spending customers
Cluster 2: 21 low-spending customers
Cluster 3: 36 average-spending customers
Cluster 4: 59 moderate-spending customers

## Visualizations:
Spending distribution per cluster
Scatter plots to show cluster boundaries
Spending vs. transaction count trends

## Tech Stack:
Python: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Jupyter Notebook: Contains clustering code with step-by-step explanations
