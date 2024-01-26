# Coupons

Sets coupons (or discounts) for use on invoices.

![Coupons](/.attachments/Documentation/Coupons.png "Coupons")

## Show Inactive

Coupon's have an "Active" flag which can be turned off hiding them from normal use. The Show Inactive checkbox wil show these inactive coupons as grey in the list

![Show Inactive](/.attachments/Documentation/Coupons-ShowInactive.png "Show Inactive")

## Add/Edit

When adding or editing a coupon the coupons details will be enabled. The "is a surcharge" checkbox allows a coupon to be set as a surcharge increasing the price of the item/invoice instead of reducing it.

![Edit](/.attachments/Documentation/Coupons-Edit.png "Edit")

### Promotion

There is a checkbox marked promotion next to the Active checkbox that controls whether or not the function appears in the [Active Promotions](../../Functions/Active-Promotions.md) window.

## Add Rules

Rules can be added to a coupon limiting where they can be used and adding the ability to automatically apply them when they are eligible.

![Add Rules](/.attachments/Documentation/Coupons-AddRule.png "Add Rules")

![Rule List](/.attachments/Documentation/Coupons-RuleList.png "Rule List")

### Rule Types

#### Allows a specific number if Invoice/Items per Customer

This adds a counter that will disable the coupon once it has counted down to zero.

![Specific Number](/.attachments/Documentation/Coupons-SpecificNumber.png "Specific Number")

#### Applies a certain  number of days after Customer Creation (Welcome)

The Welcome promotion type will apply a certain number of days after their record was created for a limited period.

![Days After Creation](/.attachments/Documentation/Coupons-DaysAfterCreation.png "Days After Creation")

#### Applies only to customers that are Route or Counter

If the customer is on a route they are set as route other wise they are a counter customer

![Route or Counter](/.attachments/Documentation/Coupons-RouteOrCounter.png "Route or Counter")

![Route or Counter List](/.attachments/Documentation/Coupons-RouteOrCounterList.png "Route or Counter List")

#### Doesn't apply to items in Category/Sub-Category

This rule allows a number of categories/sub-categories to be excluded from a promotion

![Doesn't Apply to Category/Sub-Category](/.attachments/Documentation/Coupons-DoesntApply.png "Doesn't Apply to Category/Sub-Category")

#### Last Name (starts with)

Customers who's last name starts in the range of letters will be eligible for this coupon.

![Last Name](/.attachments/Documentation/Coupons-Name.png "Last Name")

#### Only applies if they are receiving Promotional Messages

If the customer has permission to receive email or SMS promotional messages they will be eligible for this promotion.

![Promotional](/.attachments/Documentation/Coupons-Promotional.png "Promotional")

#### Only applies to customer/item

> Types: customer on Price List, items with Specific Names, specific Item Categories, or specific Sub-Categories

Limits a coupon to a specific list of items that the coupon will be available for.

![Only Applies](/.attachments/Documentation/Coupons-OnlyApplies.png "Only Applies")

#### Returning Customers

If a customer has been inactive for a certain number of days they will be eligible for this coupon in order to try to get them to return.

![Returning Customers](/.attachments/Documentation/Coupons-ReturningCustomers.png "Returning Customers")

### Rules List

Adding rules will populate them in the list below

![Rules List](/.attachments/Documentation/Coupons-AddedRules.png "Rules List")

Once the rules are saved with `OK` they will be displayed on the coupon details screen on the bottom.

![Rules List Main Window](/.attachments/Documentation/Coupons-AddedRules-Main.png "Rules List Main Window")

## Reset Counter

For coupons with a specific number of uses this will set a new start date and reset all counters.

![Reset Counter Select New Date](/.attachments/Documentation/Coupon-ResetCounter-SelectNewDate.png "Reset Counter Select New Date")

## Update Categories

Coupon Categories are used to better organize the coupons and the `Update Categories` button allows for the management of these categories.

![Update Categories](/.attachments/Documentation/Coupons-UpdateCategories.png "Update Categories")

The checkbox on each item is the default promotion setting that sets the default visibility in the [Active Promotions](../../Functions/Active-Promotions.md) window. The check box on the discount itself overrides this setting.

## Duplicate

This will simply create a new coupon based on the currently selected one.

## Set External Promotion

Links a coupon to a AWS promotion pulled from the AWS settings in the [API Keys](/Documentation/Setup/SuperUser/API-Keys.md) section.

![Set External Promotion](/.attachments/Documentation/Coupon-SetExternalPromotion.png "Set External Promotion")
