# NYC Motor Vehicle Crash Analysis

## Project Overview
This project analyzes motor vehicle crash data in New York State using **Python**, **Pandas**, and **Matplotlib**. It explores patterns in crashes over time, across locations, and under different weather and lighting conditions.

The goal is to identify trends and visualize insights that can help understand crash patterns.

---

## Dataset
Data comes from **NY Open Data**:

- [Motor Vehicle Crashes Case Information (3-Year)](https://data.ny.gov/Transportation/Motor-Vehicle-Crashes-Case-Information-Three-Year-/e8ky-4vqe)  
- [Motor Vehicle Crashes Individual Information (3-Year)](https://data.ny.gov/Transportation/Motor-Vehicle-Crashes-Individual-Information-Three/ir4y-sesj)  
- [Motor Vehicle Crashes Violation Information (3-Year)](https://data.ny.gov/Transportation/Motor-Vehicle-Crashes-Violation-Information-Three-/abfj-y7uq)  
- [Motor Vehicle Crashes Vehicle Information (3-Year)](https://data.ny.gov/Transportation/Motor-Vehicle-Crashes-Vehicle-Information-Three-Ye/xe9x-a24f)  

> For this project, a **sample of 50,000 rows** is used for faster processing.

---

## Tools Used
- **Python 3** – programming language  
- **Pandas** – data cleaning and analysis  
- **Matplotlib** – charts and graphs  
- **Google Colab / Jupyter Notebook** – to run the project  

---

## Steps

1. **Load Data** – Import the dataset and clean column names.  
2. **Prepare Data** – Convert date column to datetime, create helper columns:  
   - `month` → month of crash  
   - `Year-Month` → year and month for trend  
   - `Day of Week` → day of the week of crash  
3. **Visualize Data** – Generate charts for:  
   - Crashes per month  
   - Top 10 counties/boroughs  
   - Crashes by day of week  
   - Crashes by weather  
   - Crashes by lighting  
   - Monthly crash trend  

---

## How to Run
1. Open the notebook in **Google Colab** or **Jupyter Notebook**.  
2. Run all cells in order.  
3. Visualizations will be created automatically.

---

## Insights
- Helps identify which months, days, and conditions have higher crash rates.  
- Highlights high-crash counties or boroughs.  
- Provides clear visual trends for analysis.

---

## License
This project is for **educational purposes**. Data is publicly available from [NY Open Data](https://data.ny.gov/).
