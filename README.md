# Practical-lab2
# Practical Lab 2: Data Collection & Preprocessing

This lab is about working with raw e-commerce transaction data and turning it into something useful. I used Python and object-oriented programming to structure and clean the data, apply transformations like discount extraction, and finally calculate total revenue by city.

## What This Project Does

- Loads and cleans messy data
- Fixes missing or incorrect values
- Converts coupon codes into numerical discounts
- Adds a new feature: days since purchase
- Calculates total revenue per shipping city
- Saves the clean dataset as JSON and Parquet files

## How to Run It

```bash
python -m venv venv
.\venv\Scripts\activate
pip install -r requirement.txt
jupyter notebook


## Datasets:

Primary.csv: 500 e-commerce records (manually uploaded)
secondary.csv: Metadata (also manually added)