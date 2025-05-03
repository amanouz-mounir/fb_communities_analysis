# 📊 Facebook100 Dataset Analysis

This repository provides an in-depth exploratory data analysis (EDA) of the **Facebook100** dataset through a Jupyter notebook: `fbProject.ipynb`. The study focuses on the structure and dynamics of early Facebook social networks as they existed in **2005**.

## 📌 Table of Contents

- [Background & Objective](#background--objective)
- [Notebook Overview](#notebook-overview)
- [Dataset](#dataset)
- [Installation & Requirements](#installation--requirements)

## 🧠 Background & Objective

Launched on February 4, 2004, at Harvard under the name *“thefacebook.com”*, Facebook rapidly expanded to over 800 U.S. colleges by September 2005, reaching more than 6 million users.

The **Facebook100** dataset offers an anonymized snapshot of this early era, capturing friendship networks within the first 100 colleges on Facebook. The dataset includes:

- Over **1.2 million users**
- Nearly **94 million undirected friendship edges**
- Rich metadata: user status (undergraduate, graduate, alumni, staff, etc.), gender, major, dormitory, and graduation year

**Objective**: Analyze and visualize the social network structures, study user demographics, and explore patterns of friendship formation and Facebook adoption across universities.

## 📒 Notebook Overview

The notebook includes:

- 📥 **Data Loading & Cleaning**  
  Import and preprocess Facebook100 data

- 📊 **Descriptive Analysis**  
  Explore attributes such as gender, major, status, dormitory, and graduation year

- 🔗 **Network Structure Analysis**  
  Study graph properties: density, degree distributions, and subgraph patterns per college

- 📈 **Visualizations**  
  Graph visualizations and attribute distribution plots

- 📉 **Adoption Trends**  
  Compare Facebook adoption rates to enrollment sizes across universities

- ⚠️ **Discussion**  
  Address data quality issues: missing values, duplicate or inactive users, and off-campus profiles

## 📂 Dataset

The [Facebook100 dataset](https://archive.org/details/oxford-2005-facebook-matrix) was originally compiled by researchers for network science research. It is publicly available and anonymized for privacy.

> ⚠️ You are responsible for respecting any data usage and privacy policies associated with the dataset.

## ⚙️ Installation & Requirements

You will need the following to run the notebook:

- Python 3.x
- Jupyter Notebook or JupyterLab

### Required Python Libraries

Install dependencies via pip:

```bash
pip install pandas numpy matplotlib seaborn networkx scikit-learn
