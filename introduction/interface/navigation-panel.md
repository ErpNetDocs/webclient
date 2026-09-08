# Navigation panel

## Overview

The **Navigation panel** is the main navigation area within an application in the @@webclient. It provides access to the application's components and functions and helps users quickly move between the areas they need for their work.

The content of the Navigation panel depends on the currently opened application. It can include navigation items for accessing records and other application components, as well as **Favorites** for frequently used items.

The panel can also be organized according to the user's preferences, making commonly used items easier to access.

## Navigation panel elements

The Navigation panel changes its content according to the current navigation level. It first provides access to the available **clusters and modules** and, after a module is selected, displays the navigation items available for its repository.


### Clusters and modules

The initial navigation structure organizes the functionality of the @@webclient into **clusters** and **modules**.
<img width="384" height="925" alt="image" src="https://github.com/user-attachments/assets/885381cc-1ee1-4a68-b8e7-5e3e618e611d" />


- **Clusters** group modules into major functional areas, such as **CRM**, **Finance**, **Logistics**, and **Production**.
- **Modules** provide access to a particular functional area within a cluster. For example, the **CRM** cluster includes modules such as **Presales**, **Sales**, **Marketing**, and **Pricing**.

Selecting a module opens the navigation structure of its corresponding repository.

### Repository navigation

After a module is selected, the Navigation panel provides access to the resources available in its repository.

The panel can contain the following elements:

- **Overview** – opens the homepage of the selected module.
- **Notifications** – provides access to notifications related to the current module.
- **Menu** – contains the entities and other navigation items available in the repository. Some items can be expanded to reveal additional related items.

Each item in the **Menu** can include a short description indicating its purpose.

### Current role

The **Menu** displays the current role of the logged-in user. The role determines the repository navigation available to the user and is shown directly below the **Menu** label.

### Entity actions

Repository entities provide additional actions directly from the Navigation panel. When the pointer is placed over an entity, the available action icons appear on its right side.

Depending on the entity, these can include:

- **Layouts** (eye icon) – displays the available named layouts for the entity's navigator. Selecting a layout opens the navigator with that layout.
- **Create** (plus icon) – displays the available types of records that can be created for the entity. Selecting a type starts the creation of a new record directly from the Navigation panel.

This provides quick access to frequently used navigator layouts and record creation without first opening the corresponding navigator.

### Expandable items

A **chevron** indicates that a navigation item contains additional items.

- A right-pointing chevron indicates that the item is collapsed.
- A downward-pointing chevron indicates that the item is expanded.

For repository entities, expanding the item can provide direct access to recently opened and favorite records.

### Recent and favorite records

When an entity is expanded, the Navigation panel can display up to **five recently opened records**, as well as records marked as **Favorites**.

A label below each record indicates why it appears in the list:

- **Recent** – the record is one of the recently opened records for the entity.
- **Favorite** – а record that is a Favorite has been recently opened.

Selecting a record opens it directly from the Navigation panel.

### Panel controls

The top of the Navigation panel provides controls for working with the panel itself:

- **Search** – searches the items available in the Navigation panel.
- **Settings** – provides options for organizing the Navigation panel.
- **Pin** – keeps the Navigation panel visible while working in the @@webclient.
