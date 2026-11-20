# Superstore Sales Analysis

An analysis of a US retailer's sales data (2015 to 2018) to find where it makes and loses money, when customers buy, and how discounts affect profit. Built with Python (Pandas, Matplotlib, Seaborn) in a Jupyter Notebook, and repeated in Excel.

## What the project does

- **Cleans the data.** The CSV contains three tables stacked together (Orders, People, Returns), so only the 9,994 order rows are kept. Dates are parsed and Year-Month is extracted.
- **Compares performance** by product category, region, and customer segment (sales, profit, margin).
- **Studies seasonality** with monthly sales trends and a calendar-month comparison.
- **Tests discount sensitivity** with a discount vs profit scatter plot and discount bands.
- **Summarizes the results** as executive takeaways.

## Key findings

- Sales grew 51% from 2015 to 2018 with a steady margin of about 12.5%.
- November and December make up 29.5% of sales; January and February only 6.7%.
- Furniture has a 2.5% margin versus about 17% for Technology and Office Supplies.
- Discounts above 20% turn lines unprofitable; those lines lost $135K combined.
- The Central region earns a 7.9% margin versus 14.9% in the West.

## Files

- `superstore_analysis.ipynb`: the full Python analysis with charts and takeaways
- `superstore_sales.csv`: the dataset
- `Superstore_Analysis.xlsx`: the Excel version

## Run it

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook superstore_analysis.ipynb
```

Keep the CSV in the same folder as the notebook.