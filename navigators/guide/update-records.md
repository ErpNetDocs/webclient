# Update records

The "Update records" function allows you to apply changes to multiple records directly from the navigator. Instead of editing existing records one by one, you can prepare or paste updated data into the navigator and apply all changes with a single command.
It is equal to function "Merge" in WinClient.

During the operation, the system matches the prepared rows with existing records using the entity's primary key. If a matching record is found, it is updated with the new values. If no matching record exists, a new record is created automatically.

This is especially useful when importing or copying predefined data into the navigator, allowing you to update existing records efficiently while creating new ones only when necessary.

> [!Note]
> The Update function is intended for mass updates. Unlike Save, which stores the current state of edited records, Update treats the pasted rows as the source
> of an update operation. Existing records are matched by their primary key and updated accordingly, reducing the risk of creating duplicate records during bulk
> data modifications.

## Prerequisite

Before running "Update records", make sure the navigator displays all columns whose values you want to update.

The Update function only processes the columns that are currently visible in the navigator. Hidden columns are ignored, even if they are present in the pasted data. If you want to update a particular field, display its corresponding column before executing the operation.

