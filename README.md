# DataAnalytics-Week3

## Dataset Cleaning Process

This README provides an overview of the dataset cleaning process for the  Data cleaning using Pandas and  chipotle.tsv  projects.

## Overview 

Briefly describe the purpose and scope of the project. Include information about the dataset and its source.

## Cleaning Process

Outline the steps taken to clean the dataset. You may follow a structure similar to the one below:

### 1. Missing Values Handling

- **Question:** Check for missing values in each column (Order ID, Quantity, Item Name, Choice Description, Item Price). How should missing values be handled?

- **Action:** Use appropriate methods to handle missing values, such as filling them with mean or mode, or removing rows with missing values.

### 2. Data Types Verification

- **Question:** Verify the data types of each column. Do they align with their expected types, and should any adjustments be made?

- **Action:** Convert columns to the correct data types if needed. For example, convert 'Item Price' from string to float.

### 3. Duplicated Entries

- **Question:** Identify and handle duplicated entries in the dataset. How might duplicates impact analysis, and what is the appropriate action?

- **Action:** Remove or handle duplicated entries based on specific criteria. Use `drop_duplicates` method.

### 4. Quantity and Item Price Examination

- **Question:** Examine the Quantity and Item Price columns. Are there any inconsistencies or anomalies that need correction?

- **Action:** Address any anomalies or inconsistencies in the Quantity and Item Price columns.

### 5. Choice Description Analysis

- **Question:** Analyze the Choice Description column. How should choices be handled, especially when there are multiple descriptions for a single item?

- **Action:** Decide on a strategy for handling multiple choice descriptions, such as selecting the first one or concatenating them.

### 6. Special Characters Check

- **Question:** Check for special characters in text-based columns (e.g., Item Name, Choice Description). How can these be addressed for consistency?

- **Action:** Remove or replace special characters using string manipulation methods.

### 7. Order ID Integrity Verification

- **Question:** Cross-reference the Order ID column for integrity. Are there any irregularities or patterns that need validation?

- **Action:** Verify the integrity of Order IDs and address any irregularities.

### 8. Item Name Standardization

- **Question:** Standardize the Item Name column. Are there variations that can be unified for better analysis?

- **Action:** Apply standardization techniques to unify variations in Item Names.

### 9. Quantity and Price Relationships Investigation

- **Question:** Investigate the relationships between Quantity and Item Price. Are there cases where adjustments need to be made for accurate analysis?

- **Action:** Analyze and adjust Quantity and Item Price relationships if necessary.

### 10. Data Integrity Check

- **Question:** Perform a data integrity check by ensuring that quantities and prices align with the corresponding items and descriptions.

- **Action:** Cross-verify quantities and prices to ensure data integrity.

### 11. Converting to CSV

- **Optional Question:** If needed, convert the cleaned dataset to a CSV file using the `to_csv` function with sep=','.

- **Optional Action:** Use the `to_csv` function to export the cleaned dataset to a CSV file.

### 12. Handling Categorical Data

- **Question:** For categorical columns (e.g., Item Name), consider encoding or transforming them into a format suitable for analysis.

- **Action:** Apply appropriate encoding or transformation techniques for categorical data.

### 13. Consistent Quantity and Price Units

- **Question:** Ensure consistency in units for Quantity and Item Price. Should any conversions or adjustments be made for uniform analysis?

- **Action:** Adjust units or values if necessary to ensure consistency.
