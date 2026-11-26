# PowerBI_task9
# 🏡 PROPERTY SALES ANALYSIS
### Power BI | Data Cleaning | Data Modeling | DAX

---

## 📌 Project Overview

The **Property Sales Analysis** project focuses on preparing, transforming, and organizing real estate sales data using Microsoft Power BI.

The project aims to create a structured data model by cleaning property records, removing invalid entries, preparing Fact and Dimension tables, and creating a Date table using DAX.

## 🎯 Project Objectives

- Clean and transform the original property sales dataset.
- Remove zero-bedroom and zero-bathroom records.
- Create a structured Fact and Dimension table.
- Eliminate duplicate property IDs from the Dimension table.
- Create a dynamic Date table using DAX.
- Prepare a well-organized data model for property sales analysis.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** – Data modeling and reporting.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Calculated tables and date-related columns.
- **Power BI Data Model** – Fact and Dimension table organization.

## 📊 Data Model Structure

The project contains three main tables:

### 1. FactPropertySales
Stores property sales transaction details.

**Columns:**
- id
- SaleDate
- price
- PropertyAge
- PricePerSqFt

### 2. DimProperty
Stores property-related descriptive information.

**Columns:**
- id
- bedrooms
- bathrooms
- sqft_living
- sqft_lot
- floors
- waterfront
- view
- condition
- grade
- yr_built
- yr_renovated
- sqft_above
- sqft_basement
- zipcode
- lat
- long
- sqft_living15
- sqft_lot15
- PropertyAge

### 3. DimDate
A date dimension table created using DAX.

**Columns:**
- Date
- Year
- Month Number
- Month Name
- Quarter
- Day

## 🧹 Data Cleaning & Transformation

The following operations were performed:

- Renamed the original cleaned query.
- Created a reference query for the property dimension.
- Selected the required columns.
- Removed duplicate property IDs from DimProperty.
- Applied bedroom and bathroom filters greater than zero.
- Maintained repeated sales records in the Fact table.

## 📈 Data Validation

| Description | Records |
|---|---:|
| Original dataset | 21,613 |
| Zero-bedroom records | 13 |
| Zero-bathroom records | 10 |
| Records removed (overlap counted once) | 16 |
| Final records | **21,597** |
| Distinct property IDs after filtering | **21,420** |

## ⭐ Key Highlights

- Structured data preparation using Power Query.
- Fact and Dimension table creation.
- Duplicate record handling.
- Dynamic Date table generation using DAX.
- Organized property sales data for further analysis.

## 🎓 Project Outcome

This project demonstrates practical knowledge of Power BI, Power Query, DAX, data cleaning, and data modeling.

The prepared dataset and tables provide a structured foundation for analyzing property sales information and developing meaningful business insights.

---
