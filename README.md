# Netflix Data Analysis

A project where I explored a Netflix dataset (Movies and TV Shows) from Kaggle to practice data cleaning, transformation, and visualization with pandas and seaborn.

## What I did

- Cleaned the dataset: handled missing values (filled some with "Unknown", dropped rows with very few nulls), removed duplicates, and fixed data types (converted `date_added` to an actual date)
- Split multi-value columns (`country` and `listed_in`) so each value could be counted properly instead of being grouped together as one messy string
- Explored a few questions:
  - How has the number of titles added to Netflix changed over the years?
  - What's the split between Movies and TV Shows?
  - Which countries produce the most content?
  - What are the most and least common genres?
- Visualized the findings with seaborn/matplotlib

## Some findings

- Titles added peaked in 2019, likely from Netflix expanding aggressively before COVID slowed down production
- Movies make up a much bigger chunk of the catalog than TV Shows, probably since they're a smaller time commitment to watch and produce
- The United States has the most titles by far, which makes sense given the reach of English-language content
- International Movies is the most common genre tag, showing Netflix's focus on broad, globally-appealing content

## Tools

- Python, pandas
- seaborn, matplotlib
- Jupyter Notebook

## Dataset

`netflix_titles.csv` is included in this repo. Originally from [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows).
