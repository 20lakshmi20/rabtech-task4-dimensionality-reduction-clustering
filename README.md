# RabTech Task 4: Dimensionality Reduction & Unsupervised Clustering

## Goal
Standardize numerical features, apply PCA, choose principal components using explained variance, compare K-Means cluster counts with the Elbow Method and Silhouette Score, and visualize clusters. The notebook also demonstrates DBSCAN and hierarchical clustering.

## Dataset
This starter reuses the UCI Student Performance Mathematics dataset (`student-mat.csv`) from Task 2/Task 3. Copy that CSV into `data/raw/student-mat.csv`.

If you do not have the CSV, download the Student Performance dataset from the UCI Machine Learning Repository and place `student-mat.csv` in `data/raw/`.

## Setup in VS Code
1. Open this folder in VS Code.
2. Create/activate your Python virtual environment (you can reuse the approach from Task 3).
3. Install packages:
   `python -m pip install -r requirements.txt`
4. Open `notebooks/task4_clustering.ipynb`.
5. Select your `.venv` Python environment as the notebook kernel.
6. Choose **Run All** and save the notebook.

## Dataset note
The notebook clusters students using numerical academic/demographic features and does not use the final grade as a supervised target. Clusters are exploratory patterns, not proven student types or causal explanations.

## Deliverable
A public GitHub repository containing this notebook, README, requirements files, and any non-sensitive supporting material. Do not upload `.venv`, `__pycache__`, or unnecessary generated files.
