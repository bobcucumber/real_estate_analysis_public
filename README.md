# Zillow SRP→Detail Analyzer
Effective date: [2026-01-01]

Overview
This extension analyzes up to three Zillow listings on-demand to compute sale-to-list ratios. It processes data locally in the user’s browser.

Data Accessed
Only when the user clicks “Start/Collect”, the extension may access: listing URLs selected for analysis (up to 3), and relevant Zillow page content needed to compute results (e.g., list price, sale price when available, and school information when available).

How Data Is Used
Data is used only to compute and display results inside the extension.

Storage
Results and a short-lived cache are stored locally using chrome.storage.local. Users can clear stored data via “Clear Cache” or by uninstalling the extension.

Sharing / Selling
The extension does not sell, share, or transmit data to third parties. No external servers are used.

