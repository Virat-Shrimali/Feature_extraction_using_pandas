# Feature Extraction Using Pandas

This repository contains a Jupyter Notebook that demonstrates feature extraction and basic data manipulation using Pandas on an anime ranking dataset.

## Project Summary

The notebook loads a CSV dataset, inspects its structure, and extracts a new feature from a text column. It focuses on practical Pandas techniques for cleaning and transforming data that is initially stored in a messy combined format.

## What the Notebook Does

- Imports `numpy` and `pandas`
- Loads the `anime.csv` dataset from a GitHub raw URL
- Loading and inspecting the dataset
- Performing basic Pandas operations
- Extracting useful features from the data
- Preparing the data for further analysis

## Techniques Used

- Reading CSV data with `pd.read_csv()`
- Inspecting dataframe shape and column types with `df.info()`
- Accessing individual rows with `df.loc[]`
- Writing a custom extraction function with string parsing logic
- Applying a function across a column with `Series.apply()`
- String replacement with `str.replace()`
- Type conversion with `astype(int)`
- Feature engineering from a compound text field

## Dataset Details

The dataset used in the notebook contains anime ranking data with the following original columns:

- `Rank`
- `Title`
- `Score`

The notebook creates an additional derived column:

- `Episodes`

## Result

After processing, the dataframe includes a new numeric `Episodes` column that can be used for further analysis, visualization, or machine learning tasks.

## Reference

- **Video Tutorial:** Pandas Data Capstone Tutorial — Akarsh Vyas  
  https://youtu.be/QUaSmqBeR9w
- **Dataset Source:** `anime.csv` from `AkarshVyas/Pandas-Youtube`

## Requirements

- Python
- Jupyter Notebook
- Pandas
- NumPy

## Repository Purpose

This project is useful for learning:

- Basic Pandas data handling
- Feature extraction from messy text data
- Simple preprocessing workflows
- Converting raw text into structured numeric data
