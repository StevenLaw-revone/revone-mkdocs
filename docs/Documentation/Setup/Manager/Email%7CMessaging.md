# Email/Messaging

Settings for email and SMS messaging.

The Use Local setting is for testing purposes. The Other messaging settings are duplicates of the ones in the [Credit Card](/Documentation/Setup/Manager/Credit-Card.md) setting. The message template settings allow specific message types to be disabled.

![Email/Messaging](/.attachments/Documentation/Email.png "Email/Messaging")

You can test the settings by sending a test email.

![Test Email](/.attachments/Documentation/Email-TestEmail.png "Test Email")

A success should show a message like below and failure should display the specific error message.

![Success](/.attachments/Documentation/Email-TestEmail-Success.png "Success")

Email templates can also be set here.

![Email Templates](/.attachments/Documentation/Email-EmailTemplates.png "Email Templates")

Templates are setup with the name of the subject of the email in an html comment at the top (the `<!--Statement Ready-->` below would set the subject as "Statement Ready") and the body follows in HTML format with parameters set in curly braces like `{AddressHeader}`.

![Email Templates — Example](/.attachments/Documentation/Email-TemplateExample.png "Email Templates — Example")