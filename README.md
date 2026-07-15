# 🎬 TMDB Movie Analytics Dashboard

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![SQL](https://img.shields.io/badge/SQL-Data%20Modeling-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

This project presents an end-to-end Movie Analytics solution using the TMDB 5000 Movies Dataset.

The project combines **Python (Pandas)** for data cleaning and feature engineering with **Microsoft Power BI** for building an interactive Executive Dashboard.

The dashboard enables stakeholders to analyze movie performance, financial metrics, audience engagement, genres, and historical trends through interactive visualizations and KPI cards.

---

# 🎯 Business Problem

Movie production companies invest billions of dollars every year, but not every movie becomes commercially successful.

This project answers important business questions such as:

- Which movies generate the highest revenue?
- Which genres are the most profitable?
- Does a higher budget lead to higher revenue?
- How does audience popularity affect movie success?
- Which movies deliver the highest ROI?

---

# 🎯 Project Objectives

The objective of this project is to build an interactive Business Intelligence dashboard that helps users:

- Monitor financial performance
- Analyze movie profitability
- Explore audience engagement
- Identify high-performing genres
- Track movie trends over time
- Generate actionable business insights

---

# 📂 Dataset

**Dataset:** TMDB 5000 Movies Dataset

Dataset includes:

- Movie Title
- Budget
- Revenue
- Profit
- ROI
- Genres
- Popularity
- Ratings
- Vote Count
- Release Date
- Production Companies
- Production Countries
- Spoken Languages

**Total Movies:** **4,803**

---

# 🛠 Technologies Used

### Data Cleaning & Analysis

- Python
- Pandas
- NumPy

### Data Visualization

- Matplotlib
- Seaborn

### Business Intelligence

- Microsoft Power BI
- Power Query
- DAX

---

# 📁 Project Structure

```
TMDB-Movie-Analytics/

│
├── dashboard/
│   └── TMDB_Movie_Analytics.pbix
│
├── data/
│   ├── raw/
│   └── processed/
│
├── images/
│   └── dashboard.png
│
├── notebooks/
│   └── Data_Cleaning.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🔄 Project Workflow

## 1. Data Cleaning

- Removed unnecessary columns
- Handled missing values
- Processed JSON formatted columns
- Created cleaned dataset

---

## 2. Feature Engineering

Created new analytical features:

- Profit
- ROI
- Release Year
- Release Month
- Release Decade
- Cleaned Genres
- Production Countries
- Spoken Languages

---

## 3. Exploratory Data Analysis

Performed detailed analysis on:

- Revenue
- Budget
- Profit
- Ratings
- Popularity
- Genres
- ROI

---

## 4. Power BI Dashboard

Built a fully interactive Executive Dashboard including:

- KPI Cards
- Revenue Over Time
- Revenue by Genres
- Budget vs Revenue
- Average Rating Distribution
- Movies by Status
- Top 10 Movies by Revenue
- Top 10 Movies by Profit
- Interactive Slicers
- Quick Business Insights

---

# 📊 Dashboard Preview

![Dashboard](images/dashboard.png)

---

# 📈 Key Business Insights

- Adventure, Action, and Comedy generate the highest revenue.
- High-budget movies generally produce higher revenue.
- Average movie rating is approximately **6.1 / 10**.
- Released movies account for almost all records in the dataset.
- A small number of blockbuster movies contribute a significant share of total revenue.
- Several low-budget movies achieved exceptionally high ROI.

---

# 📌 Power BI Features

- Interactive Executive Dashboard
- KPI Cards
- DAX Measures
- Power Query Transformations
- Dynamic Slicers
- Cross Filtering
- Professional Sidebar Navigation
- Quick Insights Panel

---

# ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/TMDB-Movie-Analytics.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Open Jupyter Notebook

```bash
jupyter notebook
```

Open Power BI Dashboard

```
dashboard/TMDB_Movie_Analytics.pbix
```

---

# 📌 Project Status

✅ Data Cleaning Completed

✅ Feature Engineering Completed

✅ Exploratory Data Analysis Completed

✅ Power BI Executive Dashboard Completed

✅ Business Insights Generated

---

# 👨‍💻 Author

## Anees Rehman

Aspiring Data Analyst

**Skills**

- Python
- SQL
- Power BI
- Excel
- Pandas
- Data Visualization
- Business Intelligence

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.