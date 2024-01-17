# Customer Editing

A customer's profile is managed here.

![](/.attachments/Documentation/Customer.png "")

## Address Autocomplete

When typing in an address it will attempt to autocomplete using the Google API in [API Keys](../Setup/SuperUser/API-Keys.md).

![AutoComplete](/.attachments/Documentation/Customer-AutoComplete.png "AutoComplete")

Clicking on one of the suggestions will fill out the rest of the field with the results.

![AutoComplete Done](/.attachments/Documentation/Customer-AutoComplete-Done.png "AutoComplete Done")

## Billing Address

A separate billing address can be save when the bill is to be sent to a different address than the garments are to be sent to.

![Use Billing Address](/.attachments/Documentation/Customer-UseBillingAddress.png "Use Billing Address")

![Billing Address](/.attachments/Documentation/Customer-BillingAddress.png "Billing Address")

## Distance Matrix

> ❗ Not fully implemented

A distance matrix value can be calculated on an address getting the distance from the main depot set in the Route Origin Address in [Setup>System](../Setup/Manager/System.md). This to be used in the route calculation system.

![Distance Matrix](/.attachments/Documentation/Customer-DistanceMatrix.png "Distance Matrix")

![Distance Matrix Button](/.attachments/Documentation/Customer-DistanceMatrix-Button.png "Distance Matrix Button")

Once the load button is pressed the API will attempt to validate the address. It can sometimes be wrong so it is a good idea to verify that the address found matches.

![Distance Matrix Address Check](/.attachments/Documentation/Customer-DistanceMatrix-AddressCheck.png "Distance Matrix Address Check")

![Distance Matrix Loaded](/.attachments/Documentation/Customer-DistanceMatrix-Loaded.png "Distance Matrix Loaded")

## Email Validation

Send an validation Email to a customer to ensure that the email is set correctly.

![Email Validation](/.attachments/Documentation/Customer-EmailValidation.png "Email Validation")

![Email Validation Complete](/.attachments/Documentation/Customer-EmailValidation-Complete.png "Email Validation Complete")

## Manager Properties

Some properties need to have manager approval to change so the manager properties section is locked down with a requirement for an administrator password.

![Manager Properties](/.attachments/Documentation/Customer-ManagerProperties.png "Manager Properties")

Once in the manager properties it is possible to cancel with the cancel button.

![Manager Properties Cancel](/.attachments/Documentation/Customer-ManagerProperties-Cancel.png "Manager Properties Cancel")