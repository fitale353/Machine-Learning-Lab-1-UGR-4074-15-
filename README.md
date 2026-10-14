#Machine learning lab 1

## Data Exploration and Foundational Math

This project explores a student performance dataset generated with Python. It practices data cleaning, descriptive statistics, visualization, correlation, dot products, and feature scaling.

## Dataset

The dataset contains 100 student records and four columns:

- `study_hours` — hours spent studying
- `attendance` — attendance measure
- `previous_mark` — previous academic mark
- `final_score` — score to be analyzed and predicted

The provided data includes missing values in `study_hours`, an outlier of 50 study hours, and an impossible attendance value of -10. These records are inspected and handled during the analysis.

## Assignment Tasks

- Inspect and clean the data.
- Identify the feature matrix, numerical columns, and target variable.
- Calculate the mean, median, and standard deviation for each column.
- Create a histogram of `final_score` and a scatter plot of `study_hours` versus `final_score`.
- Calculate the Pearson correlation between `study_hours` and `final_score`.
- Use NumPy to calculate a weighted prediction using a feature vector, weights, and bias.
- Standardize `study_hours` and `previous_mark`.
- Explain why scaling matters for distance-based algorithms such as K-Nearest Neighbors.

## Requirements

- Python 3
- pandas
- NumPy
- Matplotlib

## How to Run

1. Clone or download this repository.
2. Open the analysis notebook or Python script.
3. Install any missing requirements:

   ```bash
   pip install pandas numpy matplotlib

Run the notebook cells or Python script.
Results
The analysis, calculations, visualizations, and written observations are included in the notebook or script in this repository.

Author
Fitale Tariku 
ID NO. UGR/4074/15
