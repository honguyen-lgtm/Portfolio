# Grocery Price Comparison & Receipt Processing

## Project Overview

This project uses Python to extract, clean, and analyze grocery pricing data from sample receipts across five grocery stores.

The goal was to reduce manual data entry, organize grocery prices into a structured Excel dataset, and identify which store offered the lowest total cost for a selected grocery basket.

**Note:** This project uses fictional receipts created for learning and demonstration purposes.

## Tools & Technologies

- **Python:** Data processing and workflow development
- **Pandas:** Data cleaning, manipulation, and analysis
- **EasyOCR:** Extracting text from receipt images
- **Microsoft Excel:** Storing and organizing grocery pricing data
- **Matplotlib:** Creating data visualizations
- **Google Colab:** Developing and executing Python code
- **Google Drive:** Storing input receipts and output files

## Project Workflow

1. Uploaded sample grocery receipts to a Google Drive Input folder.
2. Used EasyOCR to extract product names and prices from receipt images.
3. Cleaned and structured extracted data using Pandas.
4. Implemented receipt-level duplicate detection to help prevent repeated imports.
5. Updated an Excel dataset with approved receipt records.
6. Calculated grocery basket costs across five stores.
7. Created a horizontal bar chart to visualize price differences.

The workflow is partially automated. The Python script requires manual execution in Google Colab and review of extracted data before saving.

## Dataset

The dataset contains:

- 5 grocery stores
- 6 sample receipts
- 36 grocery item records
- 6 common grocery products

The stores analyzed were Aldi, Walmart, Hannaford, Price Chopper, and Chanatry's.

## Results

The analysis compared the total cost of the same six grocery products across five stores.

| Grocery Store | Basket Total |
|---|---:|
| Aldi | $14.31 |
| Walmart | $15.76 |
| Hannaford | $16.65 |
| Price Chopper | $17.29 |
| Chanatry's | $17.63 |

**Key Finding:** Aldi had the lowest basket cost at $14.31, compared with Chanatry's at $17.63, representing a difference of $3.32, or approximately 18.8%.

These results reflect fictional sample pricing and should not be interpreted as actual retail price comparisons.

## Data Visualization

![Grocery Basket Price Comparison](grocery_comparison.png)

The horizontal bar
