# Netflix EDA Project

## Overview
This project performs Exploratory Data Analysis (EDA) on the Netflix titles dataset. It includes data cleaning, visualization, and insights into the content available on Netflix, such as the distribution of movies vs. TV shows, release years, countries, ratings, and more.

## Dataset
The analysis is based on the `netflix_titles.csv` file, which contains information about Netflix titles including type (Movie/TV Show), title, director, cast, country, date added, release year, rating, duration, listed_in (genres), and description.

## Requirements
To run this notebook, you need the following Python libraries:
- numpy
- pandas
- matplotlib
- seaborn

You can install them using pip:
```
pip install numpy pandas matplotlib seaborn
```

## How to Run
1. Ensure `netflix_titles.csv` is in the same directory as the notebook.
2. Open `EDA.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells in order to perform data loading, cleaning, and generate visualizations.

## Analysis Summary
The notebook covers:
- **Data Cleaning**: Removing duplicates, handling missing values, and feature engineering (e.g., extracting year and month added).
- **Visualizations**:
  - Count of Movies vs. TV Shows.
  - Distribution of release years.
  - Top 10 content-producing countries.
  - Ratings distribution.
  - Year added vs. content type.
  - Top 10 genres.
  - Movie duration distribution.
  - Ratings by content type.

## Key Insights
- Insights derived from the visualizations, such as trends in content addition over years, popular genres, and rating distributions.

## License
This project is for educational purposes. The dataset is publicly available on Kaggle or similar platforms.
