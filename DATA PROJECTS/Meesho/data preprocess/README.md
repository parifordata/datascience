## Data preprocessing steps we did

1. Imported Excel file into Power BI
2. Selected `Raw_Messy_Data`
3. Clicked **Transform Data**
4. Removed automatic `Changed Type` step
5. Duplicated raw query
6. Renamed duplicate query as `clean data`
7. Turned on:

   * Column quality
   * Column distribution
   * Column profile
8. Changed profiling to **entire dataset**
9. Removed fully blank rows
10. Removed exact duplicate rows correctly using all columns
11. Changed text columns to **Text**
12. Applied **Trim** on text columns
13. Applied **Clean** on text columns
14. Cleaned `Category`
15. Standardized duplicate category names
16. Kept `Kids Section` as final category
17. Replaced/null handled category blanks
18. Cleaned `State`
19. Standardized state short forms and spelling mistakes
20. Replaced missing states with `Unknown`
21. Cleaned `City`
22. Cleaned `Availability`
23. Cleaned `Order Status`
24. Cleaned `Payment Mode`
25. Standardized `UPI`, `COD`, `Net Banking`
26. Replaced text nulls with Unknown values
27. Cleaned `MRP`
28. Cleaned `Selling Price`
29. Removed ₹, Rs, commas, Free, NA from price columns
30. Converted price columns to **Decimal Number**
31. Cleaned `Rating`
32. Replaced rating errors with `null`
33. Cleaned `Reviews`
34. Cleaned/check `Quantity`
35. Cleaned `Order Date`
36. Converted `Order Date` using locale
37. Replaced date errors with `null`
38. Created `Price Check` column
39. Created `Total Sales` column
40. Created `Discount %` column
41. Created `Delivery Days` column
42. Created `ID Check` column
43. Checked final data types
44. Confirmed error count is 0
45. Clicked **Close & Apply**
46. Created DAX measures:

* `Total Sales Amount`
* `Total Orders`
* `Total Items`
* `Average Sales`
* `Average Rating`
