# DAX_Exercise_PowerBI

![DAX_Exercise_PowerBI](https://github.com/alexvatti/DAX_Exercise_PowerBI/blob/main/Capture.png)
**Filter Context:**
Filter context is the set of values allowed in each column, based on filter constraints that were applied to the row or that are defined by filter expressions within the formula.

**The “Calculate“ Function:**
The `CALCULATE` function helps change the filter context. This function allows you to change the context in which an expression is evaluated.

**The “ALL” Function:**
The filter function `ALL` returns all the rows in a table, or all the values in a column, ignoring any filters that might have been applied. This function is useful for clearing filters and creating calculations on all the rows in a table.

**The “ALLEXCEPT” Function:**
The filter function `ALLEXCEPT` removes all context filters in the table except filters that have been applied to the specified columns.

**The “FILTER” Function:**
The filter function `FILTER` returns a table that represents a subset of another table or expression.

**Calculated Columns:**
Sometimes the data we're analyzing does not contain a particular field necessary to achieve the desired results. In such situations, calculated columns are useful. These columns use Data Analysis Expressions (DAX) formulas to define their values.

# Task

Matrix Visualization: Construct a matrix to display the percentage 
contribution of each category to the total sales. This will provide insights into 
each category's relative performance within overall sales. (total sales = 
SUM(sale_amount)). The total_sales column values shouldn’t change when a 
filter like category or brand is applied. 

# Task 

Card Visualization: Create a card visual to showcase sales by category. 
Configure this to respond only to category-specific filters applied to the sales 
table, ensuring it remains unaffected by other types of filters
