# 🏏 IPL Analysis Project

## 📌 Overview

This project provides a basic analysis of IPL match data using Python. The goal is to explore match trends, venue distributions, and team performances using simple EDA techniques.

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- pandas
- matplotlib

## 📁 Dataset Used

- **matches.csv** – Contains IPL match-level data such as:
  - Match ID
  - City
  - Date
  - Teams
  - Toss winner
  - Match winner
  - Player of the match
  - Venue

## 📊 Analysis Done

### ✅ Basic Match Info:
- Displayed first few rows of the dataset
- Checked shape, null values, and data types
- Displayed column names

### 📍 Venue & City Analysis:
- Counted total matches played in each city
- Counted total matches at each venue
- Visualized matches by city and venue using bar plots

### 🏆 Match Outcome Insights:
- Counted matches won by each team
- Bar chart showing most successful teams
- Analyzed toss winner vs match winner
- Counted how often teams win after winning the toss
- Checked the toss decision counts (bat or field)

### 👑 Player Awards:
- Counted most frequent "Player of the Match" award winners

### 📈 Visualizations:
- Bar plots using `matplotlib.pyplot` for:
  - Cities with most matches
  - Venues with most matches
  - Match wins by team
  - Toss win vs match win
  - Toss decision counts
  - Player of the match awards


