# Introduction to @@webclient

The @@webclient is the web-based user interface of the ERP.net business-management platform. It is one of the primary ways to access and interact with all the modules inside the ERP.net system—such as CRM, financials, inventory, production, and more.

This guide is designed to help you effectively use the **ERP.net Web Client** to manage and streamline your organization’s daily operations. It introduces the core concepts, interface, and tools that enable you to take full advantage of the ERP.net cloud platform.

ERP.net is built around a **single, centralized data source** combined with **automation of key business processes**. This approach is essential for modern organizations: working with one reliable source of information reduces errors, eliminates data duplication, and saves valuable time and resources. By automating routine and repetitive tasks, teams can focus on higher-value activities—boosting productivity and supporting better, faster business decisions.

---

# @@webclient Key Benefits and Fetaures

- **Centralized data** - work with a single source of truth from anywhere. Access real-time information, collaborate remotely, and make faster, data-driven decisions;
- **Lower upfront costs** - no need for expensive hardware or on-premises infrastructure. ERP.net follows a subscription-based (SaaS) model with predictable monthly or annual costs;
- **Automatic updates and maintenance**  - software updates, patches, and security improvements are handled by ERP.BG. You always work with the latest version, including new features and compliance updates;
- **Scalability** - easily scale as your business grows. Add users, modules, or storage without major system changes or downtime;
- **Enhanced security** - strong investments in data security, encryption, compliance, regular backups, and disaster-recovery mechanisms ensure your data is protected;
- **Seamless collaboration**  - teams across departments and locations can collaborate in real time. ERP.net supports a social-ERP style of work, similar to modern collaboration platforms;
- **Business agility**  -   Respond quickly to market changes, customer demands, and internal organizational shifts;
- **Complete access from a browser** - no heavy thick-client required, so users can log in from various devices;
- **Personalised dashboards and “My Apps” widgets** -  each user sees what matters most for their role;
- **Social-ERP style features** - following objects, discussions, mentions, notifications—bringing business processes closer to modern collaboration;
- **Flexible UI panels, web views** - embedding external sites or services within the client, and layout customisation by role;
- **Full support for data entry, editing, settings, and administration**  — not just “view only”.
---

In this site you will be aquianted with the concepts, terms and features:

- basic [navigator features](navigator-features.md)
- [social concepts](./social/index.md)
- the [My Apps](./my-apps/index.md) module
- [How-to guides](https://docs.erp.net/webclient/introduction/how-to/index.html) for operations and features specific to the Web Client


## 1. Common Terms

Within the ERP.net Web Client, several key terms are used throughout the interface:

- Form - the topmost core component.  A single record (object) with all its parameters, displayed on the screen through a user-friendly interface. Each page has a single  form, containing multiple panels.
- Panel - a core component. A distinct section or container that groups related elements, controls, or content.Displays a specific type of information. Each panel is hosted in a form.
- Navigator - a table-based tool for viewing and working with large volumes of data in a structured way. Navigators allow searching, sorting (by one or multiple criteria),  filtering, and drilling down into details. Some navigators include auxiliary panels that provide additional context related to the main navigator
- Ribbon - a horizontal bar at the top of the currently open form. It displays the current location in the system and command buttons and a menu with options
- Header ribbon  - the topmost header of the ERP.net window. It contains global elements such as the search engine, user profile access, notifications, and shortcuts.
- Application - a purpose-driven, logically distinct set of functions designed to support specific business tasks.
- [My apps](./my-apps/index.md#overview) – a group of specific standalone applications, integral part of the @@webclient;
- [Widget](./my-apps/index.md#widgets) - a special panel, dynamic functional element used for contextual selection or visualization of records. It could be placed in every @@webclient form;
- [Tile](./my-apps/tiles.md) - a shortcut to saved different sections of your data that can be accessed and switched between in a single tap;
- [Favorite](./my-apps/favorites/index.md) - a shortcut to items of special interest at one-touch reach.
  

## 2. Interface

The ERP.net Web Client interface includes a range of intuitive symbols, elements, buttons that provide quick access to core functionality. 

### 2.1 Interface Symbols


- **Kebab menu (⋮)**: Opens a dropdown menu with contextual options. Typically located on the right side of a panel.
- ⚙️ **Gearwheel**: Provides access to system or contextual settings.
- **Square/rectangle with a pencil**: Represents the option to view, enter, or edit an entry, such as a document, product, or user profile.
- **Plus sign (+)**: Used to create a new entry.
- **Right angle bracket (>)**: Expands a collapsible menu or section.
- 🔔 **Bell**: Notification icon. An orange circle with a number indicates new alerts (e.g., someone mentioned you or updated a tracked document).
- **House**: Navigates to the home page of the module ("Overview").
- 📌 **Pin**: Used to fix or unfix panels. 
  - A diagonal pin means you can pin the panel.  
  - A vertical pin means it's already pinned.
- ⭐ **Star**: Marks the item as important.
- **On/Off toggle**: (toggle switch) Activates or deactivates specific functions or views.
- **Funnel**: Opens a search or filtering function, usually within navigators.
- **Chevron (ˇ)**: Opens a dropdown menu.
- **Sqare**: maximizes the panel
- 🔍 **Magnifying lens**: a place to input search text

---

### 2.2 Functional Elements

These are the core elements, the structure of @@webclient that present data and are actually the tools to navigate and execute tasks.

**App bar** 

A vertical sidebar that appears after clicking the Start menu. It provides access to all ERP.net applications and their subsystems.

**Navigation panel** 

Displays the components of the currently open application, including records, settings, and favorites. This is the shortcut to reach the desired entities and operate within the module.

**Side panel**  

A context-sensitive panel on the right side of the screen. Available options depend on the active form and may include additional, context-specific features such as document routes, discussions, advanced filters, functional panels, and access permissions.

> [!Note]  
> Side-panel tools are context-based and always relevant to the currently opened record.

[**Navigators**](https://docs.erp.net/webclient/navigators/index.html))

Navigators organize and display data in a structured, interactive table format.

- Records are typically sorted by **Document Date** in descending order (newest first)
- Columns can be sorted using up/down arrows
- Each column includes a **funnel icon** for filtering and searching
- Records are opened by clicking the value in the first column, which acts as a direct link to the record form

**Single-Record Forms and Panels**

- **Single record form**  
  Every record exists within its own form. This form may consist of several panels.
  The main panel bears the name of the entity itself, and is usually called "the master panel". It contains the essential fields that define the record - the definition.
  Other panels supply related or detailed information connected with the current record and can be displayed and organized per the needs.

- **Home page**
  <br>Represents the module by several main panels, that define its structure and components (entities). The main panels contain Definitions, Documents and operations, Setup, Reports and Ledgers. Each one further consists of and reveals corresponding categories, namespaces and report-views.

- **Panels**  
  Panels structure both application home pages and individual record views. Types include:
  - Main panels
  - Detail panels
  - Related data panels
  - Widget panels

---

## My Apps

**My Apps** is the personal home area for each user. It consists of independent, interactive applications that can also be used as standalone tools.

Included applications:

- **Calendar** – manage meetings, calls, and visits (weekly and monthly views)
- **To Do** – personal task list with statuses, due dates, reminders, and notes
- **Groups** – collaboration spaces with chat, files, calendars, and tasks
- **Timeline** – visual overview of recent activities
- **Tiles** – shortcuts to predefined or complex searches
- **Favorites** – quick access to important people, documents, and items
- **Dashboard** – at-a-glance overview of key information
- **AI Assistant** - a personal AI assistant conversation module
- **Folders** - a list and access to available Folders for file management in the instance
- **Documents** - a navigator of all documents, assigned to the logged user
- **Notifications** - a list of recent notifications
---

## Personal Profile

Each user has a personal profile accessible from the top-right corner of the interface. It allows management of:

- Personal and contact information
- Company, position, and office location
- Language, theme, background, and layout preferences
- Login details, password, and registered devices

The profile is edited through a multi-tab form that ensures clear organization and easy maintenance of personal settings.
