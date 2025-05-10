# Marvel Heroes & Villains Analysis 🦸‍♂️🦹‍♀️
This repository contains an Exploratory Data Analysis (EDA) of a subset of characters from the Marvel Universe. The analysis focuses on character roles, affiliations, and powers to uncover patterns and insights in the dataset.

## 📌 Introduction

This project analyzes a dataset of 45 Marvel characters, each described by the following attributes:

- `Character`
- `Real Name`
- `Affiliation`
- `Powers`
- `Role` (Hero, Villain, Antihero)
- `Power Level`

The goal is to explore the relationships between these attributes, especially focusing on the distribution of roles and the prevalence of specific powers among characters.

## 🧾 Dataset Overview

- **Total Rows**: 45  
- **Columns**: 6  
- **Missing Values**: None  

### Key Statistics:
- Unique characters: 44 (Black Widow appears twice)
- Unique real names: 41 (Carol Danvers appears twice)
- Most common role: **Hero** (35 characters)
- Most common affiliation: **Avengers** (23 characters)
- All characters have a power level of **Low**

## 📊 Visualizations & Findings

### 🦸 Role Distribution
- **Insight**: The dataset is hero-dominated:  
  - Heroes: 35  
  - Villains: 8  
  - Antiheroes: 2  
- **Visualization**: Bar plot displaying character count by role.
- **Interpretation**: Reflects Marvel's narrative emphasis on heroes.

### ⚡ Powers Analysis
- **Insight**: Certain powers are consistently popular among characters.
- **Visualization**: Bar plot showing the most frequently appearing powers.
- **Interpretation**: Powers like superhuman strength appear across many heroes and villains, showing recurring themes in character design.

## 🚀 Future Work

- Further explore affiliations (e.g., group distribution like Avengers, X-Men).
- Build a machine learning model to predict roles based on powers or affiliations.
- Perform a network analysis to visualize relationships and team dynamics.

## ✅ Conclusion

This analysis revealed that the Marvel Universe in this dataset is highly centered around heroes, with common traits and superpowers recurring among characters. It lays the foundation for deeper analysis, including predictive modeling and character network mapping.

## 📂 Project Structure

- `marvel_analysis.ipynb`: Main notebook containing all EDA, visualizations, and insights.
- `dataset.csv`: Cleaned dataset used in the notebook (if publicly shared).
- Visualizations are embedded directly in the notebook.

## 📎 View the Full Notebook on Kaggle

👉 [Marvel Heroes vs Villains Analysis on Kaggle](https://www.kaggle.com/code/busradeveci/marvel-heroes-villains-analysis)

## 🧠 Technologies Used
- Python
- Pandas
- Matplotlib & Seaborn
- Plotly
- Jupyter Notebook
