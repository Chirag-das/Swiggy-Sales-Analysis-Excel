# Data Dictionary

| Field | Description |
|---|---|
| State | State associated with the order |
| City | City associated with the order |
| Order Date | Date of the order |
| Month | Month extracted from the order date |
| Day | Day-of-week associated with the order |
| Quarter | Quarter associated with the order date |
| Restaurant Name | Restaurant/brand name |
| Location | Restaurant location information |
| Category | Food/menu category supplied by the dataset |
| Dish Name | Name of the dish/item |
| Food Type | Veg or Non-Veg classification |
| Price (INR) | Price/sales value used for the dashboard's sales calculations |
| Rating | Rating associated with the record |
| Rating Count | Rating count supplied by the source dataset |

## Dashboard Calculations

**Total Sales**

Sum of `Price (INR)`.

**Total Orders**

Count of records in the dataset.

**Average Order Value**

`Total Sales ÷ Total Orders`

**Average Rating**

Average of the `Rating` field.

**Rating Count**

Sum of the provided `Rating Count` field.

**Important:** The workbook treats each data row as an order/transaction for dashboard counting purposes. The exact business definition of each source row should be confirmed if the original dataset documentation is available.
