Customer Segmentation using K-means Clustering

This project applies K-means clustering to segment customers of a retail store based on their purchase history, specifically using annual income and spending score data. The goal is to group customers into distinct clusters for targeted marketing strategies.

Workflow:

Data Loading: The customer dataset (Mall_Customers.csv) is loaded.

Exploratory Data Analysis (EDA): Visualized the distribution of gender, age, annual income, and spending score.
Checked for missing values and basic statistics.

Feature Selection: Selected features Annual Income (k$) and Spending Score (1-100) for clustering.

Data Preprocessing: Features are scaled using StandardScaler for normalization.

Elbow Method: The optimal number of clusters is determined using the Elbow Method, plotting the within-cluster sum of squares (WCSS) for different cluster counts.

Clustering: K-means clustering is performed with 5 clusters.

Visualization: Clusters are visualized using a scatter plot of Annual Income vs Spending Score, colored by cluster labels.

Key Libraries:

Pandas

Scikit-learn

Matplotlib

Seaborn

Results:

Customers are grouped into 5 distinct clusters based on their spending habits and income.

Visualization of customer segments can aid in targeting marketing efforts.

Visualizations:

Gender, age, income, and spending score distributions.

Elbow Method plot to determine optimal cluster count.

Scatter plot of customer clusters.
