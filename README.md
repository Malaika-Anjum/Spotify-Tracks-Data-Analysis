# Spotify Tracks Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Spotify Tracks Dataset using Python. The objective is to clean the dataset, explore its characteristics, analyze relationships between audio features, and visualize insights using NumPy, Pandas, Matplotlib, and Seaborn.

---

## Dataset

The dataset contains thousands of Spotify tracks along with various musical features such as:

- Track Name
- Artist
- Album Name
- Genre
- Popularity
- Duration
- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Explicit Content
- Key
- Mode
- Time Signature

---

## Project Structure

```
Spotify-Track-Analysis
│
├── data
│   ├── spotify.csv
│   └── spotify_cleaned.csv
│
├── notebook
│   └── analysis.ipynb
│
├── images
│   ├── correlation_heatmap.png
│   ├── popularity_distribution.png
│   ├── genre_distribution.png
│   ├── energy_vs_popularity.png
│   ├── boxplot_popularity.png
│   └── ...
│
├── README.md
└── requirements.txt
```

---

## Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## Data Cleaning

The following preprocessing steps were performed:

- Checked dataset dimensions
- Inspected data types
- Identified missing values
- Removed duplicate records
- Renamed columns (if required)
- Converted duration from milliseconds to minutes
- Removed unnecessary columns
- Exported cleaned dataset

---

## Exploratory Data Analysis

The project includes:

- Dataset overview
- Summary statistics
- Missing value analysis
- Duplicate detection
- Correlation analysis
- Genre analysis
- Artist analysis
- Popularity analysis
- Audio feature analysis

---

## Visualizations

The following visualizations were created:

- Missing Values Heatmap
- Correlation Heatmap
- Histogram
- Count Plot
- Bar Plot
- Box Plot
- Violin Plot
- Scatter Plot
- Pair Plot
- Regression Plot

---

## Pandas Operations Used

- head()
- tail()
- info()
- describe()
- shape
- columns
- isnull()
- duplicated()
- drop_duplicates()
- fillna()
- groupby()
- agg()
- pivot_table()
- value_counts()
- sort_values()
- corr()
- to_csv()

---

## Key Insights

Some important findings include:

- Distribution of songs across different genres.
- Relationship between popularity and audio features.
- Correlation between energy, loudness, and danceability.
- Most common artists in the dataset.
- Distribution of song durations.
- Comparison of explicit and non-explicit tracks.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Statistical Analysis
- Correlation Analysis
- Feature Engineering
- Pandas Data Manipulation
- NumPy Operations

---

## Future Improvements

- Interactive dashboards using Plotly
- Machine Learning models for popularity prediction
- Genre classification
- Recommendation system
- Time-series analysis of music trends

---

## How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/Spotify-Track-Analysis.git
```

Navigate to the project

```bash
cd Spotify-Track-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

Open

```
notebook/analysis.ipynb
