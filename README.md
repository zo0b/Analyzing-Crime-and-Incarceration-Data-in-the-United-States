# Analyzing Crime and Incarceration Data in the United States: Capstone Project

## Overview

This repository contains the analysis and simulation of crime and incarceration data in the United States from 2001 to 2016. This capstone project, conducted by our group, explores various statistical methods and machine learning models to analyze and predict crime trends.

## Project Members

- **Bryce Lam**: Mapping and Reducing
- **Zubair Ali**: Logistic Regression, Linear Regression
- **Evan Cheng**: Clustering

## Data Sources

- **Kaggle Dataset**: [Prisoners and Crime in United States](https://www.kaggle.com/datasets/christophercorrea/prisoners-and-crime-in-united-states/data)
- **GitHub CSV Files**: [Crime and Incarceration Dataset](https://github.com/evanwc/Kaggle-Crime-and-Incarceration-Dataset/tree/main)

## Project Structure

- **data/**: Directory containing the dataset files.
  - `crime_and_incarceration_by_state.csv`
  - `prison_custody_by_state.csv`
  - `ucr_by_state.csv`
- **CS4650_Capstone_Project.ipynb**: Jupyter Notebook containing the analysis and results.
- **README.md**: This file.

## Description

The dataset includes population data, prisoner counts, and records of violent and property crimes. The violent crimes recorded include murder, rape, robbery, and aggravated assault. Property crimes recorded include burglary, larceny, and vehicle theft. The dataset required some cleaning, such as removing rows with missing statistics and removing federal statistics that do not contain specific crime data.

## Analyses Conducted

### Mapping and Reducing
*Conducted by Bryce Lam*
- This section involves preprocessing the data and performing initial exploratory data analysis to understand the distribution and trends using `mrjob`.

### Logistic Regression and Linear Regression
*Conducted by Zubair Ali*
- This section involves building and evaluating logistic and linear regression models to classify and predict outcomes based on the dataset.

### Clustering
*Conducted by Evan Cheng*
- This section involves performing clustering analysis to identify patterns and group similar data points within the dataset.

## Installation

To run the code in this repository, you will need the following software and libraries:
- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- mrjob

You can install the necessary libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn mrjob
```

## Usage

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/cs4650-capstone-project.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd cs4650-capstone-project
    ```

3. **Ensure the data files are in the `data` directory.**
    - The `data` directory should contain the necessary dataset files:
      - `crime_and_incarceration_by_state.csv`
      - `prison_custody_by_state.csv`
      - `ucr_by_state.csv`
    - If these files are not already in the directory, add them manually.

4. **Open the Jupyter Notebook:**
    ```bash
    jupyter notebook CS4650_Capstone_Project.ipynb
    ```

5. **Run the cells in the Jupyter Notebook:**
    - Follow the instructions in the notebook to execute the code cells. This will perform the data analysis and generate the results as described in the project.

