# 🐧 Palmer Penguins Data Analysis with Pandas

This project explores the [Palmer Penguins dataset](https://github.com/allisonhorst/palmerpenguins) using Python and Pandas. It is a beginner-to-intermediate level data analysis project that demonstrates data cleaning, transformation, aggregation, feature engineering, reshaping, and ranking techniques.

---

## 📂 Dataset Overview

The dataset contains physical measurements for three penguin species observed on three islands in the Palmer Archipelago, Antarctica. The dataset includes:

- Species
- Island
- Bill length & depth
- Flipper length
- Body mass
- Sex
- Year

---

## 🛠 Features & Steps Covered

### ✅ 1. Load & Inspect
- Load data from a remote CSV
- Display initial rows and column names

### 🧹 2. Data Cleaning
- Renamed columns for clarity
- Dropped rows with missing values

### 📊 3. Descriptive Statistics & Grouping
- Computed average body mass by species
- Counted male vs female penguins per island

### ⚙ 4. Feature Engineering
- Added new column `bill_ratio` = bill_length / bill_depth
- Added `Average_body_mass` per species

### 🔍 5. Selection & Filtering
- Selected top 10 heaviest penguins
- Filtered penguins with above-average bill_ratio

### 🔢 6. Indexing Practice
- Used `.loc`, `.iat`, and `.at` to access specific rows/values

### 🔄 7. Pivot Table
- Created pivot table for average flipper length by species and island

### 🏆 8. Ranking
- Ranked penguins by body mass
- Reordered and reset index

### 📤 9. Export
- Saved the cleaned and enriched DataFrame as `Updated_DF.csv`

---

## 📌 Requirements

- Python 3.x
- pandas

Install dependencies:
```bash
pip install pandas
```

## 📜 License
Open-source and free to use for learning and practice.

## 🙌 Credits
Dataset: Palmer Penguins by Allison Horst

Analysis: By Prakash Chaudhary
