# DecodeLabs-Data-Cleaning-Project-1
# Data Cleaning and Preparation | DecodeLabs Internship

## Project Overview
This project focuses on cleaning, validating, and preparing a sales dataset for reliable analysis. The objective was to improve data quality by addressing missing values, checking for duplicate records, verifying calculations, and ensuring consistent formatting.

## Tools Used
- Microsoft Excel

## Data Cleaning Process

### 1. Missing Values
- Identified 309 blank cells in the Coupon Code column.
- Replaced the blank cells with "NO COUPON" to represent transactions without a recorded coupon.
- Verified that no blank cells remained in the dataset.

### 2. Duplicate Detection
- Checked the OrderID column for duplicate identifiers.
- No duplicate OrderIDs were found.
- No records were removed.

### 3. Data Standardization
- Verified consistent date formatting using YYYY-MM-DD.
- Checked all 14 columns for unnecessary spaces.
- Reviewed categorical values for capitalization and naming consistency.
- Standardized Unit Price and Total Price to display two decimal places.

### 4. Numerical Validation
- Checked Quantity, Unit Price, and Total Price for missing, negative, and non-numeric values.
- Verified that Total Price matched Quantity multiplied by Unit Price across the dataset.
- No calculation mismatches were identified.

### 5. Final Quality Checks
- Confirmed that no blank cells remained.
- Verified that the original and cleaned datasets contained the same number of records.
- Documented the cleaning actions and verification results in a Change Log.

## Project Files
- **Raw Dataset.xlsx:** Original dataset before cleaning.
- **Cleaned Dataset.xlsx:** Cleaned and validated dataset.
- **Change Log.pdf:** Documentation of cleaning actions, reasons, and outcomes.

## Key Results
- 309 missing Coupon Code values addressed.
- Zero duplicate OrderIDs detected.
- Zero calculation mismatches detected.
- Consistent date and numeric formatting.
- Original record count preserved.

## Conclusion
The dataset was cleaned and validated using Microsoft Excel. The resulting dataset is more consistent and ready for further analysis, with the cleaning process documented for transparency.

## Project Information
**Program:** DecodeLabs Data Analytics Internship  
**Project:** Week 1, Project 1: Data Cleaning and Preparation  
**Tool:** Microsoft Excel
