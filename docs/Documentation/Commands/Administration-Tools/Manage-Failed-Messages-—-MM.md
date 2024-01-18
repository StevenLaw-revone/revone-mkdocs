# Manage Failed Messages — MM

Pulls a list of messages that failed to send based on if there is an error in the record.

![Main](/.attachments/Documentation/ManageFailedMessages.png "Main")

If there are failed messages they can be expanded using the `+` button.

![Expanded](/.attachments/Documentation/ManageFailedMessages-Expanded.png "Expanded")

Here there is the parameters of the message in JSON format (the block of text surrounded by curly braces `{}`) followed by the error message `No Domain` indicating that in this case the domain of the email was missing (the part of the email after the `@` symbol)

## Edit

The message's customer's contact info and contact preferences can be edited here.

![Edit Contact Info](/.attachments/Documentation/ManageFailedMessages-EditContactInfo.png "Edit Contact Info")

## Delete

Deletes the message so that it is cleared from the queue.

## Refresh

Updates the list in case more errors have occurred while the window has been open.

## Retry Message

Retries sending the message.