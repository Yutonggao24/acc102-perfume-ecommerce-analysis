# acc102-perfume-ecommerce-analysis
ACC102 Track 2 data analysis project on eBay perfume e-commerce pricing, demand signals, and product opportunities.

# eBay Perfume E-Commerce Market Analysis

## 1. Problem and User

This project analyses eBay perfume product listings to understand pricing patterns, demand signals, and possible product opportunities.

The target users are small e-commerce sellers, marketing students, and business analysts interested in online perfume market trends.

## 2. Data

Dataset: Perfume E-Commerce Dataset  
Source: https://www.kaggle.com/datasets/aminasalamt/perfume-e-commerce-dataset/data  
Access date: April 2026

Files used:

- `ebay_mens_perfume.csv`
- `ebay_womens_perfume.csv`

The dataset includes product information such as title, brand, price, availability, sold quantity, and product category.

## 3. Methods

The analysis was completed in Python.

Main steps:

- Load men's and women's perfume datasets
- Combine both datasets
- Clean price and sold quantity fields
- Analyse brands, price ranges, gender categories, and demand signals
- Use sold quantity and estimated sales proxy to identify product opportunities

## 4. Key Findings

- Most listings are concentrated in lower and middle price ranges.
- High price does not always mean higher demand.
- Some brands have stronger market presence on eBay.
- Mid-priced products may offer better opportunities because they balance affordability and demand.

## 5. How to Run

Install the required packages:

```bash
pip install pandas matplotlib seaborn jupyter
```

Open and run the notebook:

```bash
jupyter notebook perfume_ecommerce_market_analysis_executed.ipynb
```

Make sure the two CSV files are in the same folder as the notebook.

## 6. Files

```text
README.md
perfume_ecommerce_market_analysis_executed.ipynb
ebay_mens_perfume.csv
ebay_womens_perfume.csv
requirements.txt
```

## 7. Demo Video

Demo video link

## 8. Limitations

This dataset is based on eBay listings, so it may not represent the entire perfume market. Sold quantity is used as a demand signal, but it is not the same as complete transaction-level sales data.
