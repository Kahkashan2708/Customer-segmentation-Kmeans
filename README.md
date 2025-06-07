#  Customer Segmentation using K-Means Clustering

This project applies machine learning techniques to segment customers based on their **annual income** and **spending score** using the **K-Means clustering algorithm**. This analysis helps in understanding customer behavior and grouping similar customers for targeted marketing.

---

##  Dataset

The dataset used is **Mall_Customers.csv**, which includes the following columns:

- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

##  Project Workflow

1. **Import Libraries**  
   Utilized NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.

2. **Load and Explore the Dataset**  
   - Checked basic statistics and null values.
   - Visualized distributions using histograms and scatter plots.

3. **Feature Selection**  
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` for clustering.

4. **Determine Optimal Clusters**  
   - Used the **Elbow Method** to choose the optimal number of clusters using WCSS (Within-Cluster Sum of Squares).

5. **Model Training**  
   - Applied K-Means clustering to group customers.

6. **Visualization**  
   - Plotted the clusters 
   - Labeled cluster centroids for interpretability.
   -  ![Customer-segmentation-kmeans](clusters.png)


---

##  Key Concepts

- **K-Means Clustering**: Unsupervised ML algorithm used to group data into `k` distinct clusters.
- **Elbow Method**: Technique to determine the ideal number of clusters by plotting WCSS against the number of clusters.

---

##  How to Run

```bash
# Step 1: Clone the repository or download the notebook
# Step 2: Ensure Python and required libraries are installed
pip install numpy pandas matplotlib seaborn scikit-learn

# Step 3: Run the Jupyter Notebook
jupyter notebook Untitled-1.ipynb
```

---

## Sample Output

- **Elbow Curve** to determine optimal clusters
- **Clustered Scatter Plot** for visual interpretation of customer segments


---

## Conclusion

This project demonstrates how customer segmentation can be achieved using clustering algorithms. Businesses can leverage such insights to personalize services and optimize marketing strategies.

---

