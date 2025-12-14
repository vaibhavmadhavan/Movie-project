# Movie Recommender System (MovieLens)

VS Code Jupyter notebook that explores MovieLens **ml-latest-small** and builds an item-based collaborative filtering recommender using **cosine similarity**.

## What this notebook covers
- Load `ratings.csv` + `movies.csv` and merge them
- EDA: rating distribution + average rating/count per movie
- Filter popular movies (movies with **> 100 ratings**)
- Build user–movie matrix (pivot) and fill missing ratings with 0
- Compute movie–movie cosine similarity and use it for recommendations

## Dataset
Download MovieLens (ml-latest-small): https://grouplens.org/datasets/movielens/  
Files used: `ratings.csv`, `movies.csv`

> Dataset files are not included in this repo. Update the CSV file paths in the notebook before running.

## Run locally
pip install pandas numpy matplotlib seaborn scikit-learn
Then open `movie_project.ipynb` in VS Code and Run All.

## Tech stack
Python, pandas, numpy, seaborn/matplotlib, scikit-learn
