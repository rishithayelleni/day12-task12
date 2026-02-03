KMeans Customer Segmentation

Objective
Perform customer segmentation using KMeans clustering to group customers based on income and spending behavior.

Tools Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Dataset
Mall Customer Segmentation Dataset from Kaggle  
Features used:

- Annual Income (k$)
- Spending Score (1-100)

Steps Performed

1. Loaded and explored the dataset
2. Selected relevant features
3. Applied StandardScaler
4. Used Elbow Method to find optimal K
5. Trained KMeans model
6. Visualized clusters
7. Saved segmented dataset

Output

- Elbow plot
- Cluster visualization
- Segmented dataset (`segmented_customers.csv`)

Conclusion
Customers were successfully grouped into distinct segments that can be used for targeted marketing and business strategy.

Interview Concepts Covered

- Clustering
- KMeans algorithm
- Feature scaling
- Inertia
- Elbow method
- Limitations of KMeans
