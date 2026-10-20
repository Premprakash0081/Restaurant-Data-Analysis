# Restaurant Data Analysis | Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project explores restaurant data using Python to identify cuisine trends, analyze city-wise restaurant distribution and ratings, understand restaurant price ranges, and evaluate the relationship between online delivery availability and aggregate ratings.

The goal is to transform raw restaurant data into meaningful insights that can support data-driven business decisions.

## 🎯 Project Objectives

- Identify the three most frequently listed cuisines.
- Analyze restaurant distribution across cities.
- Identify cities with the highest average restaurant ratings.
- Examine the distribution of restaurants across price ranges.
- Analyze online delivery availability.
- Compare average ratings of restaurants with and without online delivery.

## 🛠️ Tools & Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data cleaning, aggregation, and analysis
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive analysis and documentation

## 📂 Project Structure

Restaurant-Data-Analysis/
│
├── Restaurant_Data_Analysis.ipynb
├── Dataset.csv
└── README.md
```

*Note: Include `Dataset.csv` only if you are permitted to redistribute the dataset.*

## 🔍 Analysis & Key Findings

### 1. Cuisine Analysis

- Identified the top three cuisines: North Indian, Chinese, and Fast Food.
- North Indian cuisine represented approximately 41.50% of the restaurant records.
- Chinese cuisine represented approximately 28.66%.
- Fast Food represented approximately 20.81%.

**Business insight:** These cuisines are prominent in the analyzed restaurant listings and can help identify areas of strong restaurant presence.

### 2. City-wise Restaurant & Rating Analysis

- Analyzed the number of restaurants in different cities.
- Identified New Delhi as the largest market in the dataset, with 5,473 restaurant listings.
- Compared average aggregate ratings across cities.
- Identified Inner City with an average rating of 4.90 in the notebook's results.

**Business insight:** Restaurant count and average rating offer two different perspectives: market presence and customer-rated performance. Both should be considered when comparing potential markets.

### 3. Price Range Distribution

- Calculated restaurant counts across price range categories.
- Calculated the percentage distribution of restaurants by price range.
- Visualized the distribution to understand how restaurants are positioned across the available pricing categories.

**Business insight:** Price-range distribution helps describe the market's pricing structure and can support further analysis of affordability and restaurant positioning.

### 4. Online Delivery Analysis

- Analyzed the proportion of restaurants offering online delivery.
- Compared aggregate ratings for restaurants with and without online delivery.
- Observed the following average ratings in the notebook:

| Online delivery | Average rating |
|---|---:|
| Available | 3.25 |
| Not available | 2.46 |

**Business insight:** Restaurants offering online delivery had higher average ratings in this dataset. This is an association, not proof that online delivery causes higher ratings.

## 🧹 Data Cleaning & Methodology

The analysis includes the following steps:

1. Loaded the restaurant dataset using Pandas.
2. Identified missing values in the `Cuisines` column.
3. Removed 9 records with missing cuisine information for cuisine analysis.
4. Split cuisine entries containing multiple cuisines.
5. Counted cuisine occurrences and calculated percentages.
6. Grouped records by city to calculate restaurant counts and average ratings.
7. Calculated price range distributions and online delivery proportions.
8. Created charts to communicate the results.

## 📊 Skills Demonstrated

- Data cleaning and preprocessing
- Handling missing values
- String splitting and data transformation
- Exploratory Data Analysis (EDA)
- GroupBy and aggregation
- Frequency and percentage calculations
- Comparative analysis
- Data visualization
- Business insight generation

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, then install the required libraries:

```bash
pip install pandas matplotlib notebook
```

### Run locally

1. Clone or download this repository.
2. Place the dataset in the project directory, if permitted.
3. Update the notebook's CSV path to a relative path:

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv("Dataset.csv")
```

4. Open `Restaurant_Data_Analysis.ipynb` in Jupyter Notebook.
5. Run the notebook cells sequentially to reproduce the analysis.

## 🔮 Future Improvements

- Add more detailed data-quality checks and validation.
- Investigate rating distributions and restaurant counts across cities.
- Compare price ranges with ratings and online delivery availability.
- Build an interactive dashboard using Power BI or Plotly.
- Develop more detailed visualizations for business reporting.
- Add automated summary tables and key performance indicators.

## 📝 Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow using Python, from data cleaning and transformation to visualization and interpretation.

The analysis highlights cuisine patterns, city-level restaurant distribution, pricing categories, and differences in ratings based on online delivery availability.

It serves as a practical demonstration of foundational data analytics skills and provides a basis for more advanced restaurant market analysis.

---

**Project Type:** Exploratory Data Analysis (EDA)  
**Domain:** Restaurant & Business Analytics  
**Status:** Completed

**Author:** Prem Prakash Singh
