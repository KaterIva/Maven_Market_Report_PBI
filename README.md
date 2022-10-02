### Maven Market Report
consists of visuals, that represent different findings 
and insights from the dataset. 

It is based on data from CSV tables: `Calendar`, `Customers`, `Products`, `Regions`, `Returns_Data`, 
`Stores`, `Transaction_Data`.
There were also added a range of calculated columns and measures, created with DAX functions.

The tables are related to one another (relation one-to-many `1:*`). Please check
the relationship model screenshot below:

![This is an image](https://github.com/KaterIva/Maven_Market_Report_PBI/blob/master/Data_model_MA_Report.PNG?raw=true)

The report consists of three tabs: 
- `Topline Performance` - nine different visuals and three bookmarks, you can check transactions, profit, 
returns, revenue by every brand, drill through treemap `Total Transactions by Country`
and explore weekly revenue trending
- `Customer Details` - seven visuals, representing total transactions by customer name, 
gender, membership, occupation, city etc.
- `Notes` - some insights from the `Topline Performance` tab linked back to bookmarks

The filters are applied to all report pages, you can interact with content.

<sub>(click to start demo)</sub>
![This is an image](https://github.com/KaterIva/Maven_Market_Report_PBI/blob/master/mavenMarketDemo.gif?raw=true)

<sup>*Based on the course “Microsoft Power BI Desktop for Business Intelligence” by Maven Analytics, Chris Dutton*</sup>