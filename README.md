# VirtuBox Data Analyst Assessment – Online Retail II

## Project Overview

This project was completed as part of the Data Analyst Assessment for VirtuBox Infotech Private Limited.

The objective was to analyze a large transactional retail dataset, identify meaningful business insights, and provide actionable recommendations for management.

The analysis focuses on:

- Revenue performance and trends
- Product performance
- Customer value
- Geographic markets
- Cancellations and returns
- Data quality and analytical limitations
- Business recommendations

---

## Dataset

### Dataset Name
**Online Retail II**

### Source
**UCI Machine Learning Repository**

### Source URL
https://archive.ics.uci.edu/dataset/502/online+retail+ii

### Dataset Size

- Original records: **525,461**
- Columns: **8**
- Countries: **40**
- Unique products: **4,632**
- Unique customers: **4,383**
- Unique invoices: **28,816**

### Original Columns

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

The dataset contains transaction-level records for a UK-based online retailer.

---

## Business Problem

The analysis investigates how the retailer can improve sales performance and operational decision-making by identifying:

1. Revenue trends over time
2. High-performing products
3. Important geographic markets
4. High-value customers
5. Cancellation and return patterns

The goal is to identify opportunities for revenue growth, customer retention, inventory planning, and operational improvement.

---

## Methodology

The analysis was performed using **Python and Pandas in Google Colab**.

### Data Processing

The following major processing steps were performed:

1. Removed exact duplicate records.
2. Handled records with missing product descriptions and zero prices.
3. Identified and removed invalid negative-price adjustment records from the main sales analysis.
4. Created calculated transaction values using:

```text
TotalAmount = Quantity × Price
