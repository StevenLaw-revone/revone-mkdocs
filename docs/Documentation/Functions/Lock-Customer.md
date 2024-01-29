# Lock Customer

If a customer hasn't been paying their bills it can be useful to lock them out from creating any new invoices until the lock is cleared

## Locking the customer

Locking the customer can be done in either:

- [Process Charge Accounts](../Commands/Process-Charge-Accounts-—-PCA.md#lock-customers-with-errors)
- [Process Card Errors](../Commands/Process-Card-Errors-—-PCE.md#lock-customer)
- Manager Properties in the customer edit screen

![Manager Properties](../../.attachments/Documentation/LockCustomer-ManagerProperties.png "Manager Properties")

In the manager properties you can select a preset reason to set a lock or the `-` to remove an existing lock.

![Manager Properties Reasons](../../.attachments/Documentation/LockCustomer-ManagerProperties-Reason.png "Manager Properties Reasons")

## Displaying the reason

When a customer is locked a 🔒 will be displayed on the customer.

Beside the name in the customer summary.

![Customer Summary](../../.attachments/Documentation/LockCustomer-CustomerSummary.png "Customer Summary")

Beside the id in the edit screen.

![Edit Screen](../../.attachments/Documentation/LockCustomer-EditScreen.png "Edit Screen")

Beside the customer in the PCE screen.

![PCE Locked](../../.attachments/Documentation/LockCustomer-PCE-Locked.png "PCE Locked")

Clicking on this symbol will display a popup with reason for the lock and the time that the lock was created.

> The "(9) Starts with 9" error is an internal testing error

![Reason](../../.attachments/Documentation/LockCustomer-Reason.png "Reason")

## Effect

The only thing prevented when locked is creating a new invoice.

![New Invoice](../../.attachments/Documentation/LockCustomer-NewInvoice.png "New Invoice")

