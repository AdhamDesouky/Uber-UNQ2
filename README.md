# Uber Data Analysis Project

## Overview

This project involves a comprehensive Exploratory Data Analysis (EDA) on the Uber dataset. The goal is to uncover insights and identify opportunities to optimize Uber trips and improve business efficiency. This analysis was conducted as part of my internship with Uneeq Interns.

## Project Highlights

- **Data Exploration**: Initial exploration, missing values check, data type inspection, and summary statistics computation.
- **Data Preprocessing**: Handling missing values, converting date columns to datetime, and creating new features like `DAY_OF_WEEK`, `WEEKEND`, `TRIP_DURATION`, and `TRIP_DURATION_MIN`.
- **Feature Engineering**: Label encoding for categorical variables.
- **Data Visualization**: Creating count plots and box plots to understand trip purposes, mileage trends, and trip lengths.
- **PDF Report Generation**: Compiling a detailed report using the FPDF library, summarizing key findings and providing recommendations for enhancing Uber trip efficiency and customer satisfaction.

## Files Included

- **UberDataset.csv**: The dataset used for analysis.
- **EDA_Script.py**: The Python script for data exploration, preprocessing, and visualization.
- **Uber_Data_Analysis_Report.pdf**: The generated PDF report with detailed analysis and visualizations.

## How to Use

1. Clone the repository.
2. Install the necessary libraries using `pip install -r requirements.txt`.
3. Run the `EDA_Script.py` to perform the analysis and generate visualizations.
4. Open the PDF report to review the findings and recommendations.

## Recommendations

- Including additional data points like trip fare, trip duration, and driver rating would further enhance the analysis.
- Incorporating weather data and geospatial data could provide deeper insights into trip patterns and customer behavior.
