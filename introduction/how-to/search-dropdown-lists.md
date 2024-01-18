# How to search in drop down lists

The search in the the drow down lists that show records from another entity works with specific values. Generally, you can search by the fields that are included in the entity's Default Search Members or the entity's Display Text.

### Default Search Members

For each entity are specified particular _Default Search Members_ - a collection of _Fields_ which make **searching** possible. 

Which are the default search members of a specific entity, can be seen "Default Visualization" section of the entity's documentation. Take a look at [products](https://docs.erp.net/model/entities/General.Products.Products.html). 

### Display Format

Searching can also be accomplished with the help of fields that comprise the _Display Text_. However, these fields are prioritized after the _Default Search Members_. Searching is initiated only if there isn't any match with the fields before them. 

> **_NOTE:_**  Searching in dropdown lists and domain API returns only results which are based on the first field for which there are matches. Subsequent searches are not undertaken. If a search operation finds an exact match, the value is filled automatically in the corresponding field. 

Each entity has a _Default Display Text Format_. The _Default Display Text Format_ for each entity is specified in the entity's documentation. Take a look at [products](https://docs.erp.net/model/entities/General.Products.Products.html). 

A different _Display Text Format_ can be explicitly set for the entity in the _Display Text Format_ field of the Entities navigator in the particular database. If no _Display Text Format_ is specified, then the system apllies the _Default Display Text Format_.
