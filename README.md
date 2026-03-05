# Movie Recommendation System (Jupyter Notebook)

This project implements and compares multiple movie recommendation strategies in a single Jupyter notebook. The goal is to understand how different similarity and ranking choices affect the final suggestions for a given movie.

## Purpose

- Build a working movie recommendation pipeline.
- Compare five recommendation approaches side by side.
- Evaluate how ranking features (popularity, vote_average) and distance metrics influence recommendation stability.

## What is inside

- Data loading and basic preprocessing
- Feature preparation for similarity comparisons
- Five recommendation strategies (same calling pattern, comparable outputs)
- Side-by-side comparison cells to inspect differences across methods
- A conclusion summarizing the observed behavior

## Main technologies

- Python 3
- Jupyter Notebook
- NumPy, pandas
- scikit-learn (for vectorization and/or distances, when used)
- nlkt
- ast

## Data techniques used

- Basic cleaning and column normalization
- Feature selection and numeric scaling (when applicable)
- Similarity and distance-based retrieval
  - ranking-based approach using popularity and vote_average
  - Euclidean distance
  - Manhattan distance
  - plus the other two strategies implemented in the notebook
- Top-N recommendation generation for a given title
- Consistency comparison across models (same input, compare outputs)

## How to run

1. Create and activate a virtual environment (optional but recommended).
2. Install dependencies.
3. Open the notebook and run all cells.
