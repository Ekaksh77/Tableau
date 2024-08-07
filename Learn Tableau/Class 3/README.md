# Data Connection Types in Tableau

### 1. Live Connection
### 2. Extraction Connection

---

## Filters

Filters are subsets of data required for analysis and visualization.

### Types of Filters:

1. **Global Filter**: Applied at the entire workbook level.
    - Extract Filter
    - Data Source Filter

    All other filters, by default, are applied at the sheet level, but they can be changed to global.

2. **Dimension Filter**: Categorical / Qualitative filter
    - **Example**: Total sales till date for the Central and East regions combined.

3. **Measure Filter**
    - **Examples**:
        1. Sub-category wise total sales for sub-categories with profit only.
        2. Sub-categories with total sales >= 80K and net profit <= 0 (loss-making).
        3. Sub-category wise sales for the East region only, with net loss.

4. **Table Calculation Filter**
5. **Context Filter**
6. **Date Filter**
7. **Conditional Filter**
8. **Tooltip Filter**

---

## Assignment

### Create a Dashboard with the Following Content:
Filters should be present in the dashboard and worksheet titles should be dynamic wherever possible.

1. **Multi-Value Cards**: 
    - Total Sales
    - Total Profit
    - Total Units
    - Total Customers
    - Total Number of Unique Products
    - Total States
    - Total Number of Unique Orders

2. **Tree Map**:
    - Category-wise total sales.
    - The level should also include the total number of unique customers in each category along with total sales.

3. **Region and Category-wise Total Number of Unique Orders**:
    - For the ship modes "First Class" and "Same Day" only.

4. **Segment-wise Total Sales**:
    - Bubble chart.

5. **Sales vs. Profit**:
    - For each year.
