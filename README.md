# Netflix Content Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on Netflix's content catalog using Python and popular data analysis libraries.

The primary objective is to identify patterns, trends, and insights related to Netflix's content distribution, genre preferences, content ratings, country contributions, and catalog growth over time. Through data preprocessing, visualization, and analysis, the project aims to better understand how Netflix's content library is structured and how it has evolved.

---

## Objectives

The analysis focuses on answering the following business questions:

* What is the distribution of Movies vs TV Shows on Netflix?
* Which countries contribute the most content?
* What content ratings are most common?
* How has Netflix's content catalog grown over time?
* Which genres dominate the platform?
* How does Drama content compare to Documentary content?
* Which actors and directors appear most frequently in the catalog?

---

## Dataset Information

**Dataset:** Netflix Movies and TV Shows Dataset

* Total Records: 8,807
* Total Features: 12
* Source: Netflix Movies and TV Shows Dataset
* Data Coverage: Titles available on Netflix up to **2021**

### Dataset Limitation

This dataset contains Netflix content information only up to 2021. Therefore, all findings and insights represent historical trends and may not accurately reflect Netflix's current content catalog or business strategy.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Missing value analysis
* Handling null values
* Country data preprocessing
* Genre data preprocessing
* Multi-value column splitting and exploding
* Data consistency checks
* Basic feature engineering for analysis

---

## Analysis Performed

### Content Analysis

* Movies vs TV Shows distribution
* Content rating distribution

### Geographic Analysis

* Top content-producing countries

### Trend Analysis

* Release year distribution
* Content growth over time

### Genre Analysis

* Most common genres
* Drama vs Documentary comparison

### Creator Analysis

* Most frequently appearing actors
* Most frequently appearing directors

---

## Key Insights

* Movies significantly outnumber TV Shows in Netflix's catalog.
* The United States and India are among the largest contributors of content.
* TV-MA is one of the most common content ratings.
* Netflix experienced rapid content growth leading up to 2020.
* International Movies, Dramas, and Comedies are among the platform's most common genres.
* Drama content is considerably more prevalent than documentary content.
* A small group of actors and directors appear repeatedly across Netflix titles.

---

## Project Structure

```text
netflix-content-analysis/
│
├── data/
│   └── netflix_dataset.csv
│
├── notebooks/
│   └── netflix_content_analysis.ipynb
│
├── images/
│   └── visualizations
│
└── README.md
```

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Data Preprocessing
* Data Visualization
* Business Insight Generation
* Handling Multi-Valued Attributes
* Pandas Data Manipulation
* Analytical Thinking

---

## Future Improvements

* Build an interactive dashboard using Power BI or Streamlit
* Develop a content recommendation system
* Apply machine learning techniques for content trend prediction

---

## Author

Yash

This project was developed as part of a data science learning roadmap to strengthen practical skills in data analysis, visualization, and business insight generation.
