# datafun-07-ml

**Author:** Abdelhafidh Mahouel  
**Repository:** https://github.com/AbdelhafidhMahouel/datafun-07-ml  

---

## Overview

This repository contains **Project 7: Predictive Machine Learning Project (Module 7)**.  
The project focuses on applying **simple linear regression** techniques to real-world time-series data using Python.

The work follows the **guided examples and structure required by the course**, based on the Deitel textbook. The project demonstrates how historical data can be analyzed, visualized, and used to make future predictions, while comparing different regression approaches.

All analysis, modeling, visualizations, and insights are contained in a single Jupyter Notebook.

---

## Textbook Chapters / References

This project is based directly on examples and concepts from:

**Deitel & Deitel – _Intro to Python for Computer Science and Data Science_**

- **Chapter 10.16** – Intro to Data Science: Time Series and Simple Linear Regression  
  - Understanding linear relationships  
  - Visualizing straight-line trends  
  - Using SciPy for regression and prediction  

- **Chapter 15.4** – Case Study: Time Series and Simple Linear Regression  
  - Applying machine learning concepts  
  - Using scikit-learn’s `LinearRegression`  
  - Comparing workflows and results  

Textbook example repository (data and sample code):  
https://github.com/pdeitel/IntroToPython

---

## Project Objectives

The main objectives of this project are to:

- Load and inspect real-world time-series data using pandas
- Clean and prepare data for analysis
- Build predictive models using:
  - **SciPy** (`stats.linregress`)
  - **scikit-learn** (`LinearRegression`)
- Predict future values based on historical trends
- Visualize data and regression lines using Matplotlib and Seaborn
- Compare regression approaches and reflect on results

---

## Project Deliverables

This repository includes the following required deliverables:

- `README.md`  
  Project documentation and description (this file)

- `abdel_ml.ipynb`  
  Completed Jupyter Notebook containing:
  - Part 1: Charting a straight line  
  - Part 2: Prediction using SciPy  
  - Part 3: Prediction using scikit-learn  
  - Part 4: Insights and comparison  

- `data/ave_hi_nyc_jan_1895-2018.csv`  
  Dataset containing historical average high temperatures for January in New York City

- Supporting project files:
  - `.gitignore`
  - `pyproject.toml`
  - `.venv` (local virtual environment, not committed)

---

## Dataset Description

The dataset used in this project contains **average high temperatures in New York City for the month of January** over many years.

- Location: New York City  
- Metric: Average high temperature (°F)  
- Time series: One value per year (January only)

The dataset is provided through the Deitel textbook resources and is used exactly as required by the course instructions.

---

## Notebook Structure

The Jupyter Notebook (`abdel_ml.ipynb`) is organized to **match the instructor’s required structure** and textbook workflow.

### Part 1 – Chart a Straight Line
- Review of the linear equation: **y = mx + b**
- Visualization of a simple linear relationship
- Reinforcement of slope and intercept concepts

### Part 2 – Prediction Using SciPy
- Data acquisition and inspection
- Data cleaning and preparation
- Descriptive statistics
- Linear regression using `scipy.stats.linregress`
- Prediction of January average high temperature for a future year
- Visualization of data and best-fit line

### Part 3 – Prediction Using scikit-learn
- Train/test data split
- Model training with `LinearRegression`
- Model testing and evaluation
- Prediction using the trained model
- Visualization and comparison with SciPy results

### Part 4 – Insights
- Comparison of SciPy and scikit-learn approaches
- Discussion of similarities and differences
- Reflection on model behavior and limitations

---

## Tools and Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- SciPy
- scikit-learn

All work was performed inside a local Python virtual environment.

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdelhafidhMahouel/datafun-07-ml