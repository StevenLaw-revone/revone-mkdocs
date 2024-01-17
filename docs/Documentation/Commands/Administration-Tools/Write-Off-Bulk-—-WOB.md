# Write Off Bulk — WOB

Allows all un-picked up invoices with an item with only `Missing` linked in [Re-Scan Inventory](/Documentation/Commands/Re%252DScan-Inventory-—-RSI.md) reports to be marked written off at once.

> If the item has a missing status on one report and a found in different store on a different report is will not be counted as missing as it was missing from one store but found in a different one. As such if there is an incomplete report it may select items that are not actually missing.

When the command first opens it will open a parameters window to select the date range, stores, and routes to search in.

![Parameters](/.attachments/Documentation/WriteOffBulk-Parameters.png "Parameters")

The list of invoices with missing items will be displayed and can be used to select which invoices need to be written off.

![Main](/.attachments/Documentation/WriteOffBulk.png "Main")