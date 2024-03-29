# Database Setup

Editing the Databases requires SuperUser authorization.

![Authorization](/.attachments/Documentation/SetupDatabase-Authorization.png "Authorization")

Once in the setup the information about the database will be shown and the specific database can be selected

![Setup Database](/.attachments/Documentation/SetupDatabase.png "Setup Database")

There are some advanced settings that may not be required for setup.

![Advanced](/.attachments/Documentation/SetupDatabase-Advanced.png "Advanced")

## Add/Edit Employee

It is possible to add or edit employees on the specific database from here. This is basically the same window as the [Setup>Employee File](../Setup/All-Employees/Employee-File.md) in the main setup window.

![Add/Edit Employee](/.attachments/Documentation/SetupDatabase-AddEditEmployee.png "Add/Edit Employee")

## Edit

In the edit mode more options become available.

![Edit Options](/.attachments/Documentation/SetupDatabase-EditOptions.png "Edit Options")

> ❗ Be careful about exported database settings. The password is in clear text and could cause security issues if not deleted once it is finished being used.

| Option | Meaning |
| --- | --- |
| Check | Runs database checks to ensure that the database is setup correctly |
| Add new Database | Adds a new database |
| Export Database Settings | Exports database settings to a CSV file |
| Import Database Setting | Imports database settings from a CSV file | 

### Check Steps

Checking the database makes sure that the database is setup correctly, there are several steps that are by default not checked. These tend to attempt to fix bad existing data and often take a long time to run so they default to inactive.

![Check](/.attachments/Documentation/SetupDatabase-Check.png "Check")

## Change Database

Once there is more than one database saved the option to select what database to use becomes available.

![Change Database](/.attachments/Documentation/SetupDatabase-ChangeDatabase.png "Change Database")