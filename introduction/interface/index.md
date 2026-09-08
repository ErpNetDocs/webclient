# Interface of @@webclient

The ERP.net Web Client interface includes a range of intuitive symbols, elements, buttons that provide quick access to core functionality. 

## Interface Symbols

- **Kebab menu (⋮)**: Opens a dropdown menu with contextual options. Typically located on the right side of a panel.
- ⚙️ **Gearwheel**: Provides access to system or contextual settings.
- **Square/rectangle with a pencil**: Represents the option to view, enter, or edit an entry, such as a document, product, or user profile.
- **Plus sign (+)**: Used to create a new entry.
- **Right angle bracket (>)**: Expands a collapsible menu or section.
- 🔔 **Bell**: Notification icon. An orange circle with a number indicates new alerts (e.g., someone mentioned you or updated a tracked document).
- **House**: Navigates to the home page of the module ("Overview").
- 📌 **Pin**: Used to fix or unfix panels. 
  - A diagonal pin means you can pin the item.  
  - A vertical pin means it's already pinned.
- ⭐ **Star**: Marks the item as important.
- **On/Off toggle**: (toggle switch) Activates or deactivates specific functions or views.
- **Funnel**: Opens a search or filtering function, usually within navigators.
- **Chevron (ˇ)**: Opens a dropdown menu.
- **Sqare**: maximizes the panel
- 🔍 **Magnifying lens**: a place to input search text

## Functional Elements

These are the core elements, the structure of @@webclient that present data and are actually the tools to navigate and execute tasks.

- App bar

A vertical sidebar to the left of the platform, that appears after clicking the Start menu (in case it was not pinned). It provides access to all ERP.net applications and their subsystems.

- Navigation panel 

Displays the components of the currently open application, including records, settings, and favorites. This is the shortcut to reach the desired entities and operate within the module.

- Side panel

A [side panel](https://docs.erp.net/webclient/side-panels/index.html) is a context-sensitive panel on the right side of the screen. Available options depend on the active form and may include additional, context-specific features such as document routes, discussions, advanced filters, functional panels, and access permissions.

> [!Note]  
> Side-panel tools are context-based and always relevant to the currently opened record.

- Navigators

[Navigators](https://docs.erp.net/webclient/navigators/index.html) organize and display data in a structured, interactive table format.

- Records are typically sorted by **Document Date** in descending order (newest first)
- Columns can be sorted using up/down arrows
- Each column includes a **funnel icon** for filtering and searching
- Records are opened by clicking the value in the first column, which acts as a direct link to the record form

- Home page

Represents the module by several main panels, that define its structure and components (entities). The main panels contain Definitions, Documents and operations, Setup, Reports and Ledgers. Each one further consists of and reveals corresponding categories, namespaces and report-views.

- Single-record form 

Every record exists within its own form. This form may consist of several panels.
The main panel bears the name of the entity itself, and is usually called "the main panel". It contains the essential fields that define the record - the definition.
Other panels supply related or detailed information connected with the current record and can be displayed and organized per the needs.

- Panel 

Panels build both application home pages and individual record views. Types of panels include Main panels, Detail panels, Related data panels, Widget panels.
