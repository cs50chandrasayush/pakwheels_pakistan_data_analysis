# pakwheels_pakistan_data_analysis
# [Project Title: e.g., Pakwheels Pakistan Automobile Data Analysis]

## Overview

This project performs exploratory data analysis (EDA) on a dataset of automobiles listed on Pakwheels Pakistan. The analysis includes data loading, cleaning, preprocessing, and visualization to gain insights into the characteristics and pricing of vehicles in the Pakistani market.

## Dataset

The dataset used in this project is the **Pakwheels Pakistan Automobile Dataset**.

## Project Structure

-   `pakwheels_data_analysis`: This is the main Jupyter Notebook containing all the code for data loading, cleaning, analysis, and visualization.
-   `[pakwheels_pakistan_automobile_dataset]`: The raw dataset file. 
-   `[cleaned_pakwheels_automobile_data]`: The cleaned dataset file. 
## Analysis Performed

The Jupyter Notebook covers the following steps:

1.  **Data Loading and Initial Inspection:** Loading the dataset and examining its shape, basic statistics, and column information.
2.  **Data Cleaning:**
    * Handling duplicate entries.
    * Checking for and managing missing (NaN/NA) values.
    * Addressing inconsistencies or placeholder values in the 'price' column (e.g., zero prices).
    * Cleaning and standardizing text data (e.g., 'title' column).
3.  **Feature Engineering:**
    * Extracting relevant information from existing columns, such as the manufacturing year from the 'title'.
    * Identifying and extracting the car brand.
4.  **Exploratory Data Analysis (EDA) and Visualization:**
    * Analyzing the distribution of key features like price and engine capacity.
    * Identifying the most common car brands.
