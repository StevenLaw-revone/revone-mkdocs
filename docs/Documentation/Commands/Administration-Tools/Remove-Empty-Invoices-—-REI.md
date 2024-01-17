# Remove Empty Invoices — REI

>❗ A date range including the current day is not recommended as this can include invoices currently being worked on.

It is possible for errors to result in empty invoices being left in the database. While the system is built to not allow this to occur in normal operation things like the program closing unexpectedly can leave this sort of thing regardless. This command is designed to attempt to clean up these remnants.

![Main](/.attachments/Documentation/RemoveEmptyInvoices.png "Main")

Once the date range is selected the `Load` button will load all the empty invoices in that range.

![Loaded](/.attachments/Documentation/RemoveEmptyInvoices-Loaded.png "Loaded")

These can then be selected for removal or individually selected to use the `Go To` button to inspect in the main window.