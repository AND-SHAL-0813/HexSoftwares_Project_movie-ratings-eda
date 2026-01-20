# 🎬 Movie Analytics Dashboard

A Python-based data analysis project that cleans, processes, and visualizes movie datasets to uncover trends in ratings, genres, and top-performing films.

## 📌 Project Overview
This project provides an end-to-end pipeline for exploring movie data. It focuses on transforming raw, "dirty" data into a "tidy" format and generating a comprehensive analytics dashboard. The goal is to identify how user ratings (IMDb scores) are distributed across different genres and time periods.

### Key Features:
* **Data Preprocessing**: Handling missing values and correcting data types.
* **Statistical Analysis**: Calculating Central Tendency (Mean, Median, Mode).
* **Exploratory Data Visualization**: Distribution plots, Box plots, and Bar charts.
* **Interactive Analytics Dashboard**: A consolidated view of all key metrics using `Matplotlib` and `Seaborn`.

---

## 🛠️ Components & Workflow

### 1. Data Cleaning and Preprocessing
Ensures the dataset is reliable by:
* Removing rows with missing IMDb scores or release years.
* Converting variables to appropriate types (e.g., Year to `int`, Rating to `float`).
* Imputing missing genre information with "Unknown".

### 2. Summary Statistics
Provides a "bird's-eye view" of the data's central tendency.
* **Mean**: 6.42
* **Median**: 6.50
* **Mode**: 6.70

### 3. Data Visualization
Visualizes patterns like rating frequency and consistency across genres using histograms and box plots.

### 4. Top-Rated Movies & Genres
Identifies the "best" movies by filtering for credibility (minimum 500 votes) and ranks the highest-performing genres by average score.

---

## 📊 Dashboard Preview
The dashboard combines multiple visualizations into a single high-impact figure:
* **Overall Rating Distribution**: Shows the frequency of scores with a KDE curve.
* **Genre Performance**: Ranks genres by their mean IMDb rating.
* **Rating Consistency**: Box plots showing the spread and outliers within each genre.
* **Summary Metrics**: A textual panel for quick reference.

---

## 🚀 Getting Started

### Prerequisites
You will need Python 3.x and the following libraries:
```bash
pip install pandas numpy matplotlib seaborn
