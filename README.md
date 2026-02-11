# SALES-ANALYSIS-DASHBOARD
A comprehensive Excel-based sales data analysis project featuring interactive dashboards, pivot tables, and detailed insights from 9,994 transactions across 2020-2023.
Dataset Overview 
The main dataset contains 9,994 rows and 24 columns of transactional sales data from January 2020 through December 2023.
Categorical Values
Ship Mode (4 distinct values)
•	Standard Class - Standard shipping (3-5 business days) - 60.9%
•	Second Class - Expedited shipping (2-3 business days) - 20.3%
•	First Class - Priority shipping (1-2 business days) - 13.6%
•	Same Day - Same day delivery - 5.0%
Segment (3 distinct values)
•	Consumer - Individual retail customers (54.7%)
•	Corporate - Business/enterprise customers (32.1%)
•	Home Office - Small business/home office customers (13.3%)
Region (4 distinct values)
•	Central - Central US states
•	East - Eastern US states
•	South - Southern US states
•	West - Western US states
Category (3 distinct values)
•	Furniture - Furniture items ($685,989)
•	Office Supplies - Office and school supplies ($775,057)
•	Technology - Electronic and tech products ($836,155)
 

Data Quality Checks
Completeness
•	✓ No null values in required fields
•	✓ All orders have customer information
•	✓ All products have category assignments
•	✓ Geographic data complete (City, State, Region)
Accuracy
•	✓ Dates are logically consistent (Order ≤ Ship)
•	✓ Math checks: Sales = (Price × Quantity) × (1 - Discount)
•	✓ Profit = Sales - Cost (verified against samples)
•	✓ Postal codes match cities/states
Consistency
•	✓ Category values standardized
•	✓ Date formats uniform
•	✓ Currency values in USD
•	✓ Text fields use consistent capitalization


