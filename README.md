# 🎬 Movies Recommendation using K-Means Clustering

A Machine Learning project that groups users based on their movie genre preferences using the **K-Means Clustering** algorithm. The system identifies users with similar interests and recommends users from the same cluster, demonstrating how unsupervised learning can be applied to recommendation systems.

---

## 📌 Project Overview

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to analyze users' preferences for different movie genres.

The dataset contains ratings for the following genres:

- Action
- Comedy
- Drama
- Horror
- Romance
- Sci-Fi

After clustering users with similar preferences, the program allows the user to enter a **User ID** and recommends other users belonging to the same cluster.

---

## 🚀 Features

- Data preprocessing using StandardScaler
- Optimal cluster selection using the Elbow Method
- User segmentation using K-Means Clustering
- Cluster center analysis
- PCA visualization of clusters
- Cluster visualization with centroids
- Similar user recommendation
- Easy-to-understand code structure

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- K-Means Clustering
- StandardScaler
- Principal Component Analysis (PCA)

---

## 📂 Project Structure

```
Movies-Recommendation-KMeans/
│
├── Movies-Recommendation-kmean.py
├── movies.csv
├── requirements.txt
├── .gitignore
├── README.md
│
└── Images/
    ├── elbow_method.png
    ├── movie_clusters.png
    └── movie_clusters_centroids.png
```

---

## ⚙️ How It Works

### 1. Load Dataset

The program loads the movie preference dataset using Pandas.

### 2. Select Features

The following movie genres are selected:

- Action
- Comedy
- Drama
- Horror
- Romance
- SciFi

### 3. Standardize Data

The selected features are standardized using **StandardScaler** to ensure equal importance for every feature.

### 4. Find Optimal Number of Clusters

The **Elbow Method** calculates the Within Cluster Sum of Squares (WCSS) for different values of K.

### 5. Train K-Means Model

The dataset is clustered into groups of users with similar movie preferences.

### 6. Display Cluster Centers

The average movie preferences for each cluster are displayed.

### 7. Visualize Clusters

Principal Component Analysis (PCA) reduces the data into two dimensions for visualization.

Two graphs are generated:

- Movie User Clusters
- Movie User Clusters with Centroids

### 8. Recommend Similar Users

The user enters a User ID.

The program:

- Finds the user's cluster.
- Retrieves all users belonging to the same cluster.
- Displays similar users as recommendations.

---

## 📊 Machine Learning Concepts Used

- Unsupervised Learning
- K-Means Clustering
- Feature Scaling
- Standardization
- Elbow Method
- PCA
- Data Visualization

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Movies-Recommendation-KMeans.git
```

Move into the project folder

```bash
cd Movies-Recommendation-KMeans
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the project

```bash
python movies.py
```

---

## 📈 Output

The project generates:

- Dataset with Cluster Labels
- Cluster Centers
- Elbow Method Graph
- PCA Cluster Visualization
- PCA Cluster Visualization with Centroids
- Similar User Recommendations

---

## 📚 Learning Outcomes

This project helped me understand:

- K-Means Clustering
- Unsupervised Machine Learning
- Feature Scaling
- StandardScaler
- Elbow Method
- PCA
- Cluster Interpretation
- Recommendation Systems
- Data Visualization using Matplotlib

---

## 👨‍💻 Author

**Danish Solkar**

---

## ⭐ If you found this project helpful, consider giving it a Star!
