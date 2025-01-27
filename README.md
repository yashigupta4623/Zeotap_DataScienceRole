# Data Science Internship - Assignment

## Overview
This project demonstrates exploratory data analysis (EDA), predictive modeling, and clustering on an eCommerce dataset as part of a Data Science internship assignment. The tasks include deriving insights from the data, building a lookalike model, and performing customer segmentation using clustering techniques.

---

## Tasks Breakdown

### Task 1: Exploratory Data Analysis (EDA)
- Analyze `Customers.csv`, `Products.csv`, and `Transactions.csv` datasets.
- Identify trends, patterns, and potential outliers.
- Derive actionable business insights.
- Visualize the findings using plots.

### Task 2: Lookalike Model
- **Objective**: Recommend 3 similar customers for a given customer based on their profile and transaction history.
- **Key Steps**:
  1. Merge datasets to create a unified view.
  2. Preprocess data by normalizing key features like `Price`, `Quantity`, and `TotalValue`.
  3. Build a `NearestNeighbors` model to compute customer similarity.
  4. Generate recommendations for the first 20 customers.
- **Output**: Save results in a `Yashi_Gupta_Lookalike.csv` file.

### Task 3: Customer Segmentation (Clustering)
- **Objective**: Group customers into segments based on their profile and transaction behavior.
- **Key Steps**:
  1. Aggregate customer-level data (e.g., total spending, transaction count).
  2. Normalize the features using standard scaling.
  3. Apply clustering algorithms like `KMeans`.
  4. Evaluate clustering performance using Davies-Bouldin Index.
  5. Visualize the clusters.
- **Output**: Save clustering results in `Yashi_Gupta_Clusters.csv`.

---

## File Structure
- `Customers.csv`: Contains customer demographic and signup details.
- `Products.csv`: Contains product details such as name, category, and price.
- `Transactions.csv`: Records transaction details including products purchased, quantity, and total value.
- `Yashi_Gupta_Lookalike.csv`: Outputs top 3 lookalike customers for the first 20 customers.
- `Yashi_Gupta_Clusters.csv`: Stores the customer segmentation results and their respective cluster assignments.

---

## Prerequisites
- Python 3.8+
- Required Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Install dependencies using:
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

---

## Evaluation Criteria
- **EDA**: Quality of insights and visualization.
- **Lookalike Model**: Accuracy of recommendations and logic.
- **Clustering**: Metrics like Davies-Bouldin Index and visualizations.

---

## Author
Yashi Gupta  
Email: yashig406@gmail.com

