# View Tag Status/View Invoice Status — VTS/VIS

View Tag Status (VTS) pulls the main window without any pre-set search while View Invoice Status (VIS) pre-sets an invoice search for the currently loaded invoice

## Search types

It is possible to search by Tag, Invoice number, or Customer using the top three buttons (F2, F3, F4). The VIS version of the command skips this and jumps directly to searching by invoice using the currently displayed invoice.

![image.png](/.attachments/Documentation/ViewTagStatus01.png)

## Search

Once the search is initiated it will pull up all the tags that match the criteria up to the selected limit.

![image.png](/.attachments/Documentation/ViewTagStatus02.png)

## View Search Log

View Search Log displays a list of history on the current search in a different screen.

![image.png](/.attachments/Documentation/ViewTagStatus06.png)

## Load Tag History

Load Tag History will load the history of the selected tag from the database. The command timeout is disabled for this request as the search can take a significant amount of time (upwards of 10 minutes) as such this procedure comes with a time elapsed indicator and a cancel button in case the search needs to be aborted to allow for other work to be done.

![image.png](/.attachments/Documentation/ViewTagStatus03.png)

Once the search is complete the history will displayed in the bottom half of the screen.

![image.png](/.attachments/Documentation/ViewTagStatus04.png)

This table is large enough to require a horizontal scrollbar to display the rest of the data.

![image.png](/.attachments/Documentation/ViewTagStatus05.png)

## Invalidate Tag

Invalidates the tag on the database to allow [Heat Seal Tags](/Documentation/Functions/Heat-Seal-Tags.md) to be reused.

## Search For Status

Limits the history search to a specific status to search for. The most common one is likely to be the "Confirmation of bagging" which indicates the exact time that the bagger confirmed the garment was loaded.

![image.png](/.attachments/Documentation/ViewTagStatus07.png)