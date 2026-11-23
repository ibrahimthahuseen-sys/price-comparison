# Supplier Price Comparison

A single-file web app (`index.html`) that compares supplier quotations side by side.

## What it does
- Upload one quotation per supplier (PDF, Excel .xlsx/.xls, CSV, or a photo/scan), or paste quote text.
- Pulls out each **item**, the **quantity quoted** and the **unit price (excl. GST)**.
- Shows one **Qty** column, then a **Price** column for each supplier, headed by the supplier's name.
- Matches the same item across suppliers, even when they word it differently.
- Highlights the **cheapest price in every row**.
- Summary cards show the lowest complete quote (qty × price) and the best mix of suppliers.
- Lets you click any cell, item name or supplier name to correct it. Rename an item to match another row and the two rows merge.
- **Export to Excel** (.xlsx): a Comparison sheet with the cheapest cells highlighted, plus one sheet per supplier.
  **Copy table** copies a version you can paste into Excel.

## How to run it
- **Best:** open the published version on claude.ai. Automatic reading of PDFs, photos and free-form quotes uses Claude there.
- **Local / GitHub Pages:** open `index.html` in a browser (it needs internet to load its libraries).
  Without Claude, a built-in reader handles text-based PDFs, Excel/CSV and pasted text. It looks for item lines
  with quantity, rate and amount. Scanned PDFs and photos can only be read on claude.ai.
  Editing, comparison and Excel export work everywhere.

Your data is kept in your browser between visits. **Clear all** resets it.
