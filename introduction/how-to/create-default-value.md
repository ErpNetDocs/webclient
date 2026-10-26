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

![picture](menu.png)

5. In the dialog, review the field and value you are about to save.
6. Select any conditions that should restrict when the default applies—for example, the current user, role, enterprise company, company location, language, or sales order document type. Only the conditions you select will restrict the default.

- If you do not any conditions - "All cases", "A-Racing Ltd" becomes an unconditional default that can be applied when a new sales order of any document type is created. 
- If you select conditions, it applies when the relevant context matches them.

7. Select OK to save it.  (docs.erp.net)

![picture](conditions.png)

Example: To use Tiramisu Ltd. only for a particular sales order document type, select the document type condition before clicking OK. To use it without a document-type restriction—or any other context restriction—leave all conditions unselected. The saved setting belongs to Entity Attribute Default Values. 
