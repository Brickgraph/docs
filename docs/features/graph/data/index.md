---
title: Data Editor
---

# Data Editor

The Brickgraph Data Editor is an Excel-like table to create, update, or delete data within your knowledge graph. You can edit cells according - with columns representing the Fields that are configured in the Model Builder.

<p align="center">
 <img src="/img/screenshots/docs-data-editor.png" alt="Brickgraph banner logo" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
</p>

---

### Toolbar

The Data Editor has a collection of features and options in the top toolbar

#### Filter

You can filter which data is visible using the unique filter menu, which has two filtering options. The menu is unique because it not only allows filtering on the data in the table but also to filter by connections ("related") to other Entities in your graph.

Conceptually, the way that the "Related" filter works is by finding the entity (or entities) that are indicated and finding a path from that entity to ANY entities or relationships that can be found somewhere along that path - based on the direction indicated. Imagine drawing a line from the entity that you add to the "Related" filter and following where that line goes (in the direction specified) in the graph. This type of filter can be very useful if you are trying to find entities or relationships based on how they might be connected elsewhere in your knowledge graph.

The second type of filter is more straightforward - it is based on the data that is associated with the entity/relationship. For example, if you have are viewing "Projects" entities and want to see those with a "Status" of "Owned" you can use this filter to select the column you'd like to filter on along with the operator - which will change depending on the field type - and the value to look for.

#### Create

The Create button will pull up a form to add a new entity/relationship.

#### Delete

The Delete button will delete any rows that are selected (via the row checkbox).

#### Download

The Download button will download the current data as a CSV file.

---

### Rows

Rows in the Data Editor are very much like what you would expect to see in Excel, Google Sheets, etc. in that they are made up of editable cells - with the main difference being that cells will change behaviour based on their type. So a cell in a single-select field type will have a dropdown of options, or an "address" type field will pull up the Address Search dialog.

#### Expand row

When hovering over the row number it will change into an "expand" icon. Pressing this will open the row in form view - which allows you to also edit the data or delete the object. In the top right corner of the form view there are also links to the entity pages (Details, Subgraph, and Map)

<p align="center">
 <img src="/img/screenshots/docs-data-row-focus.png" alt="Brickgraph banner logo" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
</p>

#### Additional options

Right-clicking on the checkbox at the furthest left of the row will pull up the additional options menu. You can directly open the Entity focus pages (if viewing Entity objects), share the row data via email, or delete the entity/relationship.

### Columns

Columns in the Data Editor map against the data model fields. Clicking on the column header will pull up the column menu - from here you can view the field description (if any) or sort the rows. You can also identify the data type of the column/field by looking at the icon next to the field label (hovering over the icon will also indicate the type).

#### Addresses

A unique feature in Brickgraph is the Address field type. In the Data Editor clicking on an Address cell will pull up the Address Search dialog. You can either type the address into the top search bar or manually complete the address data. If you use the search bar Brickgraph will attempt to forward geocoding the address, parse the results, and fill out the form. You can specific the country that you are searching in to improve accuracy or toggle to "Globe" for worldwide search.

#### Relationships

One of the other unique features of Brickgraph is the Inward/Outward Relationship field type. This field type allows you to reference another entity in your graph along with data for that relationship. For example, a "Knows" relationship might have a field of "Since" that gives the user the ability to not only connect two "Person" entities to one another but also to indicate the year that those people met. In the Data Editor the relationship field will show a button to open the relationship in a dialog. From this dialog you will see the other entity in the relationship (i.e., the one person in the "Knows" relationship) as well as details about the relationship itself. You can toggle between the entity and the relationship details using the tabs at the top of the dialog.
