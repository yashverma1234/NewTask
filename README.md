# Marketing Campaign Dataset Cleaning

This project focuses on cleaning and preprocessing the Marketing Campaign dataset using Python and Pandas. The dataset was originally sourced from a direct marketing campaign dataset and contains information on customer demographics, purchasing behavior, and response to marketing efforts.

## 📁 Dataset

- File Name: `marketing_campaign.csv`
- Format: Tab-separated values (`.tsv`)
- Rows: ~2,200
- Columns: Customer ID, Demographics, Product Purchases, Campaign Responses, etc.

## 🧹 Data Cleaning Performed

The following steps were performed on the raw dataset:

1. Removed missing values
2. Removed duplicate rows
3. Converted the `Dt_Customer` column to datetime format
4. Renamed columns to lowercase and underscore-separated format
5. Standardized text fields like `Education` and `Marital_Status`
6. Converted `Income` column to float

## 🧰 Tools Used

- Python 3.x
- pandas

## 📝 How to Run

Make sure you have Python and Pandas installed:

```bash
pip install pandas
```
Then run:
```
python clean_data.py
```
The cleaned data will be saved as:
```
cleaned_marketing_campaign.csv
```
