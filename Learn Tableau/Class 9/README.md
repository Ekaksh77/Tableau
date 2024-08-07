# Level of Detail (LOD) Calculations

## 1. Fixed LOD
- **Definition**: Computes or aggregates values at a fixed level of detail specified in the calculation.

### Example:
- Calculate year and category-wise total sales.
- Compute the sum of the year's total sales.
- Determine the average of the year's sales.
- Calculate region-wise total sales.

**Syntax**: `{FIXED [Dim1], [Dim2], ... : Expression}`

---

## 2. Scoped Table LOD
- **Definition**: Fixes the level of detail at the scoped level or total level, without specifying dimensions.

**Syntax**: `{Expression} : {SUM(Sales)}`
