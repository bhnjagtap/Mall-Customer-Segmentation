# Customer Segmentation Analysis

This project focuses on customer segmentation using a mall customer dataset. The goal is to group customers into distinct clusters based on their spending behavior and annual income, allowing for more targeted marketing strategies.

## Dataset

The dataset used for this project includes the following features:
- **Customer ID**: Unique identifier for each customer.
- **Gender**: The gender of the customer (Male/Female).
- **Annual Income**: The annual income of the customer in thousands of dollars.
- **Spending Score**: A score assigned by the mall based on customer behavior and spending habits (1-100).

## Project Overview

### Objective
The primary objective of this project is to segment customers into distinct clusters using K-means clustering, based on their annual income and spending score.

### Steps Involved
1. **Data Preprocessing**: 
   - Loaded the dataset.
   - Analyzed and cleaned the data for any inconsistencies or missing values.

2. **Exploratory Data Analysis**:
   - Visualized the distribution of features like annual income and spending score.
   - Examined relationships between different features.

3. **K-means Clustering**:
   - Applied the K-means clustering algorithm to the dataset.
   - Determined the optimal number of clusters using the Elbow Method.
   - Segmented customers into five distinct clusters based on their annual income and spending score.

4. **Cluster Analysis**:
   - Analyzed the characteristics of each cluster:
     - **Cluster 1**: Moderate spenders with moderate incomes.
     - **Cluster 2**: High-income, high-spending customers.
     - **Cluster 3**: Low-income, high-spending customers.
     - **Cluster 4**: Low-income, low-spending customers.
     - **Cluster 5**: High-income, low-spending customers.
   - Visualized the clusters to understand customer segments better.

### Results
- The segmentation provided insights into different customer groups:
  - **Cluster 2** (High-income, high-spenders) are key targets for premium products and services.
  - **Cluster 3** (Low-income, high-spenders) could benefit from loyalty programs or discounts.
  - **Cluster 5** (High-income, low-spenders) represents untapped potential and may require different marketing approaches.

## Technologies Used
- **Python**: For data manipulation and analysis.
- **Jupyter Notebook**: For interactive coding and visualization.
- **Pandas**: For data handling.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For implementing K-means clustering.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/bhnjagtap/Customer-Segmentation-Analysis.git
2.Navigate to the project directory:
      ```bash

   cd Customer-Segmentation-Analysis
3.Install the required dependencies:
      ```bash

   pip install -r requirements.txt
4.Open the Jupyter Notebook:
      ```bash

   jupyter notebook CustomerSegmentation.ipynb
