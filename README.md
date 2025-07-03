# 📊 Descriptive Statistics & Correlation Analysis

This repository demonstrates essential techniques in descriptive statistics and correlation analysis using Python and Pandas.

---

## 1. Introduction

This notebook (`Descriptive_Stats-Correlation.ipynb`) aims to help you:
- Compute and interpret **descriptive statistics** (mean, median, standard deviation, percentiles).
- Visualize data distributions via **histograms**, **boxplots**, and **scatter plots**.
- Calculate and interpret **correlation coefficients** (Pearson, Spearman).
- Understand relationships and potential dependencies between variables.

---

## 2. Data Loading & Setup

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

# Load example dataset (e.g., COVID-19 data or any CSV file)
df = pd.read_csv('data/dataset.csv')
df.head()
