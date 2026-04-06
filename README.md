# Used Vehicle Pricing Analysis

**What actually drives the price of a used car?**

Ever wonder why two seemingly identical used cars are listed at completely different prices? The reasons behind the price difference is what this project aimed to explore. 

This project digs into a dataset of used vehicle listings to figure out which factors — mileage, age, make, condition, and more — have the biggest impact on price

---

## What's in this repo

```
├── data/                        # Used vehicle listings dataset
├── images/                      # Visualizations and plots
└── Vehicle_Price_Analysis_prompted.ipynb   # The main notebook
```

---

## Approach

The notebook walks through the full data science workflow:

1. **Data cleaning** — the raw dataset had missing values, outliers, and some listings that were clearly junk (free cars? $1 listings?). Filtering those out made a big difference.
2. **Exploratory analysis** — visualizing how price relates to mileage, year, manufacturer, condition, fuel type, and other features.
3. **Feature engineering** — encoding categorical variables and preparing the data for modeling.
4. **Modeling** — trying out a few regression approaches to see what predicts price best and which features matter most.
---

## What I found

A few things that stood out:

- **Mileage and vehicle age** are the strongest predictors of price, as expected — but the relationship isn't perfectly linear.
- **Manufacturer** matters a lot. Trucks and certain brands hold value significantly better than others.
- **Condition** has a surprisingly wide spread in how it impacts the price, which adds noise to the data.
- Some features that seem like they'd matter (cylinder count, paint color) ended up being less predictive than expected once other variables were controlled for.
---

## Tools used

Python, Jupyter Notebook, pandas, NumPy, matplotlib, seaborn, and scikit-learn.

---

## Background

This was part of the **UC Berkeley Extension Professional Certificate in Machine Learning & Artificial Intelligence**. The dataset is a used vehicle listings scrape covering listings across the US.
