# Unsupervised_Image_Classification_and_Visualization
🧠 Unsupervised Image Clustering & Visualization
Olivetti Faces Dataset — K‑Means, PCA, t‑SNE, Similarity Analysis
This project performs unsupervised image clustering and high‑dimensional visualization using the classic Olivetti Faces dataset.
It includes full exploratory data analysis (EDA), clustering, dimensionality reduction, similarity analysis, and visualization of results.

📌 Project Overview
The goal of this project is to explore how unsupervised learning techniques can group facial images without labels.
We use:

K-Means Clustering

Cosine Similarity

PCA (2D + 50D)

t‑SNE

Train/Test Splits for cluster generalization

Cluster centroid visualization

This workflow is ideal for learning unsupervised ML concepts, image preprocessing, and high‑dimensional visualization.

📂 Dataset: Olivetti Faces
400 grayscale images

Each image: 64 × 64 pixels

Flattened vector: 4096 features

40 individuals × 10 images each

Loaded using:

python
from sklearn.datasets import fetch_olivetti_faces
🧪 Workflow Summary
1. Import Libraries
NumPy, Matplotlib, scikit‑learn (KMeans, PCA, t‑SNE), cosine similarity, and train/test split.

2. Load Dataset
We load the images and flattened pixel vectors, inspect shapes, and check pixel intensity ranges.

3. Exploratory Data Analysis (EDA)
Includes:

Random face visualization

Pixel intensity histogram

Mean face

Variance heatmap

Additional random samples

These steps help understand the dataset’s structure and variability.

4. Cosine Similarity Matrix
We compute similarity between the first 50 images to observe how facial features relate in high‑dimensional space.

5. K‑Means Clustering
We cluster the dataset into 40 clusters (matching the number of individuals).
Outputs include:

Cluster labels

Cluster centroids

Label visualization

Elbow method to explore optimal k

6. Cluster Sampling
For each cluster, we display five sample images to visually inspect cluster consistency.

7. Dimensionality Reduction
PCA (50 components)
Used as preprocessing for t‑SNE.

PCA (2D)
Scatter plot colored by cluster labels.

t‑SNE (2D)
Nonlinear embedding for deeper structure visualization.

8. Train/Test Split & Generalization
We split the dataset:

80% training

20% testing

Then:

Train K‑Means on training data

Predict clusters for test data

Visualize test predictions

PCA & t‑SNE plots for test embeddings

This shows how well clustering generalizes to unseen images.

9. Cluster Centroid Visualization
We reshape cluster centroids into 64×64 images to visualize the “average face” of each cluster.

📊 Visualizations Included
Random faces

Pixel intensity histogram

Mean face

Variance heatmap

Cosine similarity matrix

Cluster label scatter plot

Elbow method

PCA 2D scatter

t‑SNE scatter

Test image predictions

PCA/t‑SNE test visualizations

Cluster centroid images

🧩 Technologies Used
Python 3.x

NumPy

Matplotlib

scikit‑learn

t‑SNE

PCA

Cosine Similarity

🚀 How to Run
Install dependencies:

bash
pip install numpy matplotlib scikit-learn
Run the script in Jupyter, Colab, or any Python environment.

All visualizations will appear inline.

📘 Learning Outcomes
By completing this project, you will understand:

How unsupervised clustering works

How to visualize high‑dimensional data

How PCA and t‑SNE differ

How cluster centroids represent learned patterns

How to evaluate clustering on unseen data

🙌 Acknowledgements
Dataset provided by AT&T Laboratories Cambridge via scikit‑learn.
