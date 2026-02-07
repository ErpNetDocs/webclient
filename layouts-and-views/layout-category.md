# What is a Layout Category

In the @@webclient, it is possible to display different user interface layouts for objects of the same entity, depending on the type of data they represent.
This is achieved through the use of a Layout category attribute.

A Layout category allows records belonging to the same data entity to be classified into semantic types, without introducing separate entities or changing the underlying data model. Based on this classification, the Web Client can automatically select and render different views (layouts) for different categories of the same entity.

This mechanism enables flexible UI customization while preserving a clean and unified data structure. It is especially useful when objects share common identity and behavior, but differ significantly in the information that is relevant to users.

## Concepts
What is a Layout Category?

A Layout category is a designated attribute of an entity whose value determines which UI layout is used when displaying an object in the Web Client.

**All objects:**

- Belong to the same entity
- Share the same schema, persistence, and API
- Remain logically and functionally comparable

However, each object is additionally classified by its layout category, which expresses what kind of object it is from a presentation perspective.

**Example:**

Entity: Customer

Layout category attribute: Customer Type

Possible values: Small / Big / Enterprise

All records are Customers, but each type may require a different screen layout, field set, or visual emphasis.

## Purpose of Layout Categories

The primary purpose of layout categories is to enable:

- Different UI layouts for the same entity
- Context-appropriate presentation of data
- Reduced UI complexity, by showing only relevant fields per category
- Avoidance of entity fragmentation (no need to create separate entities for each type)

Without layout categories, UI customization would typically require:

Large conditional layouts with hidden fields, or Artificial splitting of a single logical entity into multiple entities.

Layout categories provide a cleaner, declarative alternative.

## How Layout Categories Affect Views?

When an object is opened in the Web Client:

- The system identifies the entity of the object.
- The value of the layout category attribute is evaluated.
- The Web Client selects the corresponding view (layout) for that category.
- The object is rendered using the selected layout.

This selection happens automatically and transparently to the user.

## Scope and Intentional Naming

The term **Layout category** is intentionally focused on its primary role: driving layout selection in the Web Client. Although such categorization could theoretically be reused for other purposes in the future, its current and documented intent is UI-related. Using a focused name improves clarity, reduces ambiguity, and helps users immediately understand why the attribute exists and how it should be used.

If additional use cases emerge later, they can be evaluated independently without changing the conceptual clarity of the current mechanism.

[See How to separate view based on Layout Category](https://docs.erp.net/webclient/introduction/how-to/ui-customization/separate-views.html)
