# ML_for_Predictive_Maintenance
## Project Overview

This project focuses on analyzing a predictive maintenance dataset to understand and identify potential device failures. The core of this analysis is a Jupyter Notebook that performs data loading, exploration, and correlation analysis.

## Dataset

The dataset used in this project is `predictive_maintenance_dataset.csv`. It contains various metrics for different devices over time, along with a 'failure' column indicating whether a device experienced a failure.

### Columns:
- `date`: The date of the data record.
- `device`: The unique identifier for each device.
- `failure`: A binary indicator (0 for no failure, 1 for failure).
- `metric1` to `metric9`: Various operational and performance metrics for the devices.

## Analysis Steps

The `Pred_Maintenance_.ipynb` Jupyter Notebook performs the following key steps:
1.  **Library Imports:** Imports essential libraries for data manipulation and visualization.
2.  **Data Loading:** Loads the `predictive_maintenance_dataset.csv` file into a pandas DataFrame.
3.  **Initial Exploration:** Checks for missing values, duplicates, and class imbalance in the target variable (`failure`).
4.  **Feature Engineering:** Extracts additional time-based features like month and weekday from the 'date' column.
5.  **Correlation Analysis:** Calculates and visualizes the correlation matrix to understand the relationships between different metrics and device failure.

## Requirements

To run the Jupyter Notebook, you will need to install the libraries listed in the `requirements.txt` file.

## How to Run the Project

1.  Clone this repository.
2.  Install the required packages using pip:
    ```bash
    pip install -r requirements.txt
    ```
3.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook Pred_Maintenance_.ipynb
    ```
