# FIFA Dataset Analysis

- Dataset link: https://www.kaggle.com/datasets/maso0dahmed/football-players-data

## Overview
This project performs an **exploratory data analysis (EDA)** on a FIFA player dataset. The goal is to understand player attributes, uncover patterns, handle missing data, and identify top-performing players based on various metrics.

## Features
- Load and inspect the FIFA dataset using **pandas**.  
- Explore numeric columns: check for missing values, duplicates, and basic statistics.  
- Handle missing values using `fillna` for numeric columns.  
- Aggregate and summarize data using:  
  - **GroupBy**  
  - **Pivot Tables**  
- Sort and locate players with **highest/lowest values** in different metrics.  
- Visualize insights using **Seaborn** and **Matplotlib**:
  - Histograms and boxplots for distributions  
  - Bar plots, strip plots, and count plots for categorical comparisons  
  - Scatter plots and pairplots for relationships between numeric features  
  - Heatmaps for correlations and pivot table summaries  

## Dataset
- Columns include player info (name, nationality, age, height, weight), attributes (overall_rating, potential, dribbling, finishing, etc.), financial data (value_euro, wage_euro), and positional data.  
- Numeric and categorical data are handled separately for analysis.  
- Missing values handled appropriately with `fillna`. 

## Technologies Used
- Python 3.x  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## Example Analyses
- Average dribbling per nationality  
- Players with maximum dribbling, finishing, or overall rating  
- Distribution of age, wage, and potential  
- Multi-dimensional summaries using pivot tables (e.g., average rating per nationality × primary position)  
- Visualization of relationships between attributes  

## Usage
1. Clone the repository or download the dataset.  
2. Load the dataset in a Python environment:  
- import pandas as pd
- df = pd.read_csv('fifa_players.csv')
3. Perform analysis using groupby, pivot tables, or visualization functions.
4. Use .fillna() to handle missing values when needed.
5. Create plots with Seaborn/Matplotlib to explore trends and relationships.
