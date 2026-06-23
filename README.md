### DecodeLabs_Project.1_Ayomide_Adesola_Akande
E-Commerce Sales Data Cleaning and Preparation

Overview
As part of the Decode Labs Data Analytics Internship Program, this project involved cleaning and preparing an e-commerce sales dataset using Microsoft Excel. The dataset consisted of 1,200 records and 14 fields containing information related to customer purchases, transactions, payment methods, and sales activities.
The primary aim of this task was to improve the quality and reliability of the data before proceeding to exploratory data analysis and visualization.

Objectives
The key objectives of the cleaning process were:
•	Identify and eliminate duplicate records.
•	Detect and address missing values.
•	Verify and correct data formats where necessary


•	Prepare the dataset for further analysis and reporting.
•	
Dataset Description
The dataset, provided by DecodeLabs, contained transactional information including:
•	Order ID
•	Date
•	CustomerID
•	Product
•	Quantity
•	Unit Price
•	Shipping Address
•	Payment Method
•	Order Status
•	Tracking Number
•	Items In Cart
•	Coupon Code
•	Referral Source
•	Total Price
•	
Tools and Features Used
The following Excel features were utilized during the cleaning process:
•	Remove Duplicates
•	Find and Replace
•	Formatting Tools

Data Cleaning Process
1. Duplicate Record Check
A comprehensive review of the dataset was conducted using Excel's Remove Duplicates feature. After examining all records, no duplicate entries were identified within the dataset.
2. Treatment of Missing Values
Missing entries were detected by applying Excel filters and the Find and Replace function. The missing values were found in the CouponCode column. Since removing these records could result in data loss, the blank cells were replaced with "UNKNOWN". A total of 309 missing entries were updated.
3. Data Type Formatting
Several formatting adjustments were carried out to ensure consistency across the dataset:
•	The Date field was converted to the appropriate date format.
•	Numerical fields were formatted as Number or Currency where applicable.
•	Text-based columns were standardized using Text/General formatting.
4. Verification of Calculated Values
The Total Price column was reviewed and validated by comparing its values against the product of Quantity × Unit Price. This step ensured that the calculations were accurate and free from inconsistencies.

Skills Demonstrated
Throughout this project, the following skills were applied:
•	Data Cleaning and Preparation
•	Data Quality Validation
•	Spreadsheet Handling and Management
•	Data Formatting and Standardization

•	Use of Excel Functions and Tools

Conclusion
The cleaning process successfully improved the overall quality and consistency of the dataset. By resolving missing values, verifying calculations, and ensuring proper formatting, the dataset became suitable for exploratory data analysis and subsequent visualization tasks. These steps helped establish a reliable foundation for generating accurate business insights.

### Sreenshots
#### Raw_data
<img width="1266" height="553" alt="raw_data" src="https://github.com/user-attachments/assets/a28ea0ca-7078-4abc-b942-34f85215c0b6" />

### Sreenshots
#### Cleaned_data
<img width="1205" height="544" alt="cleaned_data" src="https://github.com/user-attachments/assets/53041c27-d085-405b-a857-12bf133a9dd6" />
