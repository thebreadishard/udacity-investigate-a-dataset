# Investigate a Dataset — TMDb Movie Data

Udacity Data Analyst project: an exploratory data analysis of the
[TMDb movie dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata) using
NumPy, pandas, and matplotlib/seaborn within a Jupyter Notebook.

## Dataset

The dataset contains information on ~10,000 movies collected from
[The Movie Database (TMDb)](https://www.themoviedb.org/), including user
ratings, budget, and revenue.

- Columns such as `cast` and `genres` contain multiple pipe-separated (`|`)
  values.
- The `budget_adj` and `revenue_adj` columns express budget and revenue in
  terms of 2010 U.S. dollars, accounting for inflation.

The data file is included at
`Database_TMDb_movie_data/tmdb-movies.csv`.

## Questions Explored

_To be finalized as the analysis develops._

## Project Structure

```
Investigate_a_Dataset.ipynb        # Analysis and report
Database_TMDb_movie_data/
    tmdb-movies.csv                # TMDb dataset
```

## How to Run

1. Create and activate a virtual environment:
   ```powershell
   python -m venv .venv
   .\.venv\Scripts\Activate.ps1
   ```
2. Install the dependencies:
   ```powershell
   pip install numpy pandas matplotlib seaborn jupyter
   ```
3. Open `Investigate_a_Dataset.ipynb` in Jupyter or VS Code and run the cells
   top to bottom.

## Summary of Findings

_To be completed at the end of the analysis._

## License

This project is licensed under the terms described in [LICENSE](LICENSE). The
project template and dataset are provided by Udacity.
