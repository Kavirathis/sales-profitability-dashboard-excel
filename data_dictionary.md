# Data Dictionary

Source sheet: `DATA` (2,000 rows x 12 columns, 01-Jan-2022 to 31-Dec-2023). No missing values, no duplicate transaction IDs.

| Column | Type | Description |
|---|---|---|
| Transaction_ID | Text | Unique ID (TXN0001 - TXN2000) |
| Transaction_Date | Date | Date of transaction |
| Revenue | Number | Income from the transaction |
| Expenses | Number | Cost of the transaction |
| Profit | Number | Revenue - Expenses (negative = loss) |
| Category | Text | Business category (R&D, Operations, Sales, Marketing, HR ...) |
| Region | Text | Africa, Asia-Pacific, Europe, North America, South America |
| Department | Text | HR, IT, Sales, Marketing, Operations, Finance |
| Product_Line | Text | Healthcare, Electronics, Clothing, Software, Furniture |
| Customer_Segment | Text | B2B, B2C, SMB, Enterprise |
| Payment_Method | Text | Cash, Credit Card, Bank Transfer, PayPal |
| Discount | Decimal | Discount applied (0.00 - 0.30) |
