---
dataset_info:
  features:
  - dtype: string
    name: Order_ID
  - dtype: string
    name: Customer_ID
  - dtype: string
    name: Date
  - dtype: int64
    name: Age
  - dtype: string
    name: Gender
  - dtype: string
    name: City
  - dtype: string
    name: Product_Category
  - dtype: float64
    name: Unit_Price
  - dtype: int64
    name: Quantity
  - dtype: float64
    name: Discount_Amount
  - dtype: float64
    name: Total_Amount
  - dtype: string
    name: Payment_Method
  - dtype: string
    name: Device_Type
  - dtype: int64
    name: Session_Duration_Minutes
  - dtype: int64
    name: Pages_Viewed
  - dtype: bool
    name: Is_Returning_Customer
  - dtype: int64
    name: Delivery_Time_Days
  - dtype: int64
    name: Customer_Rating
  splits:
  - name: train
    num_examples: 5000
---

# Saturia -- E-Commerce Dataset

## Dataset Description

This dataset contains e-commerce order and customer behaviour
information. It includes customer details, order dates, product
categories, prices, quantities, discounts, payment methods, device
types, website session activity, delivery time and customer ratings.

## Dataset Source

-   **Platform:** Hugging Face
-   **Dataset:** Saturia/e-commerce
-   **Dataset URL:** https://huggingface.co/datasets/Saturia/e-commerce
-   **Format:** CSV
-   **Number of records:** 5,000
-   **Number of features:** 18
-   **Date range shown in the dataset viewer:** 1 January 2023 to 26
    March 2024

## Intended Use

This dataset can be used for educational data analysis and visualisation
projects, including sales analysis, customer behaviour analysis, payment
preference analysis and delivery performance analysis.

## Suggested Analysis

-   Analyse total sales by product category and city.
-   Identify popular payment methods and device types.
-   Examine returning and new customer patterns.
-   Explore the relationship between session duration, pages viewed and
    purchase amount.
-   Analyse delivery times and customer ratings.
-   Study sales trends over time.

## Data Cleaning Notes

Before analysis, inspect the downloaded CSV for missing values,
duplicate records, incorrect data types, inconsistent category labels
and unusual numerical values. Do not assume that missing values or
duplicates exist; verify them in the file.

## Limitations

This dataset is presented as an e-commerce dataset for analysis. Check
the dataset source for further information about how the records were
collected or generated. Do not treat the records as verified real-world
business transactions.
