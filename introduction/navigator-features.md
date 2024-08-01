# Navigator features

There are several features and behaviors that are common for all ERP.net Web Client navigators.

## Default sorting

If you haven't customized the view of a document navigator in any way, or if you have reset your current view's settings to default, they will be sorted by **Document Date** in a descending order.

This is done for convenience, as it allows you to see the documents which were most recently created first.

![Pictures](pictures/default_sorting.png)

## Accessing records

In most navigators, you can access a document or a record through the value of its **first** column, regardless of which column that is.

Values displayed in the rows of that column are accessible through **hyperlinks** leading exactly to the document they represent.

> [!NOTE]
> Certain navigators don't support opening links and therefore don't have this feature enabled.

![Pictures](pictures/hyperlinks_first_column.png)

You can alternatively access the document form of a record:

1. By clicking on it, then expanding its **Details** panel and finally clicking on the **Open** button
2. By clicking on its **icon** positioned in the **System column** at the far-left.

> [!NOTE]
> The **System column** always contains a quick-access button for the respective record and its position cannot be modified

![Pictures](pictures/access_document_twoways.png)

## Navigator menu

Each navigator features its own dedicated **Menu** through which you can perform the following:

* Determine the security type of each navigator record by configuring **access permissions**
* Build and apply **advanced filters**
* Use ERP.net's dedicated **AI Asssistant** (upcoming)
* Take advantage of **side panels** that reveal additional data and attachments for each selected document
* Use **[functional panels](./how-to/functional-panels/index.md)** to speed up the process of filling out a document
* Expand **detail panels** to see information relevant for each selected record of the navigator (e.g. its Document Lines)
* Create **tiles** to save and later easily access a specific navigator view
* **[Customize](https://docs.erp.net/webclient/introduction/how-to/ui-customization/access-to-views.html)** the navigator form by enabling, disabling, reordering and renaming its panels and widgets.
* [**Hierarchy**](#Hierarchy): The Side Panel for hierarchical references streamlines filtering and viewing of hierarchical data by displaying its structure

![Pictures](pictures/Menu_view_01_08.png)

### Hierarchy 

A **Side Panel** for hierarchical references in navigators, designed to streamline the filtering and viewing of hierarchical data.

![Pictures](pictures/Hierarchy_menu_01_08.png)

The **Side Panel** displays the hierarchical structure of data, allowing users to click through different levels to filter and access related records efficiently.

![Pictures](pictures/Hierarchy_view_01_08.png)

> [!NOTE]
> Hierarchical references are organized into submenus if there are multiple references; single references display directly in the **Side Panel**. The feature uses the **Strategy Pattern** for flexibility and robustness, and sub-menus help manage numerous options more effectively.

![Pictures](pictures/Hierarchy_Note_01_08.png)

## Panel menu

Panels and widgets enabled in a navigator have a separate **Menu button** accessible at their top-right corners.

It features the ability to:

* **Maximize** the panel to take up the entire screen
* **Reload** the panel to reflect the most up-to-date information
* Quickly create a **new** record of one or more respective types
* **Search** the contents of the respective panel
* Take advantage of handy advanced features like the **[Grouping panel](https://docs.erp.net/webclient/introduction/my-apps/documents.html#show-grouping-panel)** and **[Filter row](https://docs.erp.net/webclient/introduction/how-to/filtering-expressions.html)**
* Select **multiple** records from the panel
* Create a **.xlsx file** containing all records of the panel
* Limit the **row counts** of the panel to a specific number
* **[Customize](https://docs.erp.net/webclient/introduction/how-to/ui-customization/customize-fields.html)** the panel by enabling, disabling, reordering and renaming its columns.

![Pictures](pictures/panel_menu.png)

### Multi select

Whenever you select multiple records using the **Multi select** feature, a new **Selected** count button will appear on the navigator's ribbon.

It allows you to **export** the selected records as .xlsx files

![Pictures](pictures/multiselect.png)

### Group by column headers

With the help of the **[Show grouping panel](https://docs.erp.net/webclient/introduction/my-apps/documents.html#show-grouping-panel)**, you can also group a navigator's records based on one or more column headers.

Such groups can be used to organize records by type, state, the month they were created on, etc.

![Pictures](pictures/group_by_headers.png)

## Row context menu

If you **right-click** on a particular row, you will expand a dropdown menu with one or more of the following options:

* **Open** the row's associated record
* Apply an **advanced filter** affecting the entire panel, using this particular row as source (e.g. documment currency)
* Access the **form definition** of the row (only for fields that can be defined).

![Pictures](pictures/row_context_menu.png)

## Column context menu

If you **right-click** on a particular column, you will expand a dropdown menu with the following options:

* **Sort** the column's contents by ascending or descending order
* **Clear** the sorting, restoring the column view to default
* **Group** the records of the column by specific criteria like character count, word count, etc.
* **[Summarize](https://docs.erp.net/webclient/introduction/my-apps/documents.html#summary)** columns using functions like Summary and Distinct
* Restore the column's **default width**
* **Hide** the column from view (can be re-enabled through the Panel customization Menu)

![Pictures](pictures/column_context_menu.png)

### Group by intervals

Depending on the type of a column (e.g. Date, Number, Document Type), you can perform more specific grouping operations.

This is achieved through **intervals** such as character counts and time periods.

**Example:**

We can apply a rule where records will be grouped by the year indicated in their Document Date column.

As a result, the entire panel will be divided into "year" groups that include records created in the respective year.

![Pictures](pictures/group_by.png)

### Group context menu

If you **right-click** on a particular column with a group filter applied, you can expand a dropdown menu with the following unique options:

* **Sort** the respective groups based on the column in ascending or descending order
* **Expand** and **collapse** all groups at once
* Change the **group interval** applied on the column
* Perform **Summary** functions on all groups 

#### Sort summarized groups

If a Summary function is applied on a column, you can use it to **sort** existing groups.

Groups can be sorted based on their own column or by columns which have summary functions applied.

![Pictures](pictures/sort_groups.png)

> [!NOTE]
> The screenshots for this article are from v24 of the Web Client.
