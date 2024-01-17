# Re-Scan Inventory — RSI

Used to get an accounting of the invoices/bags that are expected in the store versus what is actually in store

![Main](/.attachments/Documentation/ReScanInventory.png "Main")

This is intended for use with a barcode reader so when the reader's scan is complete it should produce an enter key stroke and move to the second entry then add the item and how it was found

![Scan](/.attachments/Documentation/ReScanInventory-Scan.png "Scan")

There are seven statuses that items can be found in

| Status | Meaning |
| --- | --- |
| Found | The item was found where it was expected |
| Added in Re-Scan | The item was not listed in a location so it was added to that location in the database |
| Was Listed in a different Location | The invoice was listed in a different location in the database so the database value was changed |
| Missing | The item was expected to be in store but was not scanned. It may have fallen off the rack or some other reason. This is added after the close button is pressed and the "Close and save" option is selected |
| Different Store | The invoice was listed with a prefix that doesn't match the current store |
| Picked Up | This invoice was marked as picked up but was found in store so the pickup status was removed and the location set to the scanned one |
| Written Off | This item had been previously been marked as written off by an employee. The written off status has been removed and the location changed to the scanned one |

Any error that occurs is accompanied by an error sound as well as a red error entry in the scan list

![Error](/.attachments/Documentation/ReScanInventory-Error.png "Error")

On pressing the Close button a set of options are presented

| Option | Action |
| --- | --- |
| Save for Later | Saves the current progress without completing it so that the re-scan can be picked up later |
| Complete and save | Completes the report searching the database for items that are missing and adding them before saving | 
| Discard | Discards the current report and deletes any saved items in the report |
| Cancel | Cancels the close operation and returns to the main Re-Scan window |

![Close](/.attachments/Documentation/ReScanInventory-Close.png "Close")