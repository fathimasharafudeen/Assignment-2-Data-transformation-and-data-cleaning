# Assignment-2-Data-transformation-and-data-cleaning
# Excel Data Cleaning and Transformation Assignment

A hands-on exercise applying core data-cleaning and transformation techniques in Excel to a small retail product dataset.

## Overview

This project works with a dataset of retail products (electronics, fashion, kitchen, outdoor, and accessories items) and applies a series of cleaning and transformation tasks commonly needed when preparing raw data for analysis.

## Dataset

The dataset contains the following columns:

| Column | Description |
|---|---|
| Manufacturing Date | Date the product was manufactured |
| Country Code | Country of origin/sale (e.g. US, UK, IN, CA) |
| Product Name | Name of the product |
| Brand Name | Brand/manufacturer |
| Price ($) | Product price |
| Quantity | Units in stock/sold |
| Category | Product category (e.g. Electronics, Fashion, Kitchen, Outdoor, Accessories) |
| Product Brand | Combined Brand Name + Product Name |

## Tasks Covered

- Identifying and handling missing values in the `Price` column
- Imputing or otherwise handling missing `Category` values
- Detecting inconsistent text formats and typos in `Product Name` and `Category`
- Using Find & Replace to standardize text and fix misspellings
- Identifying and removing duplicate rows
- Splitting a combined `Product ID` field into `Manufacturing Date` and `Country Code`
- Merging `Brand Name` and `Product Name` into a single `Product Brand` column
- Formatting the `Price` column as currency
- Formatting `Manufacturing Date` as `DD-MM-YYYY`
- Applying data bar / color scale conditional formatting to `Price`
- Creating a custom conditional formatting rule to highlight `Category = "Electronics"`

## File

- `Excel_Assignment_2_-_Data_Cleaning_and_Transformation.xlsx` — the dataset and worked solutions

## Tools

- Microsoft Excel (Find & Replace, Text to Columns, conditional formatting, data validation)

## Notes

This is a coursework/practice assignment intended to demonstrate proficiency in fundamental Excel data-cleaning workflows.
