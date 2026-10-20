Added
- Review column (AND): flags orders with a Low margin and revenue over $1,000. Result: 2 orders.
- Bulk column (OR): flags orders with Qty of 5 or more or a Large order size. Result: 119 orders.
- Targets table on the Lookup sheet with a target margin per category (Gaming 8%, all others 25%).
- Target Margin column using XLOOKUP against the Targets table.
- Below Target column using IF to compare actual margin with target margin.

Findings
- Bulk matches Large exactly (119 orders), so the Bulk flag adds no new information.
- 4 orders use product IDs (P121, P130) missing from the product list. Kept and flagged, not guessed.
- 117 orders are below their category target: Phones 58, Computers 34, TV 25. No Gaming orders.
- The Day 2 Low flag (under 20%) pointed at game consoles, but category targets point at phones, TVs and laptops. The threshold chosen changes the story.

Next
- XLOOKUP approximate match for price bands, first PivotTable and findings write-up.
