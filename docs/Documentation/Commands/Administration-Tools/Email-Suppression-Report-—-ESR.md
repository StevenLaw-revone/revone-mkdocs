# Email Suppression Report — ESR

Pulls down a comparison of the Email Suppression list from the Amazon Web Services API with existing emails in active customers.

The API Settings are found in Setup>API Keys which requires SuperUser authorization

![API Settings](/.attachments/Documentation/EmailSuppressionReport-ApiSettings.png "API Settings")

Once the report is loaded it will display all customers who's email has bee suppressed

![Main](/.attachments/Documentation/EmailSuppressionReport.png "Main")

![Buttons](/.attachments/Documentation/EmailSuppressionReport-Buttons.png "Buttons")

## Edit Email

If the email is a typo then it can be edited from within the window

![Edit Email](/.attachments/Documentation/EmailSuppressionReport-EditEmail.png "Edit Email")

The new email must be different from the original one

![Same Email](/.attachments/Documentation/EmailSuppressionReport-SameEmail.png "Same Email")

## Export Raw Suppressions

The raw suppression list can be exported to a CSV file

## Save Suppression Flags

Save the suppression to the customer's data allowing it to be seen by employees for correction when interacting with the customer

In the customer summary

![Suppressed Flag — Summary](/.attachments/Documentation/EmailSuppressionReport-SuppressedFlag.png "Suppressed Flag — Summary")

In the customer's edit page

![Suppressed Flag — Edit](/.attachments/Documentation/EmailSuppressionReport-Edit-SuppressedFlag.png "Suppressed Flag — Edit")

Clicking on the email in the summary or the suppressed flag in the edit window will show a short explanation of the suppression

![Suppression Reason](/.attachments/Documentation/EmailSuppressionReport-SuppressionReason.png "Suppression Reason")
