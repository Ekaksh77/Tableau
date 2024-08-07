# Level of Detail (LOD): Handling Multiple Data Sets and Sources

## Modeling Methods

### 1. Unions
- **Definition**: Appends datasets with the same information and schema.

### 2. Joins
- **Definition**: Maps rows between datasets based on common fields. Four types of joins:

  - **Inner Joins**: Returns rows with values common to both datasets.
  - **Right Joins**: Returns rows with values common to both datasets and rows with values unique to the right dataset.
  - **Left Joins**: Returns rows with values common to both datasets and rows with values unique to the left dataset.
  - **Full Joins**: Returns all rows from both datasets, including common and unique rows.

### 3. Blending
- **Definition**: Combines data from multiple sources by linking common dimensions.

### 4. Relationship
- **Definition**: Establishes relationships between tables without merging them, allowing for data analysis across different tables based on related fields.

---

### Questions:

1. **Total Sales for Returned and Not Returned Orders**: Use Left Join.
2. **Number of Orders Returned**: Use Left Join and Inner Join.
3. **Total Return vs. Not Return Profit**: Use Full Join.
4. **Year-wise Return vs. Not Returned Metrics**:
   - Number of Orders
   - Total Sales
   - Average Sales
   - Total Profit
   - Average Profit

---

# Assignment

1. **Year-wise Number of Returned Orders**:
   - Calculate the change in returned orders.
   - If the number of returned orders decreases, display in green. If it increases, display in red.

2. **Year-wise Return vs. Not Returned Metrics**:
   - Number of Orders
   - Total Sales
   - Average Sales
   - Total Profit
   - Average Profit
   - Replace null values with "Not Returned" and "Yes" with "Returned."

3. **Top 5 Customers by Number of Returned Orders**.

4. **Top 5 Products by Number of Returned Orders**.
