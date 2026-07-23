# CodeAlpha Superstore EDA

> **CodeAlpha Data Analytics Internship Project**

A production-quality Exploratory Data Analysis (EDA) of the Global Superstore Sales dataset, designed to surface actionable business intelligence through rigorous statistical analysis and professional data visualisation.

---

## Project Overview

This project examines transactional sales data from a fictional US-based retail superstore to answer key business questions around revenue performance, regional trends, category profitability, and shipping efficiency.

The analysis follows a structured, industry-standard EDA workflow and is documented to a standard suitable for direct portfolio publication.

---

## Repository Structure

```
codealpha-superstore-eda/
├── CodeAlpha_Superstore_EDA.ipynb   # Main analysis notebook
├── train.csv                        # Source dataset (9,800 rows × 18 columns)
├── requirements.txt                 # Python dependencies
├── .gitignore                       # Git exclusions
└── README.md                        # This file
```

---

## Dataset

| Attribute | Value |
|---|---|
| Source | Global Superstore Sales Dataset |
| Rows | 9,800 |
| Columns | 18 |
| Date Range | 2014 – 2017 |
| Key Fields | Order Date, Ship Date, Category, Segment, Region, Sales |

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.11 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Static visualisation |
| Seaborn | Statistical visualisation |
| Plotly | Interactive charts |
| SciPy | Statistical testing |
| Jupyter Notebook | Interactive analysis environment |

---

## Notebook Sections

1. Introduction
2. Business Problem
3. Dataset Overview
4. Data Loading & Initial Inspection
5. Data Cleaning
6. Feature Engineering
7. Univariate Analysis
8. Bivariate Analysis
9. Multivariate Analysis
10. Time Series Analysis
11. Correlation Analysis
12. Outlier Detection
13. Business Insights
14. Recommendations
15. Conclusion

---

## Key Questions Answered

- Which product categories and sub-categories drive the most revenue?
- How does sales performance vary by region and customer segment?
- What are the seasonal and yearly revenue trends?
- Which shipping modes are most frequently used?
- Are there significant outliers in sales that require attention?

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/<your-username>/CodeAlpha_Superstore_EDA.git
cd CodeAlpha_Superstore_EDA

# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch the notebook
jupyter notebook CodeAlpha_Superstore_EDA.ipynb
```

---

## Author

**Lalit** — CodeAlpha Data Analytics Intern

---

## License

This project is for educational and portfolio purposes.
