# Sets vs Parameters

### Set
- **Definition**: A grouping method based on a field. Sets categorize data into two groups:
  - **IN**: Values that satisfy the condition (True).
  - **OUT**: Values that do not satisfy the condition (False).
- **Application**: Manually select or apply conditions to categorize data.

### Parameter
- **Definition**: An input workbook variable used to receive input from the user.

### Combined Use
- **Top Set Colour**:
  - **IN**: Top
  - **OUT**: Bottom

---

# Calculated Fields: Custom Fields

### Types of Calculated Fields:

1. **Aggregated Calculated Field**: Uses aggregate functions like SUM, MIN, MAX, AVG, COUNT, etc. It reflects inside the Dimension of AGG.
2. **Non-Aggregated Calculated Field**: Does not use aggregate functions. It reflects inside the Dimension of SUM/AVG, etc.

---

# Numerical Operators

- Operators: `*`, `/`, `-`, `+`, `^`

---

# Functions

### String Functions:
- `LEFT()`, `RIGHT()`, `MID()`, `UPPER()`, `LOWER()`, `LTRIM()`, `RTRIM()`, `TRIM()`, `REPLACE()`

### Examples:
1. First two characters of a name.
2. Concatenate: `+`

### Question:
- **UID**: Combine the first 2 characters of Customer Name, the first 2 characters of State, and the last 3 characters of City Name. Separate each with a `/`.

---

# Assignment

1. **Filter View by Top 10 Customers by Sales**:
   - Display: Customer Name, UID (First 2 characters of Customer Name, First 2 characters of State, Last 3 characters of City Name, Last 2 characters of Postal Code - all in uppercase) separated by `/`.

2. **Sub-category wise**:
   - Total Sales
   - N% Tax
   - Net Sales (Total Sales - N% Tax Value)

3. **Region and Year wise**:
   - Number of Orders Placed
   - % Change in Number of Orders Placed
