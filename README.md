# GSTReportGenerator
GSTReportGenerator - Here reports from all eCommerce platforms will be given as input. Final Consolidated report will be generated automatically
Here's a quick summary of what the IBI GST Report Generator has grown into:
What was built:

Single HTML file, fully self-contained, hosted on GitHub Pages
Processes Amazon, Flipkart, Meesho, ShopClues data in one click
Generates all GSTR-1 tables in correct order with correct values
Exports to Excel (Download) and Google Sheets (Send to Sheets)

Key accuracy features:

B2B POS derived from buyer GSTIN state — not delivery address
Table 12 HSN is NET (refunds deducted) matching Table 14 ECO Net
Table 9B Registered uses invoice's own tax ratio to prevent negative IGST
Table 13 correctly counts Shipment + Cancel rows, excludes Refund rows
Daman → 26-Dadra and Nagar Haveli and Daman and Diu
Zero-taxable HSN rows filtered out automatically
