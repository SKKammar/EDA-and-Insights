# Zomato Restaurant Data — EDA and Insights

A data analysis project on the Zomato restaurant dataset. The goal was simple: stop guessing about what makes a restaurant successful on the platform and actually look at the numbers.

---

## What this project covers

I explored a dataset of ~9,500 restaurants listed on Zomato across multiple cities in India from Kaggle. After cleaning the data, I tried to answer five questions that felt genuinely interesting to me as someone looking at this from a business angle:

1. Which cities are dominating the platform — and is that a problem?
2. Do restaurants with online delivery actually get better ratings?
3. Does having table booking make a restaurant more popular?
4. What cuisines show up the most when you look past the combo strings?
5. How does price range actually translate to spend?

The answers were honestly more clear-cut than I expected.

---

## Key findings

- **Delhi NCR is 80%+ of the dataset.** New Delhi alone has 5,473 listings. The rest of the country barely registers — which is either an opportunity or a data collection problem, depending on how you look at it.
- **Online delivery correlates with higher ratings.** Delivery-enabled restaurants average 3.25 vs 2.46 — a 0.79-point gap that's hard to ignore.
- **Table booking restaurants get 3x more votes.** Whether that's because better restaurants offer booking, or because booking drives engagement, is worth digging into further.
- **About 25% of restaurants have no rating at all.** They show up as 0.0, which skews any aggregate stats if you're not careful.
- **Premium restaurants (Price Tier 4) cost nearly 3x more than Tier 3.** It's not a linear jump — there's a distinct high-end segment.

---

## Dataset

**Source:** [Zomato Restaurants Dataset — Kaggle](https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data)

The dataset contains restaurant listings with fields like city, cuisine type, average cost for two, price range tier, online delivery availability, table booking availability, aggregate rating, and total votes.

---

## How to run it

The notebook runs on Google Colab — no local setup needed.

1. Click the **Open in Colab** badge at the top of the notebook
2. Upload `zomato.csv` to the Colab file panel (the notebook checks for it automatically)
3. Run all cells top to bottom (`Runtime → Run all`)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SKKammar/EDA-and-Insights/blob/main/Project1EDAPlutoAcademy.ipynb)

---

## What's inside the notebook

| Section | What it does |
|---|---|
| Data Cleaning | Drops irrelevant columns, handles nulls, fixes type issues, flags unrated entries |
| EDA — 5 Questions | One cell per question, each with a clear output and a calculated metric |
| Visualizations | 6 chart types: bar, pie, histogram, line, scatter, heatmap |
| Insights Report | 5 data-backed observations written in plain English |

---

## Tech used

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## About

This is a Project about EDA and Insights — part of building a data analysis portfolio as I prepare for software engineering roles. More projects coming.

If you spot something wrong in the analysis or have a better way to approach one of the questions, feel free to open an issue. I'm still learning and genuinely curious.
