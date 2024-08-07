# Type Conversion Functions

1. **String**: `STR()`
2. **Integer**: `INT()`
3. **Decimal**: `FLOAT()`
4. **Date**: `DATE()`
5. **Date with Time**: `DATETIME`
6. **Boolean**: `BOOL()`
7. **ZN()**: Replaces NULL values with 0
8. **ABS()**: Converts negative values to positive values

---

# Logical Functions

- `IF`, `ELSE`, `ELSEIF`, `END`, `CASE`, `WHEN`, `IFF`

---

# Aggregate Functions

- `SUM`, `MIN`, `MAX`, `AVG`, `COUNT`, `COUNTD`, etc.

---

### Questions:

1. Sub-category wise total profit.
2. Sub-category wise total profit and total loss.
3. Sub-category wise total sales:
   - >= 2L: "A Class"
   - Rest: "P Class"

4. Sub-category wise total sales:
   - >= 3L: "A1 Class"
   - >= 2L: "A2 Class"
   - >= 80K: "B Class"
   - Rest: "P Class"

---

# Date Functions

- `YEAR()`, `MONTH()`, `DAY()`, `WEEKDAY()`, `TODAY()`, `NOW()`, `DATEDIFF()`, `DATEADD()`, etc.

---

### Question:

- Sub-category wise total sales for the years 2015 and 2016 individually, and their total, using calculated fields only.

---

# Assignment

1. **Dashboard Parameter**: 
   - Sub-category wise total sales:
     - `P1`: "A1 Class"
     - `P2`: "A2 Class"
     - `P3`: "B Class"
     - Rest: "P Class"

2. **Calculated Fields**:
   - Sub-category wise total sales for 2015 and 2016 individually, their total, difference, and percentage difference (percentage change of 2016 from 2015 sales).
