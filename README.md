# Ecommerce Clickstream & Purchase Analysis

This project analyzes over 100 million user interactions from a large multi-category ecommerce store. The data covers October and November 2019 and helped uncover key insights about customer buying habits, revenue trends, and which products drove the most sales.

## Highlights
- Combined two months of data to work with roughly 110 million events.
- Found that the `electronics.smartphone` category brought in the highest revenue by far.
- Spotted a big jump in mid-November sales, likely tied to early holiday promotions or a targeted campaign.
- Built daily revenue charts and ranked product categories to better understand what’s driving purchases.

## Tools Used
- **Python (pandas, matplotlib)** for cleaning, aggregating, and visualizing the data.
- **Tableau Public** to create an interactive dashboard.
- **SQLite** (optional) for running quick ad-hoc SQL queries on the cleaned dataset.

## Recommendations
- Double down on marketing for smartphones, since that’s already the top driver of revenue.
- Look into loyalty programs or bundle offers around best-selling electronics to keep customers coming back.
- Review the mid-November spike to figure out what worked so well and see if it can be repeated.

##  Project Files
- `/notebooks/ecommerce-eda.ipynb`: Jupyter notebook with all data cleaning and analysis steps.
- `/data/cleaned_data.csv`: cleaned dataset, ready for Tableau dashboards, SQL analysis, or further modeling.
