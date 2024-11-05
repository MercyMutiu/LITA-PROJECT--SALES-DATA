# LITA-PROJECT--SALES-DATA
This shows the analysis of the sales data given for the LITA project

### Project overview and objective
This project made use of Microsoft Excel, SQL and Power BI to analyze the sales data. the objective is to analyze the dataset containing sales information using the three applications taught during the class period. The project shows how the three tools can be combined to bring out information from raw data, discover the trends in the sales and track the sales performance.

### Data sources
The data set was provided by the facilitators of the program as a final project for the course.

### Tools and Techniques
- Microsoft Excel: pivot table was used to summarize the sales by product, region and month, also formulas were used to calculate some metrics in the dataset.
- SQL: the dataset was loaded into the SQL server and different queries were written.
- Power BI: a dashboard was created and it included the sales overview, the top performing products and the regional breakdown.

### Steps taken
1. Data cleaning: the data was cleaned by removing duplicates thus reducing the number of rows to 9921 rows.
- Pivot table: the data was summarized and tables were created to show the summary of total sales by product, region and month.
   
![image](https://github.com/user-attachments/assets/ddc25f4a-8cd1-4269-ad6d-d1c3e6ce241f)

The image above shows the summary of the sales data by product, region and month, also the average sales was shown.

2. Data Analysis
- Microsoft Excel: was use to calculate the average sales by product and the total revenue per region
 - Average sales per product
``` Excel
=AVERAGEIF(C2:C9922,"shirt",H2:H9922)
=AVERAGEIF(C2:C9922,"shoes",H2:H9922)
=AVERAGEIF(C2:C9922,"Hat",H2:H9922)
=AVERAGEIF(C2:C9922,"Socks",H2:H9922)
=AVERAGEIF(C2:C9922,"Jacket",H2:H9922)
=AVERAGEIF(C2:C9922,"Gloves",H2:H9922)
```

 -Total revenue per region
``` Excel
=SUMIF(D2:D9922,"North",H2:H9922)
=SUMIF(D2:D9922,"south",H2:H9922)
=SUMIF(D2:D9922,"east",H2:H9922)
=SUMIF(D2:D9922,"west",H2:H9922)
```

