# Blending

### Definition:
- **Blending**: Combines data from two different sources.
- **Method**: Uses Left Join.

### Aggregation Levels:
- **Left (Primary Data Source)**: Indicated by a Blue Tick.
- **Right (Secondary Data Source)**: Indicated by an Orange Tick.

### Notes:
- Primary and Secondary Data Sources can vary on each sheet.

---

### Questions:

1. **Yearly Number of Returned Orders**.
2. **Region and Year-wise Metrics**:
   - Number of Returned vs. Not Returned Orders
   - Total Sales

---

# Reference Lines and Bands

- **Types**:
  - **Average Line**
  - **Constant Line**
  - **Variable Line (Target)**

---

### Questions:

- **Region and Year-wise Total Sales**.

---

# Assignments:

1. **Year and Region-wise Total Sales**:
   - Create a side-by-side bar chart.
   - Bars for regions below the average of the year's total should be red.
   - Bars for regions above the average line should be green.

2. **Year and Category-wise Metrics**:
   - Number of Returned Orders
   - Average Returned Sales
   - Use blending.

3. **Category-wise Sales Comparison**:
   - Current Year vs. Previous Year Sales.
   - Display using a Bar-in-Bar chart.

4. **Field Creation**: `State Sale Cat`
   - If State-wise Total Sales >= 70K, categorize as "Top".
   - If State-wise Total Sales >= 35K, categorize as "MOD".
   - Otherwise, categorize as "Poor".

   - Show State Sales Category-wise with the number of total states in a Pie Chart.
