# Data Analysis Projects 🧮

## Overview  
This repository contains the **Data Analysis Final Project**, where I perform a complete end‑to‑end data analysis workflow: from data cleaning and exploratory data analysis (EDA) to visualization, modelling, and interpretation of results.  
It showcases my skills in Python, Pandas, visualisation libraries and machine‑learning fundamentals.

## Key Steps  
- **Data Loading & Cleaning**: handle missing values, outliers, type conversions.  
- **Exploratory Data Analysis (EDA)**: use descriptive statistics, scatter plots, boxplots, group‑by operations, pivot tables, and heatmaps to uncover patterns.  
- **Feature Engineering**: generate relevant features, encode categorical variables, scale numeric data.  
- **Modelling**: apply regression (linear, polynomial) or clustering (K‑Means) where appropriate, evaluate model performance (MSE, R², cross‑validation) and refine.  
- **Visualization & Insights**: present findings with clear, interpretable plots and figures.

## Technologies & Tools  
- Python (Pandas, NumPy)  
- Data visualisation: Matplotlib, Seaborn  
- Machine learning: Scikit‑Learn  
- Jupyter Notebook for interactive workflow  
- GitHub for version control

## Example Visualisation  
<img width="616" height="470" alt="image" src="https://github.com/user-attachments/assets/5f51e0e0-4ee1-45b6-80c3-51188bc81024" />

<img width="624" height="478" alt="image" src="https://github.com/user-attachments/assets/5e369218-2864-4680-9b7b-11efd6a29c3b" />


```python
import seaborn as sns
import matplotlib.pyplot as plt

corr = df.corr()
plt.figure(figsize=(10,8))
sns.heatmap(corr, annot=True, fmt=".2f", cmap="coolwarm")
plt.title("Feature Correlation Heatmap")
plt.show()
