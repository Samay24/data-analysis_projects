# 🎬 Netflix Data Visualization Project

## 📌 Overview

This project analyzes and visualizes Netflix dataset using Python. It covers exploratory data analysis (EDA) to understand the structure of the dataset and creates visual insights related to release years, content types, and countries using pandas and matplotlib.

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib.pyplot

## 📁 Dataset Description

The dataset contains information about Netflix content including:

- `show_id`: Unique ID for each show
- `type`: Type of content (Movie or TV Show)
- `title`: Title of the show
- `director`, `cast`: Names of directors and actors
- `country`: Country of production
- `date_added`: When the show was added to Netflix
- `release_year`: Release year of the show
- `rating`: Age rating
- `duration`: Duration of the content
- `listed_in`: Genre categories
- `description`: Summary of the show

## 🔍 Steps & Analysis Done

### ✅ Data Preprocessing
- Loaded CSV file using `pandas.read_csv()`
- Displayed dataset using `head()` and `info()`
- Checked null values using `isnull().sum()`
- Dropped rows with missing values using `dropna()`
- Verified data types and column structure

### 📊 Visualizations Created
1. **Bar Chart – Content Type Distribution**
   - Shows count of Movies vs TV Shows

2. **Bar Chart – Top 20 Countries**
   - Countries producing the most Netflix content

3. **Bar Chart – Number of Releases per Year**
   - Release year trend of content on Netflix

4. **Bar Chart – Content Type by Year**
   - Compared number of Movies and TV Shows over different years

## ✅ Insights
- **Movies** are more frequent than TV Shows on Netflix.
- **United States**, **India**, and **United Kingdom** contribute the most content.
- Content releases have increased steadily over the years.
- The number of TV shows is lower but has grown over time.


