# Netflix Data Analysis

A project where I explored a Netflix dataset (Movies and TV Shows) from Kaggle to practice data cleaning, transformation, and visualization using **pandas**, **matplotlib**, and **seaborn**.

## What I did

* Cleaned the dataset by handling missing values (filled some with `"Unknown"`, dropped rows with very few nulls), removed duplicates, and converted `date_added` to a datetime format.
* Split multi-value columns (`country` and `listed_in`) so each value could be counted individually instead of being grouped together as one string.
* Explored a few questions:

  * How has the number of titles added to Netflix changed over the years?
  * What's the split between Movies and TV Shows?
  * Which countries produce the most content?
  * What are the most and least common genres?
* Visualized the findings using **matplotlib** and **seaborn**.

## Some Findings

* Titles added peaked in **2019**, likely reflecting Netflix's rapid expansion before production slowed in the following years.
* Movies make up a much larger share of the catalog than TV Shows.
* The United States has the most titles by far, followed by India and the United Kingdom.
* International Movies is the most common genre tag, highlighting Netflix's focus on globally available content.

## Visualizations

### Titles Added Per Year

Shows how Netflix's catalog grew over time, with the highest number of titles added in **2019**.

![Titles Added Per Year](images/titles_added_per_year.png)

---

### Movies vs TV Shows

Compares the distribution of Movies and TV Shows in the Netflix catalog.

![Movies vs TV Shows](images/movie_vs_tv.png)

---

### Top 10 Content-Producing Countries

Displays the countries that contributed the most titles to the Netflix catalog.

![Top Countries](images/top_countries.png)

---

### Most Common Genres

Shows the most common genres after splitting titles with multiple genre labels.

![Top Genres](images/top_genres.png)

## Tools

* Python
* pandas
* matplotlib
* seaborn
* Jupyter Notebook

## Dataset

`netflix_titles.csv` is included in this repository.

Original dataset: **Netflix Movies and TV Shows** on Kaggle:

https://www.kaggle.com/datasets/shivamb/netflix-shows
