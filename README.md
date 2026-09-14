# Product Catalog Analysis

## Overview

A data-driven analysis of a product catalog to uncover pricing patterns, product profitability, brand performance, supplier economics, and customer-facing product insights.

## Key Business Insights

- **Average Product Price:** $245
- **Median Product Price:** $165
- **Maximum Product Price:** $1,482.95
- **Price Standard Deviation:** $251
- **Products Above Average Price:** 400

### Category Pricing

- **Electronics** has the highest average price at **$798.84**.
- **Jewelry** follows at **$566.81**.
- **Home Appliances** averages **$479.14**.
- **Health & Wellness** has the lowest average price at **$158.63**.

### Brand Profitability

- **Samsung** generated the highest total profit at **$4,317.20**.
- **LG** generated **$3,825.17**.
- **David Yurman** generated **$3,204.63**.

### Supplier Performance

- **Amazon Supply** achieved the highest average profit at **$128.87**.
- **Domestic Producers** averaged **$128.31**.
- **Euro Logistics** averaged **$128.27**.

### Pricing & Ratings

The Pearson correlation between product price and rating is **-0.0202**, indicating virtually **no linear relationship** between price and customer rating.

This suggests that higher-priced products do not necessarily receive higher ratings.

## Top Profitable Products

| Product | Profit |
|---|---:|
| HP Smartphone | $624.22 |
| OnePlus Gaming Console | $601.11 |
| OnePlus Smartphone | $586.64 |
| Messika Product | $566.19 |
| HP Camera | $560.45 |

## Business Recommendations

1. **Prioritize high-value categories** such as Electronics and Jewelry while maintaining competitive pricing.
2. **Strengthen relationships with high-performing brands and suppliers** that consistently generate stronger profits.
3. **Avoid using product ratings alone for pricing decisions**, as the price-rating correlation is almost zero.
4. **Investigate the drivers of supplier profitability** before reallocating purchasing volume, including quality, reliability, and cost structure.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Project Structure



```text
Product-Catalog-Analysis/
│
├── Notebook/
│   └── Product Catalog Analysis.ipynb
│
├── Presentation/
│   └── Product_Catalog_Corporate_Numbers_Analysis.pptx
│
└── README.md

