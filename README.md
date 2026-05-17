# 🎬 Netflix Content Analysis

Exploratory data analysis of Netflix movies and TV shows using Python and Pandas — uncovering content trends, ratings distribution, and global production patterns.

---

## 📌 Project Overview

This project analyses the [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) from Kaggle containing 8000+ titles available on Netflix. The goal was to extract meaningful insights about Netflix's content strategy and trends.

---

## 🛠️ Tech Stack

- **Python** — Pandas, NumPy, Matplotlib
- **Jupyter Notebook** — Analysis environment

---

## 📂 Dataset

| Column | Description |
|---|---|
| `show_id` | Unique ID for each title |
| `type` | Movie or TV Show |
| `title` | Name of the title |
| `director` | Director name |
| `cast` | Main cast |
| `country` | Country of production |
| `date_added` | Date added to Netflix |
| `release_year` | Year of release |
| `rating` | Content rating (PG, R, TV-MA etc.) |
| `duration` | Duration in minutes or seasons |
| `listed_in` | Genre/category |

---

## 🔍 Key Analyses

### 1. 🎥 Movies vs TV Shows Distribution
- Compared count of Movies vs TV Shows on Netflix
- Found what type of content Netflix focuses on more

### 2. 📅 Content Added Over the Years
- Tracked how Netflix's library grew year by year
- Identified peak years of content addition

### 3. 🌍 Top Countries by Content Production
- Analysed which countries produce the most Netflix content
- USA, India, UK dominate the production landscape

### 4. ⭐ Content Ratings Distribution
- Breakdown of content by rating (TV-MA, TV-14, PG-13 etc.)
- Shows Netflix's target audience demographic

---

## 🧹 Data Cleaning

| Issue | Fix |
|---|---|
| Null values in `director`, `cast`, `country` | Filled with `'Unknown'` |
| Null `date_added` values | Dropped rows |
| Wrong data types on date columns | Converted to datetime |
| Inconsistent duration format | Separated into numeric + unit |

---

## 📊 Key Findings

| Analysis | Insight |
|---|---|
| Content Type | 70% Movies, 30% TV Shows |
| Peak Year | 2019 had the highest content additions |
| Top Country | USA produces the most Netflix content |
| Top Rating | TV-MA is the most common rating |

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/KavishTomar4/Netflix-Analysis.git
cd Netflix-Analysis
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib
```

3. Run the notebook
```bash
jupyter notebook netflix_analysis.ipynb
```

---

## 📁 Project Structure

```
Netflix-Analysis/
│
├── netflix_analysis.ipynb    # Main analysis notebook
├── netflix_titles.csv        # Dataset
└── README.md                 # Project documentation
```

---

## 💡 Conclusion

> Netflix heavily focuses on Movies over TV Shows. Content additions peaked around 2019 before slowing down. The US dominates production, but India is rapidly growing as a content hub. Most content is rated TV-MA suggesting Netflix targets adult audiences.

---

## 👤 Author

**Kavish Tomar**
[GitHub](https://github.com/KavishTomar4)
