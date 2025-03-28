# PySpark Fundamentals

A comprehensive repository for learning and implementing PySpark fundamentals with practical examples.

## Repository Contents

- **Fundamentals.ipynb**: Jupyter notebook containing PySpark basics, transformations, actions, data reading, and advanced operations
- **BigMart_Sales.csv**: Sample retail dataset with 8523 records and 12 columns including item and outlet information
- **drivers.json**: JSON dataset containing Formula 1 driver information

## Dataset Information

### BigMart_Sales.csv
- **Rows**: 8523
- **Columns**: 12
- **Fields**: Item_Identifier, Item_Weight, Item_Fat_Content, Item_Visibility, Item_Type, Item_MRP, Outlet_Identifier, Outlet_Establishment_Year, Outlet_Size, Outlet_Location_Type, Outlet_Type, Item_Outlet_Sales

### drivers.json
- JSON dataset containing Formula 1 driver information
- Fields include driverId, driverRef, code, name, nationality, dob, and more

## Topics Covered

- **Data Reading**: CSV, JSON with options (inferSchema, header)
- **Schema Definition**: DDL Schema, StructType
- **Transformations**: select, filter, withColumn, withColumnRenamed, sort, limit, drop
- **Handling Nulls**: dropna, fillna
- **String Operations**: regexp_replace, upper/lower functions
- **Date Functions**: current_date, date_add, date_sub, datediff
- **Aggregations**: groupBy, agg functions (sum, avg), collect_list
- **Window Functions**: row_number, rank, dense_rank
- **SQL Integration**: createTempView, spark.sql
- **User Defined Functions (UDF)**: Creating and implementing custom functions
- **Joins**: inner, left, right, anti
- **Advanced Features**: pivot, when-otherwise conditional logic
