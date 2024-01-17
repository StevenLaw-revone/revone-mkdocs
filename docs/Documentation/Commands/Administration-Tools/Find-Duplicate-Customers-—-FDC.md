# Find Duplicate Customers — FDC

Used to find duplicate customers based on name similarity to attempt to join customers with potential misspellings

![image.png](/.attachments/Documentation/FindDuplicateCustomers01.png)

### Similarity Threshold

This function relies on using a fuzzy comparison routine that produces a similarity rating between 0 and 100 for how similar two names are. The threshold is the level above which the customers will be considered to have similar names. If the number is lowered there will be more false matches but bigger spelling mistakes are likely to be found.

In order to search for matches the `Find Duplicates` button must be pressed as the process can take quite a while.

![image.png](/.attachments/Documentation/FindDuplicateCustomers02.png)

Once the search has completed the list of matches will be displayed grouped by the first match with the number of matches shown. Clicking on the `+` button will open the list of matches.

![image.png](/.attachments/Documentation/FindDuplicateCustomers03.png)

In hte list of matches the individual customers will be listed with check boxes to allow the customers to be selected for joining

![image.png](/.attachments/Documentation/FindDuplicateCustomers04.png)

Once the customers to join have been selected the `Join Selected Customers` button can be pressed to start joining.