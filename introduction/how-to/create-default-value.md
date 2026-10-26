# Default attribute value*

*also known as "Entity attribute default value", "Default value"

In the Web Client, you can save a field’s current value as a default. The setting is stored in System/Internal system data/**Entity Attribute Default Values**

## Prerequisites: 

To access "Default attribute value"—including "Set as default attribute value" and "Manage default attribute value"—the user must meet both requirements:

- Be a member of a user group granted the Global Layout Manager system permission - this permission is managed through the Desktop client
- Have Is Layout Admin enabled for their current user–role assignment - may be managed through the WEB client

If either requirement is not met, the options are not available. 

## Create new default attribute value

The examples here are carried on a Sales Order - Customer field.

1. Open a new Sales Order in the Web Client - document type "Sales Order"
2. Select a record for the Customer field, e.g. "A-Racing Ltd"
3. Open the Customer field’s three-dot context menu.
4. Select **Default attribute value** → **Set as default attribute value.**

![picture](./pictures/menu.png)

5. In the dialog, review the field and value you are about to save.
6. Select any conditions that should restrict when the default applies—for example, the current user, role, enterprise company, company location, language, or sales order document type. Only the conditions you select will restrict the default.

- If you mark "For all cases" -no conditions, "A-Racing Ltd" becomes an unconditional default that can be applied when a new sales order of any document type is created. 
- If you mark "For specific cases" and select conditions, the value applies when the chosen conditions are met.

  Let us choose conditions per Role and per Document type.

7. Select OK to save the Default attribute value.
   
![picture](./pictures/conditions.png)

This creates a record in table "Entity Attribute Default Values". 

This value is next applied when the values are met at the creation of a new Sales order. In the example Customer will be autimatically set to "A-Racing Ltd" when a new order of document type "Sales Order" is created, by a user whose role is "X-Tech MI Role".
If an order of a dfferent document type is created, the Customer will be empty (as normal).

