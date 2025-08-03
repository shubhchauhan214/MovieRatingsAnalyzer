# 🎬 Movie Ratings Analyzer – NumPy + Matplotlib Project

This project simulates a dataset of 1000 movies with various attributes (genre, release year, duration, user rating) and performs analysis using **NumPy** and visualization using **Matplotlib**.

---

## 📌 Project Objective

- Generate a synthetic movie dataset using NumPy
- Analyze ratings, genres, and trends
- Visualize data using multiple Matplotlib plots
- Understand boolean masking, bins, z-order, alpha, and layout handling

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- Jupyter Notebook (for development)

---

## 📁 Dataset Fields

| Column         | Description                              |
|----------------|------------------------------------------|
| `movie_id`     | Unique ID from 1 to 1000                 |
| `genre`        | Randomly assigned from 6 genres          |
| `release_year` | Between 2000 and 2025                    |
| `duration_mins`| Duration of the movie in minutes         |
| `user_rating`  | User rating (1.0 to 5.0, 1 decimal place)|

---

## 🔍 Features Covered

### ✅ NumPy
- Array creation
- Random data generation
- Boolean masking
- Aggregations: `mean`, `min`, `max`, `median`
- Unique value counts
- Year-wise and Genre-wise filtering and analysis

### ✅ Matplotlib
- Bar chart with z-order control
- Line plot with time trends
- Histogram with bin size discussion
- Boxplot for distribution summary
- Grid, alpha (transparency), and layout handling
- Saving plots using `plt.savefig()`

---

