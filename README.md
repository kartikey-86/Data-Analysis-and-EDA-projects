# TMDB Movies Data Analysis & EDA Projects

Welcome to my portfolio of data analysis and exploratory data analysis (EDA) projects! This repository demonstrates my analytical skills and proficiency with essential tools for data analysts, including **Python**, **SQL**, **Power BI**, and more. Here, I work with a dataset of 9,000+ movies extracted from the TMDB API, showcasing how to turn raw data into actionable insights.

---

## 📊 Project Overview

This project analyzes a rich movie dataset from TMDB, exploring patterns in genres, popularity, votes, release years, and more. The workflow covers data wrangling, cleaning, visualization, and interpretation of key findings.

### Dataset Description

- **Source:** [Kaggle TMDB Movies Dataset](https://www.kaggle.com/)
- **Rows:** 9,827
- **Columns:** 9 (after cleaning: 6 columns, 25,551 rows due to genre explosion)
- **File:** `mymoviedb.csv`

#### Columns

- **Release_Date:** Movie release date (cast to year for analysis)
- **Title:** Movie name
- **Overview:** Brief summary (dropped during analysis)
- **Popularity:** TMDB-computed metric (views, votes, favorites, watchlist)
- **Vote_Count:** Total votes received
- **Vote_Average:** Average rating (out of 10)
- **Original_Language:** Original language (dropped during analysis)
- **Genre:** Categories (cleaned and categorized)
- **Poster_Url:** URL of the movie poster (dropped during analysis)

---

## 🔍 EDA Questions Explored

1. **What is the most frequent genre in the dataset?**
2. **Which genres have the highest votes?**
3. **Which movie got the highest popularity? What's its genre?**
4. **Which year saw the most movies filmed?**

---

## 🧹 Data Wrangling & Cleaning

- Dropped irrelevant columns (`Overview`, `Original_Language`, `Poster_Url`)
- Casted `Release_Date` to year format
- Handled outliers in `Popularity`
- Categorized `Vote_Average`
- Cleaned and exploded `Genre` column (comma-separated values)
- Ensured no NaNs or duplicates

---

## 📈 Data Visualization

Utilized **Matplotlib** and **Seaborn** to generate insightful visualizations, such as:
- Genre frequency charts
- Popularity and votes by genre
- Yearly movie release trends

---

## 📝 Key Insights

- **Drama** is the most frequent genre (appears in >14% of movies).
- Drama also receives the highest votes and popularity (>18.5%).
- **Spider-Man: No Way Home** is the most popular movie (genres: Action, Adventure, Science Fiction).
- **2020** was the peak year for movie releases.

---

## 🛠 Built With

- **Python 3** (pandas, numpy)
- **JupyterLab** (interactive notebooks)
- **Matplotlib** & **Seaborn** (visualization)
- **SQL** (for data extraction and querying)
- **Power BI** (for dashboarding and advanced visualizations)
- **Excel** (supplementary analysis)

---

## 🚀 About Me

I’m Kartikey, a passionate data analyst with experience in Python, SQL, Power BI, and other core tools. This repo is a showcase of my analytical workflow and ability to uncover insights from complex datasets.

---

Feel free to explore, fork, or connect for collaboration and feedback!