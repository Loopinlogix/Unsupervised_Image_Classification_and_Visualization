# Unsupervised_Image_Classification_and_Visualization

🎉 Unsupervised Image Clustering & Visualization
aka: Teaching K‑Means to Recognize People It’s Never Met Before
https://img.shields.io/badge/Python-3.10-blue?style=flat-square
https://img.shields.io/badge/NumPy-1.26-orange?style=flat-square
https://img.shields.io/badge/scikit--learn-1.4-green?style=flat-square
https://img.shields.io/badge/Matplotlib-3.8-purple?style=flat-square
https://img.shields.io/badge/Project-100%25-Done-success?style=flat-square

Welcome to the Olivetti Faces Adventure, where we take 400 grayscale faces from the 90s and convince a machine to group them into clusters — without telling it what a face is.
It’s like giving a toddler a box of photos and saying:

“Sort these by vibes.”

And somehow… it works.

🤖 What This Project Does (in human language)
This repo explores how machines “see” faces using:

K‑Means Clustering (the machine plays “match the faces”)

Cosine Similarity (which faces are besties?)

PCA (compressing faces like a .zip file)

t‑SNE (turning math into pretty scatter plots)

Train/Test Splits (can the machine generalize or does it panic?)

Cluster Centroids (the “average face” of each group — surprisingly creepy)

📸 Visual Highlights
(Replace these with your actual images — GitHub loves visuals)

🎭 Random Faces
A chaotic collage of strangers who all look like they’re about to star in a 1993 sitcom.

😐 The Mean Face
The average of all faces.
Looks like someone who would say “We need to talk.”

🔥 Variance Heatmap
Shows which pixels change the most.
Spoiler: eyes and mouth — humans are expressive, who knew?

🌈 t‑SNE & PCA Plots
Beautiful scatter plots where each dot is a face.
It’s like a galaxy, but instead of stars, it’s dudes from the 90s.

🧪 Full Workflow (fun edition)
1. Import Libraries
We summon NumPy, Matplotlib, scikit‑learn, and other magical creatures.

2. Load the Olivetti Faces Dataset
400 faces.
64×64 pixels.
4096‑dimensional vectors.
Your laptop cries a little.

3. EDA: Look at Faces
We show random faces because… why not.

4. Pixel Intensity Histogram
A graph that says:

“These faces are mostly gray.”

5. Mean Face & Variance Face
The mean face is unsettling.
The variance face looks like a thermal camera caught someone lying.

6. Cosine Similarity
Which faces are mathematically similar?
The machine decides who looks like who.

7. K‑Means Clustering
We tell the machine:

“There are 40 people. Figure it out.”
It tries its best.

8. Elbow Method
A plot that looks like a rollercoaster but tells you nothing.
Still fun to include.

9. Predicting Clusters
We ask K‑Means:

“Which group does this face belong to?”
It answers confidently, even when wrong.

10. Five Samples Per Cluster
A gallery of faces grouped by cluster.
Some clusters make sense.
Some are chaos.
All are hilarious.

11. PCA & t‑SNE Visualizations
Turning 4096 dimensions into 2.
Magic.

12. Train/Test Split
We hide 20% of faces and see if the machine panics.
It does okay.

13. Cluster Centroids
The “average face” of each cluster.
Looks like NPCs from a PS1 game.

🧩 Tech Stack
Python

NumPy

Matplotlib

scikit‑learn

PCA

t‑SNE

Cosine Similarity

A lot of patience

🚀 How to Run
bash
pip install numpy matplotlib scikit-learn
Run the script in:

Jupyter Notebook

Google Colab

VS Code

Anywhere that supports Python and existential dread

🎓 What You Learn
How unsupervised learning works

How machines “see” faces

Why dimensionality reduction is magic

Why cluster centroids look haunted

How to visualize high‑dimensional data

How to evaluate clustering on unseen images

🙌 Credits
Dataset from AT&T Laboratories Cambridge via scikit‑learn.
Faces from the 90s.
Chaos provided by K‑Means.
