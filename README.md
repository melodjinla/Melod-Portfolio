Ecommerce Customer Behavior Analysis

This project analyzes over 100 million user interactions from a large multi-category ecommerce store. The data covers October and November 2019 and helped uncover key insights about customer buying habits, revenue trends, and which products drove the most sales.

Highlights
Combined two months of data to work with roughly 110 million events.

Found that the electronics.smartphone category brought in the highest revenue by far.

Spotted a big jump in mid-November sales, likely tied to early holiday promotions or a targeted campaign.

Built daily revenue charts and ranked product categories to better understand what’s driving purchases.

Tools used
Python (pandas, matplotlib) for cleaning, aggregating, and visualizing the data.

Excel to quickly pivot and slice parts of the cleaned dataset that were too large to comfortably handle in typical SQL databases or Power BI on a personal machine.

The original CSV is quite large (over 8GB), so all analysis was done in Python and Excel. No SQL or Power BI was used for this one due to size constraints.

Recommendations
Double down on marketing for smartphones, since that’s already the top driver of revenue.

Look into loyalty programs or bundle offers around best-selling electronics to keep customers coming back.

Review the mid-November spike to figure out what worked so well and see if it can be repeated.

Project files
/notebooks/ecommerce-eda.ipynb: Jupyter notebook with all data cleaning and analysis steps.

/data/cleaned_data.csv: cleaned dataset, ready for Excel exploration or further modeling (too large for direct use in SQLite or Power BI on a local machine).

