# Find Duplicates — FDC

Finds duplicate customer records and opens the ability to join them to similarly named customers. This uses a fuzzy compare function that generates a similarity rating and compares it to a threshold. This is to allow customers with spelling errors and typos to be compared.

![Main](/.attachments/Documentation/FindDuplicateCustomers01.png "Main")

The find function requires a button press so that the threshold and years since last in can be set before undertaking the rather lengthy comparison process

![Find Duplicates](/.attachments/Documentation/FindDuplicateCustomers02.png "Find Duplicates")

Once duplicates are found they will be listed with the number of different customer records found

![Duplicates](/.attachments/Documentation/FindDuplicateCustomers03.png "Duplicates")

Clicking the `+` button will open a list of the records found allowing them to be selected for joining

![Details](/.attachments/Documentation/FindDuplicateCustomers04.png "Details")

There are several conditions that make joining impossible without further work and a popup will be displayed if this is found

![Has Routes](/.attachments/Documentation/FindDuplicateCustomers-Route.png "Has Routes")
