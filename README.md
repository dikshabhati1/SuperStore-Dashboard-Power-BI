# SuperStore Dashboard

### Overview
![](https://github.com/dikshabhati1/SuperStore-Dashboard-Power-BI/blob/main/Dashboard%20Images/Overview1.jpg)

### Segment
![](https://github.com/dikshabhati1/SuperStore-Dashboard-Power-BI/blob/main/Dashboard%20Images/Segment2.jpg)

### Product
![](https://github.com/dikshabhati1/SuperStore-Dashboard-Power-BI/blob/main/Dashboard%20Images/Product3.jpg)

## Dataset
This dataset is the Superstore dataset. This contains 2 excel files:

**1. SuperStore Orders** <br>
This excel file contains the data about orders made by customers for any product. This table also contains information about customers like name, address and information about orders like product name, order-id, product category. There are total 19 columns and 5899 rows in this excel file.

**2. SuperStore Returns** <br>
 This excel file contains information about the returned order id.
 



## DAX Formulas used in Measures

**1. Total Sales**
* `Total Sales = SUM(Orders[Sales])`

**2. Total Profit**
* `Total Profit = SUM(Orders[Profit])`

**3. Extract Year from Date**
* `Year = Year(Orders[Order Date])`

**4. Extract Month from Date**
* `MonthNo = Month(Orders[Order Date])`

**5. MonthName from Month number**
* `MonthName = FORMAT(DATE(1, [MonthNo], 1), "MMM")`


