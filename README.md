# Day4_DataScience_Bootcamp

# 🎵 Spotify Tracks Dataset – Exploratory Data Analysis & Data Visualization

## 📌 Project Overview

This project was completed as part of **Epochs '26 – Assignment 4**. The objective was to perform **Exploratory Data Analysis (EDA)** and create meaningful visualizations using **Matplotlib** and **Seaborn** to uncover patterns, trends, and relationships within the Spotify Tracks Dataset.

The focus of this assignment is not only to create charts but also to communicate insights through effective **data storytelling**.

---

# 📂 Dataset

**Dataset:** Spotify Tracks Dataset

The dataset contains detailed information about Spotify tracks, including:

* Artist
* Album
* Track Name
* Popularity
* Duration
* Explicit Content
* Danceability
* Energy
* Loudness
* Speechiness
* Acousticness
* Instrumentalness
* Liveness
* Valence
* Tempo
* Genre

These audio features help describe the characteristics of songs and allow for meaningful analysis.

---

# 🎯 Objectives

* Explore the dataset and understand its structure.
* Identify numerical and categorical features.
* Perform descriptive statistical analysis.
* Detect missing values and duplicate records.
* Analyze relationships between different audio features.
* Create meaningful visualizations using Matplotlib and Seaborn.
* Present insights through effective data storytelling.

---

# 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset overview
* Data type inspection
* Descriptive statistics
* Missing value analysis
* Duplicate record detection
* Numerical feature analysis
* Categorical feature analysis
* Correlation analysis

---

# 📊 Visualizations Created

The following visualizations were developed as part of this project:

1. **Top Spotify Genres (Bar Chart)**

   * Displays the most frequent music genres in the dataset.

2. **Popularity Distribution (Histogram)**

   * Shows how song popularity is distributed.

3. **Explicit vs Non-Explicit Songs (Count Plot)**

   * Compares explicit and non-explicit tracks.

4. **Danceability vs Popularity (Scatter Plot)**

   * Explores the relationship between danceability and popularity.

5. **Energy Distribution (Box Plot)**

   * Highlights the spread of energy values and potential outliers.

6. **Correlation Heatmap**

   * Displays relationships among numerical audio features.

7. **Top Artists (Bar Chart)**

   * Identifies artists with the highest number of tracks.

8. **Loudness Distribution (Histogram)**

   * Examines the distribution of loudness values.

9. **Tempo Distribution (Histogram)**

   * Visualizes the spread of song tempos.

10. **Average Popularity by Genre (Bar Chart)**

    * Compares the average popularity across different music genres.

---

# 🖼️ Visualization Images

Store all generated visualization images inside the `images/` folder.

Example:

```text
images/
│
├── genre_distribution.png
├── popularity_distribution.png
├── explicit_songs.png
├── danceability_vs_popularity.png
├── energy_boxplot.png
├── correlation_heatmap.png
├── top_artists.png
├── loudness_distribution.png
├── tempo_distribution.png
└── popularity_by_genre.png
```

---

# 💡 Key Insights

### 🎵 Genre Distribution

Only a small number of genres dominate the dataset, while many genres contain comparatively fewer tracks.

### ⭐ Popularity Distribution

Most tracks have moderate popularity, whereas highly popular songs represent a smaller portion of the dataset.

### 🚫 Explicit Content

Non-explicit tracks are more common than explicit tracks.

### 💃 Danceability vs Popularity

Danceability alone does not determine whether a song becomes popular.

### ⚡ Energy Analysis

Most songs exhibit moderate to high energy levels, with a few low-energy outliers.

### 🔥 Correlation Analysis

Certain audio features, such as energy and loudness, show positive relationships, while others have weaker or negative correlations.

### 🎤 Artist Analysis

A relatively small number of artists contribute a large share of tracks in the dataset.

### 🎼 Loudness & Tempo

Most songs fall within common loudness and tempo ranges, indicating consistent production characteristics across many tracks.

### 📈 Popular Genres

Some genres consistently achieve higher average popularity than others.

---

# 📌 Overall Conclusions

This exploratory analysis provides valuable insights into Spotify music characteristics and listening trends. The visualizations reveal patterns in popularity, genre distribution, artist contributions, and relationships among audio features.

These findings can support future machine learning tasks such as music recommendation, genre classification, popularity prediction, and playlist generation.

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📁 Repository Structure

```text
Day4_DataVisualization/
│
├── visualization.ipynb
├── dataset.csv
├── README.md
├── requirements.txt
└── images/
    ├── genre_distribution.png
    ├── popularity_distribution.png
    ├── explicit_songs.png
    ├── danceability_vs_popularity.png
    ├── energy_boxplot.png
    ├── correlation_heatmap.png
    ├── top_artists.png
    ├── loudness_distribution.png
    ├── tempo_distribution.png
    └── popularity_by_genre.png
```

---

# 🚀 How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/Day4_DataVisualization.git
```

2. Navigate to the project directory.

```bash
cd Day4_DataVisualization
```

3. Install the required dependencies.

```bash
pip install -r requirements.txt
```

4. Launch Jupyter Notebook.

```bash
jupyter notebook
```

5. Open `visualization.ipynb` and run all cells to reproduce the analysis and visualizations.

---

# 📌 Assignment Details

**Program:** Epochs '26

**Assignment:** Day 4 – Exploratory Data Analysis & Data Visualization

### Deliverables

* ✅ `visualization.ipynb`
* ✅ `README.md`
* ✅ Visualization Images
* ✅ GitHub Repository

---

# 👨‍💻 Author

**ASIF HUSSAIN**

Completed as part of the **Epochs '26 Data Science Bootcamp**.
