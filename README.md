# Retail Sales Analysis:

This repository contains a data analysis project that explores sales data from a retail dataset. The analysis is performed using Python with the Pandas, Matplotlib, and Seaborn libraries in a Jupyter Notebook.

The primary goal of this analysis is to identify key sales trends and performance metrics across different product categories.

## Dataset

The dataset used for this analysis is `Data Analyst Assessment - dataset 1.csv`.

It contains transactional data, including the following key columns:
* **Category**: The product category (e.g., Groceries, Shoes, Womens).
* **Sales**: The total sales amount for a given transaction or item.

## Requirements

To run this analysis, you will need Python 3 and the following libraries installed:

* pandas
* numpy
* matplotlib
* seaborn
* jupyter-notebook

You can install these dependencies using pip:
```bash
pip install pandas numpy matplotlib seaborn jupyter-notebook
```

## How to Use

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <your-repository-name>
    ```
3.  **Ensure you have installed the required libraries** (see Requirements section above).

4.  **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  **Open the notebook file:**
    In the Jupyter interface that opens in your browser, click on `Heart_it_Out_checkpoint.ipynb` to open the notebook and run the cells. The notebook is set up to load the `Data Analyst Assessment - dataset 1.csv` file directly.

## Analysis Overview

The Jupyter Notebook (`Heart_it_Out_checkpoint.ipynb`) performs the following steps:

1.  **Data Loading:** The `Data Analyst Assessment - dataset 1.csv` file is loaded into a pandas DataFrame.
2.  **Data Audit:** An initial inspection of the data is conducted to understand its structure, identify data types, and check for missing values.
3.  **Exploratory Data Analysis (EDA):** The core of the analysis involves using a `pivot_table` to aggregate total sales by product category.
4.  **Sorting and Ranking:** The categories are sorted based on their total sales to identify the top-performing and lowest-performing categories.
5.  **Visualization:** Although not fully detailed in the snippet, the inclusion of `matplotlib` and `seaborn` suggests that the notebook likely contains visualizations (e.g., bar charts) to represent the sales performance of different categories.

### Key Finding

The primary output of the analysis is a table that ranks product categories by their total sales in descending order, providing clear insights into which categories are the main drivers of revenue.

    

