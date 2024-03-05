##SQL Data Cleaning Project

#Project Summary:
The SQL Data Cleaning Project focuses on enhancing the quality and structure of the Nashville Housing dataset stored in the Portfolio Project database. The project involves a series of SQL queries and updates to address data inconsistencies, standardize formats, and enrich the dataset's completeness.

#Project Tasks:

1. Standardizing Date Format:
    Conversion of SaleDate to a standardized Date format.
    Handling potential issues with the update process.

2. Populating Property Address Data:
    Identifying and addressing null values in PropertyAddress.
    Utilizing a JOIN operation to consolidate PropertyAddress data from different records.
    Updating null PropertyAddress values with nonnull alternatives.

3. Breaking out Address into Individual Columns:
    Splitting PropertyAddress into separate columns for Address and CityState.
    Utilizing string manipulation functions like SUBSTRING and CHARINDEX.

4. Processing Owner Address:
    Parsing OwnerAddress into separate columns for State, City, and Address.
    Handling potential challenges with parsing.

5. Changing Y and N to Yes and No:
    Converting 'Y' and 'N' values in the 'Sold as Vacant' field to 'Yes' and 'No'.

6. Removing Duplicates:
    Identifying and removing duplicate records based on specific criteria using ROW_NUMBER().

7. Deleting Unused Columns:
    Removing columns such as OwnerAddress, TaxDistrict, PropertyAddress, and SaleDate.

8. Importing Data using OPENROWSET and BULK INSERT:
    Providing more advanced options for importing data, though server configuration is required.
    Showing potential methods using BULK INSERT and OPENROWSET.

