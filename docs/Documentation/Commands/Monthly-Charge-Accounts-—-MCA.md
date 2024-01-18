# Monthly Charge Accounts — MCA

Used to generate statements, and statement discounts, for customers.

## Parameters

The frequency type and invoice date range need to be selected before any statement is generated. The month drop down will set the Start and End dates to the specified month (if the month hasn't occurred yet it will set to that month last year)

![Parameters](/.attachments/Documentation/MonthlyChargeAccounts-Parameters.png "Parameters")

The Frequency Type is a Manager Property in the customer setup used to separate customers into different groups. Here the separation is how frequently the statement needs to be generated

![Frequency Types](/.attachments/Documentation/MonthlyChargeAccounts-FrequencyType.png "Frequency Types")

The setting is in Manager Properties at the bottom of the following screenshot

![Customer Setting](/.attachments/Documentation/MonthlyChargeAccounts-ChargeAccountFrequency.png "Frequency Types")

The full list of options is available to be set in the Setup>Charge Account Frequencies tab

![Setup — Change Charge Account Frequencies](/.attachments/Documentation/MonthlyChargeAccounts-Setup-ChargeAccountFrequencies.png "Setup — Change Charge Account Frequencies")

![Buttons](/.attachments/Documentation/MonthlyChargeAccounts-Buttons.png "Buttons")

## Generating Statements

Once in the main MCA window you need to select the customers that you want to send the statements to

![Main](/.attachments/Documentation/MonthlyChargeAccounts.png "Monthly Charge Accounts")

This icon ![Email](/.attachments/Documentation/MonthlyChargeAccounts-Email.png "Email") means that the customer is setup to receive emailed statements while this one ![Print](/.attachments/Documentation/MonthlyChargeAccounts-Print.png "Print") means that the statement will need to be saved and likely printed to had to the customer.

The Create Statement Discount button when checked will create a statement discount invoice if the customer has a statement discount setup. This is a negative amount invoice that records the discount across the entire statement

The "Save email statements instead of sending" button will instead create the file for all customers even ones set up to receive emailed statements. This allows a statement to be created without sending to the customer

## Send Check Spam Folder Email

This sends a simple email using a template in setup to ask the customer to check their spam folder page as some email providers filter emails with attachments to spam