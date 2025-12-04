# Netflix Titles Model Comparison

## Overview
This project analyzes the Netflix titles dataset to compare the performance of two machine learning models—Logistic Regression and Random Forest—in predicting whether a title is a Movie or a TV Show. The analysis includes data cleaning, feature engineering, model training, evaluation, and visualization of results.

## Dataset
- **File**: `netflix_titles.csv`
- **Source**: Netflix titles dataset (assumed to be publicly available or provided).
- **Description**: Contains information about Netflix titles, including type (Movie/TV Show), release year, rating, duration, country, and more.

## Requirements
To run this project, you need the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install them using pip:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Ensure `netflix_titles.csv` is in the same directory as the notebook.
2. Open `Comparing_two_models.ipynb` in Jupyter Notebook or JupyterLab.
3. Run the cells sequentially to:
   - Load and clean the data.
   - Prepare features for machine learning.
   - Train and evaluate the models.
   - View the comparison table and confusion matrix.

## Models Compared
- **Logistic Regression**: A linear model for binary classification.
- **Random Forest**: An ensemble method using multiple decision trees.

## Evaluation Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

A confusion matrix is provided for the Random Forest model.

## Results
- Random Forest generally outperforms Logistic Regression in this dataset.
- Detailed metrics and visualizations are generated in the notebook.

## File Structure
- `Comparing_two_models.ipynb`: Main Jupyter notebook with the analysis.
- `netflix_titles.csv`: Dataset file.
- `README.md`: This file.

## Contributing
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is for educational purposes. Ensure compliance with dataset licensing.
