# API Keys
<span style="font-size:.8rem;opacity:.8">Updated 2024-05-13 version 0.3.1028</span>


Set keys for external APIs.

![API Keys](../../../.attachments/Documentation/ApiSettings.png "API Keys")

## Edit AWS Pinpoint email templates.

Allows editing the AWS templates from inside the POS system

![Edit AWS Templates](../../../.attachments/Documentation/ApiSettings-EditAwsTemplates.png "Edit AWS Templates")

## Load Bulk Profiles — Klaviyo

When customer profiles have been uploaded in bulk through CSV the profile IDs need to be pulled and associated back with the customers. This button will pull the current list of profiles from Klaviyo and associate them with customers with matching Customer IDs. It will then display the number of profiles that were pulled and the number that were loaded.

![Load Bulk Profiles — Result](../../../.attachments/Documentation/ApiSettings-LoadKlaviyoProfiles.png "Load Bulk Profiles — Result")

 The loaded amount is generally going to be lower than the number of customers due to split profiles and the admin account having it's own profile that doesn't match with any customer.