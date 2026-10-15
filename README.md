Spotify Songs' Genre Segmentation and Recommendation Engine

Project Overview

This project analyzes a dataset of Spotify songs to automatically segment them into distinct auditory clusters based purely on how they sound, without relying on human-assigned genres. Using these clusters, I built a recommendation engine that suggests new songs based on the audio features of a track you already enjoy.

Features

Data Cleaning & Scaling: Handled missing values, removed duplicates, and standardized audio features (like tempo, energy, and acousticness).

Exploratory Data Analysis (EDA): Visualized genre distributions and the acoustic profile of the dataset.

Feature Correlation: Mapped out how different musical features relate to one another using a correlation heatmap.

Machine Learning (K-Means Clustering): Grouped songs into 8 distinct clusters based purely on mathematical similarities in their sound.

Dimensionality Reduction (PCA): Visualized the 9-dimensional audio features on a 2D map to easily view the clusters.

Recommendation Engine: Built a fast cosine-similarity engine that finds the 5 closest sounding songs to any given input within its specific cluster.

Tools & Libraries Used

Python: The core programming language.

Pandas & NumPy: For data manipulation and math.

Matplotlib & Seaborn: For drawing graphs and heatmaps.

Scikit-Learn: For K-Means clustering, PCA, and Cosine Similarity calculations.

How to Run

Clone this repository.

Ensure you have the spotify dataset_2.csv file in the same directory.

Open Spotify_Project.ipynb in Google Colab or Jupyter Notebook.

Run all cells sequentially.
