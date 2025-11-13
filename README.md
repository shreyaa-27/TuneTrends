
# TuneTrends – Music Trends Analysis Using Python

## Overview

TuneTrends is a Python-based data analysis project built using concepts learned during the 5-day Green Skilling Python Workshop.
The project focuses on collecting, merging, cleaning, and analyzing Spotify Regional Weekly Charts to identify trends in songs, artists, and streaming patterns over time.

The notebook demonstrates skills in data handling, preprocessing, exploratory data analysis (EDA), visualization, and basic machine learning.

---

## Project Structure

```
TuneTrends/
│
├── data/
│   ├── regional-in-weekly-*.csv        # Raw weekly data files
│   ├── spotify_all_weeks_combined.csv  # Final merged dataset
│
├── TuneTrends_Analysis_Final.ipynb
├── TuneTrends_Analysis_Final_Commented.ipynb
└── README.md
```

---

## Features

### 1. Data Collection and Merging

* Uses `glob` to automatically collect all weekly CSV files.
* Sorts them chronologically.
* Merges all weeks into a single dataset.
* Saves the final version as `spotify_all_weeks_combined.csv`.

### 2. Data Cleaning and Preprocessing

* Removes duplicates.
* Fixes missing values.
* Converts date columns.
* Renames and organizes fields.

### 3. Exploratory Data Analysis (EDA)

Includes analysis on:

* Most streamed tracks.
* Top artists over time.
* Weekly stream trends.
* Songs with the longest chart presence.
* Correlation analysis.
* Stream distribution patterns.

### 4. Machine Learning

Used simple models such as:

* Linear Regression
* Random Forest Regressor (or the models used in your notebook)

Performed tasks such as:

* Train-test split
* Model training
* Error metric calculation (MAE, MSE, RMSE)
* Model comparison

### 5. Visualizations

Created using `matplotlib` and `seaborn`:

* Line plots
* Bar charts
* Trending patterns
* Heatmaps

---

## Technologies Used

* Python 3
* pandas
* numpy
* glob
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

---

## How to Run the Project

1. Clone the repository:

```
git clone <your-repo-url>
```

2. Install dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open the notebook:

```
jupyter notebook
```

4. Run all cells in:

```
TuneTrends_Analysis_Final.ipynb
```

---

## Purpose of This Project

This notebook was created to practice and apply the Python concepts taught during the Green Skilling Workshop, especially:

* Data analysis with pandas
* Working with multiple files
* Cleaning and transforming data
* Creating plots for insights
* Trying simple machine learning approaches

---

## Feedback

Any feedback or suggestions for improvement are welcome. This project is part of my ongoing learning journey in Python and data analysis.

---


