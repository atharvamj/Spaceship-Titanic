# Spaceship Titanic Data Processing and Classification

This repository contains Python code for data processing and classification tasks related to the Spaceship Titanic dataset. The dataset is used for machine learning, and the code includes data preprocessing and building a classification model.

## Overview

The provided Jupyter notebook is organized into two major sections:

### Data Processing

The data processing section involves several key steps:
- Handling missing values
- Interpolating numeric features
- Filling categorical features with the most frequent category
- Splitting the data into training and testing sets

### Classification Model

The classification section focuses on the following tasks:
- Defining categorical and numeric transformers using Pipelines
- Combining transformers using a ColumnTransformer
- Creating a classification pipeline that includes data preprocessing
- Utilizing a RandomForestClassifier (replace it with your chosen classifier)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/atharvamj/Spaceship-Titanic.git
    ```

2. Navigate to the project directory:

    ```bash
    cd Titanic_Comp_1
    ```

Make sure to update the file paths and adjust the scripts based on your specific dataset and requirements.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- pandas
- scikit-learn
- NumPy

Install the required dependencies using:

```bash
pip install -r requirements.txt
