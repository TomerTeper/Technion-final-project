
# Movie Data Analysis and Machine Learning Project

## Overview

This project aims to analyze and predict movie revenues using various machine learning models. It includes comprehensive exploratory data analysis (EDA), feature engineering, and the implementation of multiple machine learning models. Additionally, the project leverages Explainable AI (XAI) techniques, specifically SHAP (SHapley Additive exPlanations), to interpret the models and understand feature importance.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Feature Engineering](#feature-engineering)
- [Machine Learning Models](#machine-learning-models)
  - [Linear Regression](#linear-regression)
  - [RandomForestRegressor](#randomforestregressor)
  - [XGBoost](#xgboost)
- [SHAP Analysis](#shap-analysis)
- [Installation](#installation)
- [Usage](#usage)


## Dataset

The dataset used in this project is from The Movie Database (TMDB). It contains information about movies including revenue, budget, cast, crew, genres, and other metadata.

## Exploratory Data Analysis (EDA)

### Revenue Analysis
We explored the distribution of movie revenues and applied log transformations to handle skewness.

### Title Analysis
- Generated word clouds for movie titles.
- Analyzed the length of movie titles.

### Overview Analysis
- Generated word clouds for movie overviews.
- Analyzed the length of movie overviews.

### Tagline Analysis
- Generated word clouds for movie taglines.
- Analyzed the length of movie taglines.

### Budget Analysis
Explored the distribution of movie budgets and applied log transformations.

### Genre Analysis
Processed and visualized the distribution of movie genres.

### Language Analysis
Analyzed the distribution of original languages and identified English movies.

## Feature Engineering

- Log transformations for skewed features (revenue, budget, popularity, etc.).
- Length of text features (title, overview, tagline).
- Processed genres, production companies, and countries.
- Added binary features for top actors, keywords, and directors.

## Machine Learning Models

### Linear Regression

Used Linear Regression to predict movie revenues.

### RandomForestRegressor

Implemented RandomForestRegressor for predicting movie revenues.

### XGBoost

Utilized XGBoost for predicting movie revenues.

## SHAP Analysis

We used SHAP (SHapley Additive exPlanations) to explain the output of the RandomForestRegressor model.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/TomerTeper/IDC-Machine-Learning-from-Data.git
    ```
2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Load the dataset.
2. Run the exploratory data analysis and feature engineering scripts.
3. Train and evaluate machine learning models using the provided scripts.
4. Use SHAP to analyze feature importance and model explanations.

