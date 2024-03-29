# SMS Suppression Report — SSR

Loads a list of customers with cellphones matching items on the Opt Out list in the AWS.

The loading procedure cannot show the total amount of items on the list due to how the Opt Out list works on AWS so it simply shows how many items have been pulled so far.

![Loading](/.attachments/Documentation/SmsSuppressionReport-Loading.png "Loading")

Once the items have loaded they are displayed in a list.

![Main](/.attachments/Documentation/SmsSuppressionReport.png "Main")

An item can be selected and the cellphone number edited from this screen.

![Edit Cellphone](/.attachments/Documentation/SmsSuppressionReport-EditCellphone.png "Edit Cellphone")

It will not allow the new cellphone to match the current one.

![Error](/.attachments/Documentation/SmsSuppressionReport-Error.png "Error")

## Export Raw Suppressions

Prompts the user to save the Opt Out list to a CSV file.

## Save Suppression Flags

Saves a flag to the customer indicating that the customer's cellphone number is suppressed.

## Reload

Reloads the list to account for changes to the database.

## Go To Customer 

Jumps to the customer in question so that more information can be inspected/edited

