# SuperStore Dashboard

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


