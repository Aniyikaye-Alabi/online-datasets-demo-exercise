# Student Dropout and Academic Success Prediction Analysis
# Aniyikaye Alabi (alabianiyikaye6@gmail.com)

## Overview

This repository contains a Jupyter notebook that analyzes the "Predict Students' Dropout and Academic Success" dataset from the UCI Machine Learning Repository. The project focuses on exploring student academic outcomes and identifying patterns that may predict dropout rates and academic success.

## Dataset

- **Source**: UCI Machine Learning Repository (Dataset ID: 697)
- **Title**: Predict Students' Dropout and Academic Success
- **Format**: The dataset is automatically fetched using the `ucimlrepo` library
- **Structure**: Contains features (X) and target variables (y) related to student academic performance
- **Link to Dataset**: `https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success`

## Dependencies

The notebook requires the following Python packages:

```bash
pip install ucimlrepo pandas
```

## Code Structure

The notebook includes the following key components:

### Data Loading
- Fetches the dataset directly from UCI ML Repository using `fetch_ucirepo(id=697)`
- Separates features and target variables into pandas DataFrames

### Data Exploration
- **Variable Information**: Displays all dataset variables, including a summary of missing values for each variable
- **Data Preview**: Shows the first 3 rows and last 8 rows of the dataset
- **Data Structure**: Examines the features and targets separately

## Key Features

- **Automated Data Retrieval**: No need to manually download datasets
- **Data Quality Check**: Initial exploration of dataset structure and content
- **Pandas Integration**: Seamless conversion to pandas DataFrames for analysis

## Usage

1. Install required dependencies
2. Run the Jupyter notebook cells sequentially
3. The notebook will automatically fetch the dataset and display initial exploratory information

## Dataset Information

The dataset contains information about students that can be used to predict:
- Student dropout likelihood
- Academic success indicators

The exact features and target variables are displayed when running the notebook's variable information section.
