# Customer Segmentation using K-Means

## Overview
This project performs customer segmentation using K-Means clustering on a real-world dataset.
The goal is to identify meaningful customer groups to support targeted marketing and business decisions.

## Dataset
The dataset contains customer demographics and professional attributes including age, gender,
profession, work experience, family size, and spending score.

## Approach
1. Data cleaning and missing value imputation
2. Encoding categorical features
3. Feature scaling using StandardScaler
4. Optimal cluster selection using Elbow Method
5. K-Means clustering (k = 4)
6. Cluster profiling and visualization
7. Validation on unseen test data

## Results & Insights
Customers were segmented into four distinct clusters representing early-career customers,
stable professionals, highly experienced individuals, and older conservative users.

## Visualizations
### Elbow Method
![Elbow](images/elbow_method.png)

### Customer Clusters
![Clusters](images/clusters_age_workexp.png)

## Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt

