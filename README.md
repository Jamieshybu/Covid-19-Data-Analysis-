# COVID-19 Patient Data Analysis

## Overview

This project presents an Exploratory Data Analysis (EDA) of a COVID-19 patient dataset using Python in Jupyter Notebook. The analysis focuses on understanding patient demographics, medical conditions, and healthcare-related characteristics through statistical summaries and visualizations.

---

## Objectives

- Explore the COVID-19 patient dataset.
- Perform basic data cleaning.
- Analyze patient demographics and medical information.
- Visualize important patterns using charts and graphs.

---

## Dataset

The dataset contains information about COVID-19 patients, including:

- Sex
- Age
- Patient Type
- Medical Unit
- Date of Death
- Intubation Status
- Pneumonia
- Diabetes
- COPD
- Asthma
- Hypertension
- Obesity
- Tobacco Usage
- ICU Admission
- Other medical conditions

---

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## Data Preprocessing

The following preprocessing steps were performed:

- Checked for duplicate records
- Removed duplicate values
- Checked for missing values
- Examined dataset shape
- Verified data types
- Generated descriptive statistics

---

## Analysis Performed

- Dataset overview
- Summary statistics
- Gender distribution
- Patient type distribution
- Average age by gender using `groupby()`
- Frequency analysis using `value_counts()`

---

## Visualizations

The notebook includes the following visualizations:

- Histogram of Patient Age
- Scatter Plot (Age vs Medical Unit)
- Scatter Plot (Age vs Diabetes)
- Bar Chart of Gender Distribution
- Pie Chart of Gender Distribution
- Pie Chart of Patient Type Distribution
- Count Plot of Tobacco Usage
- Count Plot of Gender
- Line Plot of Age (First 100 Records)

---

## Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## Project Structure

```
COVID-19-Patient-Data-Analysis/
│
├── Covid 19 Analysis.ipynb
├── Covid Data.csv
├── README.md
└── images/
```

---

## Key Insights

- Examined the distribution of patients based on age and gender.
- Compared outpatient and hospitalized patient counts.
- Explored the relationship between age and selected medical conditions.
- Visualized tobacco usage among patients.
- Used statistical summaries and charts to better understand the dataset.

---

## Future Enhancements

- Perform advanced statistical analysis.
- Develop predictive machine learning models.
- Create an interactive dashboard using Power BI or Tableau.
- Analyze relationships between multiple health conditions.

---

## Author

**Jamie Shybu**

Integrated MCA Student
