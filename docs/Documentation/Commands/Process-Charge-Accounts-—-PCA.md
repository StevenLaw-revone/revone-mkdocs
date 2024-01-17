# Process Charge Accounts — PCA

Charge a customer for all the invoices in a specific time range

![Main](/.attachments/Documentation/ProcessCardAccounts.png "Main")

The Frequency Type is a Manager Property in the customer setup used to separate customers into different groups. Here the separation is how frequently the statement needs to be generated

![Frequency Types](/.attachments/Documentation/MonthlyChargeAccounts-FrequencyType.png "Frequency Types")

The setting is in Manager Properties at the bottom of the following screenshot

![Customer Setting](/.attachments/Documentation/MonthlyChargeAccounts-ChargeAccountFrequency.png "Frequency Types")

The full list of options is available to be set in the Setup>Charge Account Frequencies tab

![Setup — Change Charge Account Frequencies](/.attachments/Documentation/MonthlyChargeAccounts-Setup-ChargeAccountFrequencies.png "Setup — Change Charge Account Frequencies")

The `+` Button beside the month allows for a more specific date range to be selected

![Specific Date Range](/.attachments/Documentation/ProcessCardAccounts-SpecificDateRange.png "Specific Date Range")

Once the Load Data button is pressed all the eligible invoices are loaded

![Loaded](/.attachments/Documentation/ProcessCardAccounts-Loaded.png "Loaded")

Clicking on the `+` button beside the customer will open a detal list with the invoices that are to be paid

![Details](/.attachments/Documentation/ProcessCardAccounts-Details.png "Details")

### Process Payments

Iterates through the list of selected customers and pays their invoices using a single lump payment to their on file card

### Change Credit Card

Changes the on file card

### Send Expiry Emails

Searches through the list of customers for ones with an expired card and sends an email warning about the expiry to their selected contact

### Print Unpaid

Loads a report of the customers and their invoices and sends it to the printer

### Clear $0 Customers

Marks all invoices for customers currently owing $0 to be paid and picked up

### Send Declined Messages

Sends a Declined Card Message to any selected customer who's card was declined while processing

### Mark Resolved

Marks any error under the selected customers as inactive