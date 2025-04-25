🌸 Iris Dataset Clustering with KMeans and Hierarchical Clustering
This project demonstrates the application of unsupervised learning (clustering techniques) on the classic Iris dataset using KMeans and Hierarchical Clustering algorithms.

🎯 Objective
The objective of this project is to apply and compare clustering techniques to identify natural groupings in the Iris dataset without using the species (target) labels.

📊 Dataset
Source: sklearn.datasets.load_iris()
Features: 4 (sepal length, sepal width, petal length, petal width)
Samples: 150
Target: Removed for clustering (unsupervised learning)
🛠️ Preprocessing
Loaded the Iris dataset using sklearn.
Created a DataFrame with only feature columns.
Dropped the species (target) column since clustering is unsupervised.
No missing values or scaling required as data is already clean and normalized.
🤖 Clustering Algorithms
🔸 KMeans Clustering
How it works: Partitions data into K groups by minimizing the distance between data points and their assigned cluster center.
Why it's suitable: Iris has 3 distinct species, making it ideal for a clustering method like KMeans that expects a predefined number of clusters.
🔸 Hierarchical Clustering
How it works: Builds a tree (dendrogram) of clusters by iteratively merging the closest pairs of clusters.
Why it's suitable: Helps visualize natural groupings and doesn’t require specifying number of clusters upfront.
📈 Results & Visualizations
Visualized clusters using the first two features: sepal length vs sepal width.
Used Seaborn for scatter plots and SciPy for dendrograms.
Algorithm	Clusters Formed	Visualization
KMeans Clustering	3	✔️
Hierarchical Clustering	3	✔️
