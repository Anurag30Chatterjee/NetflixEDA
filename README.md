# 🎬 Netflix Titles Exploratory Data Analysis (EDA)

## 📌 Overview

This project explores the Netflix Titles dataset using Python and Jupyter Notebook to uncover insights into content distribution, genre patterns, country presence, and production timelines. The dataset was sourced from Netflix's public catalogue and includes metadata about shows and movies available on the platform.

---

## 🗂️ Tools & Technologies

- **Language:** Python  
- **Notebook:** Jupyter  
- **Libraries:** Pandas, Matplotlib, Seaborn, WordCloud, Plotly  

---

## 📊 Dataset Details

- **Source:** Netflix public catalogue  
- **File:** `netflix_titles.csv`  
- **Total Records:** ~8800+  
- **Columns:** Show ID, Type (Movie/TV Show), Title, Director, Cast, Country, Release Year, Date Added, Duration, Rating, Description

---

## 🛠️ Project Workflow

1. **Data Loading & Overview**
   - Read CSV data into a DataFrame
   - Checked for nulls, duplicates, and inconsistencies

2. **Data Cleaning**
   - Converted date formats
   - Filled missing values in key fields
   - Separated duration into numerical and unit components

3. **Exploratory Data Analysis**
   - Distribution of movies vs TV shows
   - Year-wise content addition trend
   - Top genres and countries contributing to Netflix’s catalog
   - Ratings distribution across types
   - WordClouds for cast and description keywords

4. **Visualizations**
   - Bar plots, pie charts, line graphs, and word clouds to present trends effectively

---

## ❓ Key Questions Answered

- What is the breakdown between Movies and TV Shows on Netflix?
- Which years saw the most content added to the platform?
- What are the most common genres and ratings?
- Which countries contribute the most content?
- What are the typical durations of Movies and TV Shows?

---

## 📈 Summary of Insights

- **Content Type:** Movies constitute ~70% of the content; TV Shows ~30%  
- **Growth:** The peak content addition was in 2019-2020, indicating rapid growth  
- **Top Genres:** Dramas and Comedies are the most common genres  
- **Country Presence:** The United States leads in content volume, followed by India, UK, and Canada  
- **Ratings:** Most content is rated **TV-MA**, **TV-14**, and **R**  
- **Duration Trends:** Movies typically last 90–120 mins; TV Shows vary widely by season count  
- **Cast Appearances:** Recurrent cast members visible in WordClouds  

---

## ✅ Conclusion

This EDA offers a detailed understanding of Netflix’s content strategy and global distribution. By analyzing types, genres, and trends over the years, stakeholders can make informed decisions regarding content acquisition, user targeting, and marketing strategies.

---

## 📌 Future Scope

- Sentiment analysis on descriptions  
- Recommendation engine based on genre and metadata  
- Time-series analysis on content addition  
