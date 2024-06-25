# Navigators features

In this step-by-step guide, we will showcase several features and behaviors that are common to all ERP.net Web Client navigators.

## Default sorting

If you haven't customized the view of a document navigator in any way, or if you have reset your current view's settings to default, they will be sorted by **Document Date** in a descending order.

This is done for convenience, as it allows you to see the documents which were most recently created first.

## Access records through links

In most navigators, you can access a document or a record through the value of its **first** column, regardless of which column that is.

Values displayed in the rows of that column are accessible through **hyperlinks** leading exactly to the document it represents.

> [!NOTE]
> Certain navigators don't support opening links and therefore don't have this feature enabled.

## Navigator menu

Each navigator features its own dedicated **Menu** through which you can perform the following:

* Determine the security type of each navigator record by configuring **access permissions**
* Build and apply **advanced filters**
* Use ERP.net's dedicated **AI Asssistant** (upcoming)
* Take advantage of **side panels** that reveal additional data and attachments for each selected document
* Use **functional panels** to speed up the process of filling out a document
* Expand **detail panels** to see information relevant for each selected record of the navigator (e.g. the Document Lines)
* Create **tiles** to save and later easily access a specific navigator view
* **Customize** the navigator form by enabling, disabling, reordering and renaming its panels and widgets.

## Panel menu

Panels and widgets enabled in a navigator have a separate **Menu button** accessible at their top-right corners.

It features the ability to:

* **Maximize** the panel to take up the entire screen
* **Reload** the panel to reflect the most up-to-date information
* Quickly create a **new** record of one or more respective types
* **Search** the contents of the respective panel
* Take advantage of handy filtering features such as the **Grouping panel** and **Filter row**
* Select **multiple** records from the panel
* Create a **.xlsx file** containing all records of the panel
* Limit the **row counts** of the panel to a specific number
* **Customize** the panel by enabling, disabling, reordering and renaming its columns.

## Column context menu

If you **right-click** on a particular column, you will expand a dropdown menu with the following options:

* **Sort** the column's contents by ascending or descending order
* **Clear** the sorting, restoring the column view to default
* **Group** the records of the column by specific criteria like character count, word count, etc.
* **Summarize** applicable column contents using a Min, Max, Count or Distinct function
* Restore the column's **default width**
* **Hide** the column from view (can be re-enabled through the Panel customization Menu)

### Multi-export

Whenever you select multiple records using the **Multi select** feature, a new **Selected** count will appear under the respective panel's menu.

It allows you to **export** the selected records as .xlsx files

### Grouping 

Depending on the type of the column (e.g. Date, Number, Document Type), you can perform specific grouping functions.

This is achieved through specific **intervals** such as character counts and time periods.

**Example:**

We can filter an entire panel's contents by applying a rule where records will be grouped by whether or not they contain a specific document type as an exact matching value.

### Summary

The context menu of each column allows you to perform several summary functions.

These are used to perform advanced calculations that allow you to see important insights into a panel's records.

## Row context menu

If you **right-click** on a particular row, you will expand a dropdown menu with one or more of the following options:

* **Open** the row's associated record
* Apply an **advanced filter** affecting the entire panel, using this particular row as source (e.g. documment currency)
* Access the **form definition** of the row (e.g. customer, payment type).

## Accessing a record

You can access the document form of an individual navigator record in three ways:

1. By clicking on its **hyperlink** in the first column (applicable for most navigators)
2. By clicking on it, then expanding its **Details** panel and finally clicking on the **Open** button
3. By clicking on its **icon** positioned in the **system column** at the far-left.

> [!NOTE]
> The System column always contains a quick-access button for the respective record and its position cannot be modified

