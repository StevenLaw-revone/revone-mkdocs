# Multiple Locations — ML

Scan barcodes to set locations to multiple items/invoices at once. As most barcode readers act as keyboards to the software typing in manually works as well

Once the enter key is hit (emulated in the barcode scan) it will advance to the conveyer location. After the next enter is detected it will try to find the item/invoice and check the validity of the location

![Multiple Locations](/.attachments/Documentation/MultipleLocations01.png "Multiple Locations")

If there is an error then an error sound will be made and the error will be shown in red

![Error](/.attachments/Documentation/MultipleLocations-Error.png "Error")

Selecting the line will enable the "Copy selected detail" button which copies the text into the clipboard

![Error — Select](/.attachments/Documentation/MultipleLocations-Error-Select.png "Error — Select")

While this error is unlikely to be needed later a more complicated error could show up

```
test is not a valid barcode.
```

If the addition is valid a success noise will be played instead and the information will be added to the top of the list

![Success](/.attachments/Documentation/MultipleLocations-Success.png "Success")

Closing the window will finish the process