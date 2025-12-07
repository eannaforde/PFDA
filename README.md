# Programming for Data Analytics – Assignments

This repository contains multiple assignments completed for the *Programming for Data Analytics* module.  
Each assignment demonstrates core Python skills including data loading, cleaning, transformation, visualisation, and basic statistical analysis.

The assignments included:

- **Assignment 02 – Northern Ireland Bank Holidays (Python Script)**
- **Assignment 03 – Email Domain Pie Chart (Jupyter Notebook)**
- **Assignment 05 – Population Analysis  (Jupyter Notebook)**
- **Assignment 06 – Knock Airport Weather Analysis (Jupyter Notebook)**

---

## Assignment 02 – Northern Ireland Bank Holidays  
**File:** `assignment02-bankholidays.py`  
A simple Python script that prints all official Northern Ireland bank holidays using basic `print()` statements.

---

## Assignment 03 – Email Domain Pie Chart  
**File:** `assignment03-pie.ipynb`  
Loads a CSV file of 1000 people, extracts email domains, counts occurrences, and displays the results in a pie chart.

Key skills:
- Reading CSV data  
- String splitting  
- Counting values (`value_counts()`)  
- Pie chart visualisation  

---

## Assignment 05 – Population Analysis   
**File:** `assignment05-population.ipynb`  
Dataset: CSO FY006A Population (2022)  
https://ws.cso.ie/public/api.restful/PxStat.Data.Cube_API.ReadDataset/FY006A/CSV/1.0/en

Completed tasks:
- Clean age labels (e.g., "Under 1 year", "100 years and over")  
- Convert age and population values to integers  
- Calculate weighted mean age for **Male** and **Female**  
- Compute population difference between sexes for each age  

---

## Assignment 06 – Knock Airport Weather Analysis  
**File:** `assignment_6_Weather.ipynb`  
Dataset: Met Éireann Knock Airport hourly weather  
https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv

Completed tasks:
- Plot hourly temperature  
- Plot daily mean temperature  
- Plot monthly mean temperature  



---

## References (Used across notebooks)

- Pandas Documentation: https://pandas.pydata.org/docs  
- Matplotlib Documentation: https://matplotlib.org/stable/contents.html  
- NumPy Weighted Average: https://numpy.org/doc/stable/reference/generated/numpy.average.html  
- CSO PxStat API (FY006A):  
https://ws.cso.ie/public/api.restful/PxStat.Data.Cube_API.ReadDataset/FY006A/CSV/1.0/en  
- Met Éireann Climate Data:  
https://cli.fusio.net/cli/climate_data/webdata/hly4935.csv  
- Lecturer "Weighted Stats" notebook (cleaning method reference)