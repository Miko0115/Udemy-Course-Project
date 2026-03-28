# Udemy Course Data — Exploratory Data Analysis

An EDA of ~13,600 Udemy business courses, exploring pricing, ratings, subscriber patterns, and growth trends.

## Dataset

The dataset contains 13,608 Udemy courses with details like price, rating, number of subscribers, reviews, and publish date. Prices are in INR.

**Source:** [Udemy Course Dataset on Google Drive](https://drive.google.com/uc?id=1rqn_eoGU0aN8QC-xK_s4xZ99pgwV1koF)

Download the CSV and place it in the project root as `udemy.csv` before running the notebook.

## Key Findings

- Udemy discounts heavily — median discount is ~86%, so list prices are mostly meaningless
- Rating doesn't strongly correlate with subscriber count
- Higher-priced courses don't have fewer subscribers — pricing alone doesn't determine popularity
- Course publishing grew steadily from 2015 to 2020
- ~96% of courses are paid, with very few free offerings

## Setup

```bash
pip install -r requirements.txt
```

Then open `Udemy Course Data.ipynb` and run all cells.
