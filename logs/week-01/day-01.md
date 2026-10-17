# Week 1, Day 1 | 17 Oct 2026

**Goal:** Use XLOOKUP to join sales data with product and store details.

## What I did
- Used XLOOKUP to bring ProductName, Category, UnitPrice, UnitCost and Region into a 600-row sales table
- Added "Not found" handling and found 4 orders with product codes missing from the product list
- Used COUNTIF to count the missing rows
- Built Revenue and Profit columns

## Key results
- Total revenue: $317,546
- Total profit: $92,222 (about 29% margin)

## What I learned
- An error in one column spreads to every column that uses it
- Ctrl+F searches formulas too, so COUNTIF is better for counting results
- Keep totals away from the data so sorting and pivots don't break

## Next
Day 2: IF logic and more calculated columns
