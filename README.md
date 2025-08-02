# A-Predictive-Analysis-of-Uber-s-2016-Ride-Hailing-Data


## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the "Uber Drives 2016" dataset to uncover patterns, trends, and key insights from the trip data. Additionally, it includes a machine learning model to predict trip duration based on various features.

## Dataset

This project uses the **Uber Drives 2016** dataset, which can be found on platforms like Kaggle.

You **must** download the dataset and update this path in the notebook to point to the location of `UberDataset.csv` on your own system.

## Key Features & Analysis

-   **Data Cleaning & Preprocessing:** Handles missing values and converts date columns to the correct datetime format for analysis.
-   **Feature Engineering:** Extracts new features like trip duration, month, day of the week, and hour from the raw data.
-   **Exploratory Data Analysis (EDA):**
    -   Distribution of trip durations and distances.
    -   Analysis of trip frequency by hour of the day and day of the week.
    -   Identification of trips occurring during rush hour.
-   **Machine Learning - Trip Duration Prediction:**
    -   A **Random Forest Regressor** is trained to predict the duration of a trip in minutes.
    -   Categorical features like 'CATEGORY' and 'PURPOSE' are encoded for the model.
    -   The model's performance is evaluated using Root Mean Squared Error (RMSE) and R² Score.
    -   A feature importance plot is generated to show which factors most influence the trip duration prediction.


## How to Run

1.  Ensure you have downloaded the `UberDataset.csv` file.
2.  Open the `uber_analysis.ipynb` notebook and **update the file path** in the cell where the data is loaded.
3.  Run the Jupyter Notebook:
    ```bash
    jupyter notebook uber_analysis.ipynb
    ```
4.  Execute the cells in the notebook sequentially to see the analysis and model results.
