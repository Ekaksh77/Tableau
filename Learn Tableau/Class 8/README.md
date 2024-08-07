# Table Calculative Functions

- **Index()**: Returns the index of the current row in the partition.
- **Last()**: Returns the number of rows from the current row to the last row in the partition.
- **Total()**: Computes the total of the expression across the entire partition.

---

# Window Functions

### Questions:

1. **Region and Year-wise Total Sales**: Calculate the total sales and average of the total sales for each region's yearly total sales.
   - Functions: `WINDOW_AVG`, `WINDOW_SUM`, `WINDOW_MIN`, etc.

2. **Cumulative**: Represents a running total.
   - Function: `LOOKUP()`

---

# Level of Detail (LOD) Calculations

LOD calculations specify the level of aggregation in calculations.

### LOD Types:

1. **Fixed LOD**: Computes or aggregates the value at the specified level of detail in the calculation.
   - **Syntax**: `{FIXED [Dim1], [Dim2], ... : Expression}`

2. **Scoped Table LOD**: Fixed at the scoped total level without specifying dimensions.
   - **Syntax**: `{Expression} : {SUM(Sales)}`

---

### Questions:

1. **Year and Category-wise Total Sales**: Calculate total sales, sum of the year's and category's total sales.

---

# Assignment

1. **Year and Category-wise Total Sales**:
   - Calculate total sales, sum of the year's and category's total sales, average of the year's and category's total sales, and the difference between year and category total sales from the average of the year's and category's total sales using LOD calculations.

2. **Yearly Number of Orders**:
   - Calculate the percentage of total orders placed using table calculations.

3. **Yearly Number of Orders**:
   - Calculate the percentage of total orders placed using LOD calculations.

4. **Year and Category-wise Total Sales**:
   - Calculate total sales, sum of the year's and category's total sales, average of the year's and category's total sales, and the difference between year and category total sales from the average of the year's and category's total sales using table calculations.
