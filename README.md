By using Google Sheets, this data analysis explores the online sales trends of various products in 2024.
This study shows that the overall sales have been decreasing throughout the whole year with a 50% loss in profit. The number of units sold seems to be irrelevant to the profit, where the highest contributors to the sales were the items with the highest prices.

This dataset contains several columns that shows certain information on the online sales in 2024. These are:
1. Transaction ID
2. Date
3. Product Category
4. Product Name
5. Units Sold
6. Unit Price
7. Total Revenue
8. Region
9. Payment Method


The objectives of this study is:
1. to discover the overall trend of online sales in 2024.
2. to discover the sales of every products in different months in 2024.
3. to discover the products with the best and worst sales in different months in 2024.


To prepare the data for the anlysis:
1. Create a copy of the dataset into a new spreadsheet.
2. Remove irrelevant columns. In this case, 'Transaction ID' and 'Product Category' columns.
3. Remove any blank rows.
4. Convert columns into their respective formats i.e. number, date, etc.
5. Re-format the 'Date' column to show only the month name.


To fulfill the aforementioned objectives: 
1. A pivot table is made to showcase the month and the sum of the revenue. This is then made into a line chart. This line chart shows the overall trend of online sales in 2024.
2. A query function is used to get the month, product name, the sum of units sold, and the sum of revenue, grouped by the product name and the sum of units sold.
3. A filter function is then used to get these columns from only the chosen month.
4. From here, a bar chart is made to display the sale of every product in chose month.
5. Then, query functions are used again to display the top 5 and bottom 5 products in separare tables.
6. The line chart, bart chart, the filtered monthly sale table with a drop down menu, top 5 and bottom 5 product tables are put into a dashboard.
