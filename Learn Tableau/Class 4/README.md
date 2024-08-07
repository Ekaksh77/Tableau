# Tips to Create a Professional Dashboard

1. Ensure all dashboards have the same size and consistent fonts for titles and headers.
2. Use a gradient or a mix of 2-4 colors only; avoid overly colorful designs.
3. Properly format each dashboard object, including borders and colors.
4. Utilize your company’s theme colors.

---

## Examples

### Question:
Sub-category wise number of orders for the Central region with total sales >= 50K.

---

## Filters

### Extract Filters and Data Source Filters
- Dimension-Date Filter
- Measure Filter

### Relative Date Filtering
- By default, the anchor date is today.

#### Example:
Total sales for each category for the year 2018.

#### Example:
Total sales for the last 6 months of the data.

---

## Context Filters

- Created using Dimension Filter only to set priority.

### Order of Operations in Tableau

1. **Extract Filter**
2. **Data Source Filter**
3. **Context Filter**: Top priority at sheet level, includes sets, conditional filters, Top N, and fixed LOD.
4. **Dimension Filter**: Includes/excludes LOD, data blending.
5. **Measure Filter**: Includes forecasts, table calculations, clusters, and totals.
6. **Table Calculation Filters**: Includes trend lines and reference lines.
7. **Quick Filters**: Available in the tooltip after right-clicking.

---

## Top and Bottom Filtering

### Questions:
- Top 5 sub-categories by total profit.
- Bottom 5 sub-categories by total profit.
- Year-wise top 3 sub-categories by sales for the years 2015, 2016.

---

## Assignment

1. Top 5 products by number of orders.
2. Bottom 8 products by number of orders - bar charts.
3. Date-wise total sales for every Monday in January 2015.
