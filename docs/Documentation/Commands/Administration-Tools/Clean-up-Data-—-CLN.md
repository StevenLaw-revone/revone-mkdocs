# Clean Up Data — CLN

A tool to clean up data in the database. Generally for fixing misspellings and alternate spellings (e.g. city and brand names)

![Main](/.attachments/Documentation/CleanUpData01.png "Main")

The two options currently available are Customer City and Brand

![Field Options](/.attachments/Documentation/CleanUpData01-FieldOptions.png "Field Options")

Once the `Find Matches` button is pressed it will search for close matches

![Found](/.attachments/Documentation/CleanUpData02.png "Found")

In this example there are three different spellings of Chestermere.

![Selected](/.attachments/Documentation/CleanUpData03.png "Selected")

Clicking `Correct Selected` will bring up the option to select the correct spelling.

![Spelling Options](/.attachments/Documentation/CleanUpData04.png "Spelling Options")

Here it is clear that for some reason an employee attempted to add the province abbreviation in the City field. As such the correct option would be Calgary without any province abbreviation but that is not available. This is what the Override option is for.

![Spelling Options 2](/.attachments/Documentation/CleanUpData05.png "Spelling Options 2")

The Override option opens a prompt for the correct spelling to be entered manually

![Override](/.attachments/Documentation/CleanUpData06.png "Override")
