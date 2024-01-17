# Messaging

Messages are periodically sent to customers on various triggers using the AWS Pinpoint API setup in [API Keys](../Setup/SuperUser/API-Keys.md).

| Message | Trigger | Description |
| --- | --- | --- |
| New Customer | New customer created | A welcome message to indicate that the customer was successfully setup in the database and that the contact succeeded |
| Order Ready | Counter customer's order has all sub invoices set to a location | Alerts the customer that an order is ready to pick up | 
| Order Delivery | Route customer has items scanned in [Multiple Pickup — MU](../Commands/Multiple-Pickup-—-MU.md) | Alerts the customer that items are on the way |
| Card Declined | Card on file transaction is declined | Alerts customer of error in a transaction |
| Card Expiry | Send Expiry Emails button in [Process Charge Accounts — PCA](../Commands/Process-Charge-Accounts-—-PCA.md) | Alerts the customer that their card is either expired or about to expire |
| Delivery Issue | ❗ _Removing pickup date? not sure why_ | Indicates that there was an issue with the delivery |
| Garment Issue | On saving a garment issue | Alerts the customer that an issue with the garment has been found and logged. |

[Email/Messaging](../Setup/Manager/Email%257CMessaging.md)