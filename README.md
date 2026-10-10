# 🎵 Spotify Tracks Exploratory Data Analysis (EDA)

This project features an Exploratory Data Analysis (EDA) and data cleaning pipeline on a Spotify track recommendation dataset using Python. The analysis aims to understand audio characteristics, popularity distributions, and relationships between various music features.

---

## 📊 Dataset Overview
* **Dimensions**: 4,999 rows and 19 columns[cite: 5].
* **Key Features**: Track metadata (`Track Name`, `Artist Name(s)`, `Album Name`, `Popularity`, `Artist Genres`) and audio parameters (`Danceability`, `Energy`, `Loudness`, `Valence`, `Tempo`, etc.)[cite: 5].
* **Initial Findings (Data Quality)**:
  * Identified missing values in specific columns such as `Artist Genres` (255 rows), `Danceability` (252 rows), and `Instrumentalness` (102 rows)[cite: 5].
  * Detected **13 duplicate rows** that require handling prior to modeling[cite: 5].

---

## 🛠️ Technologies & Libraries Used
* **Python** 
* **Pandas & NumPy** (Data manipulation and cleaning)
* **Matplotlib & Seaborn** (Data visualization and feature distribution plotting)

---

## 🚀 Features & Analysis Steps
1. **Data Loading & Inspection**: Loading the dataset and examining data types and missing values.
2. **Data Cleaning**: Handling missing values and removing duplicate records[cite: 5].
3. **Exploratory Data Analysis (EDA)**: 
   * Analyzing statistical distributions of audio features (such as *Danceability*, *Energy*, and *Tempo*)[cite: 5].
   * Visualizing variable distributions and correlations using histogram grids and heatmaps.

---

## 📂 Project Structure
```text
├── data/                    # Spotify dataset
├── eda_distributions.png    # Audio feature distribution visualization[cite: 5]
├── notebook.ipynb           # Main Jupyter Notebook for analysis
└── README.md                # Project documentation
