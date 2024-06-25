# Navigators features

In this step-by-step guide, we will showcase several features and behaviors that are common to all ERP.net Web Client navigators.

## Default sorting

If you haven't customized the view of a document navigator in any way, or if you have reset your current view's settings to default, they will be sorted by **Document Date** in a descending order.

This is done for convenience, as it allows you to see the documents which were most recently created first.

## Accessing records

In most navigators, you can access a document or a record through the value of its **first** column, regardless of which column that is.

Values displayed in the rows of that column are accessible through **hyperlinks** leading exactly to the document it represents.

> [!NOTE]
> Certain navigators don't support opening links and therefore don't have this feature enabled.

You can alternatively access the document form of a record:

1. By clicking on it, then expanding its **Details** panel and finally clicking on the **Open** button
2. By clicking on its **icon** positioned in the **system column** at the far-left.

> [!NOTE]
> The System column always contains a quick-access button for the respective record and its position cannot be modified

## Navigator menu

Each navigator features its own dedicated **Menu** through which you can perform the following:

* Determine the security type of each navigator record by configuring **access permissions**
* Build and apply **advanced filters**
* Use ERP.net's dedicated **AI Asssistant** (upcoming)
* Take advantage of **side panels** that reveal additional data and attachments for each selected document
* Use **functional panels** to speed up the process of filling out a document
* Expand **detail panels** to see information relevant for each selected record of the navigator (e.g. the Document Lines)
* Create **tiles** to save and later easily access a specific navigator view
* **[Customize](https://docs.erp.net/webclient/introduction/how-to/ui-customization/access-to-views.html)** the navigator form by enabling, disabling, reordering and renaming its panels and widgets.

## Panel menu

Panels and widgets enabled in a navigator have a separate **Menu button** accessible at their top-right corners.

It features the ability to:

* **Maximize** the panel to take up the entire screen
* **Reload** the panel to reflect the most up-to-date information
* Quickly create a **new** record of one or more respective types
* **Search** the contents of the respective panel
* Take advantage of handy filtering features such as the **[Grouping panel](https://docs.erp.net/webclient/introduction/my-apps/documents.html#show-grouping-panel)** and **[Filter row](https://docs.erp.net/webclient/introduction/how-to/filtering-expressions.html)**
* Select **multiple** records from the panel
* Create a **.xlsx file** containing all records of the panel
* Limit the **row counts** of the panel to a specific number
* **[Customize](https://docs.erp.net/webclient/introduction/how-to/ui-customization/customize-fields.html)** the panel by enabling, disabling, reordering and renaming its columns.

## Row context menu

If you **right-click** on a particular row, you will expand a dropdown menu with one or more of the following options:

* **Open** the row's associated record
* Apply an **advanced filter** affecting the entire panel, using this particular row as source (e.g. documment currency)
* Access the **form definition** of the row (only for fields that can be defined).

## Column context menu

If you **right-click** on a particular column, you will expand a dropdown menu with the following options:

* **Sort** the column's contents by ascending or descending order
* **Clear** the sorting, restoring the column view to default
* **Group** the records of the column by specific criteria like character count, word count, etc.
* **[Summarize](https://docs.erp.net/webclient/introduction/my-apps/documents.html#summary)** applicable column records to get important insights
* Restore the column's **default width**
* **Hide** the column from view (can be re-enabled through the Panel customization Menu)

### Multi-export

Whenever you select multiple records using the **Multi select** feature, a new **Selected** count will appear on the navigator's ribbon.

It allows you to **export** the selected records as .xlsx files

### Grouping by intervals

Depending on the type of the column (e.g. Date, Number, Document Type), you can perform specific grouping functions.

This is achieved through specific **intervals** such as character counts and time periods.

**Example:**

We can apply a rule where records will be grouped by the first two characters of each row of a column.

As a result, only records containing these characters will be grouped.

### Grouping by column headers

With the help of the **[Show grouping panel](https://docs.erp.net/webclient/introduction/my-apps/documents.html#show-grouping-panel)**, you can also group a navigator's records based on a key parameter visualized by its respective column title.

Such groups can be used to organize records by type, state, the month they were created on, etc.

### Group context menu

If you **right-click** on a particular column header in the Show grouping panel, you will expand a dropdown menu with one or more of the following options:

* **Expand** and **collapse** all groups of the navigator at once
* Additionally **group** the panel's contents by different intervals
* **Sort** all groups by their totals
* Perform **Summary** functions on all groups, which reveals how many entries in them are count and/or distinct
* Restore the **default width** of the column that is now used as a grouping column header
* **Hide** the column header, which disables it from the Show grouping panel and the navigator itself

> [!NOTE]
> The screenshots for this article are from v24 of the platform.