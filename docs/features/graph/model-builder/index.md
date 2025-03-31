---
title: Model Builder
---

# Model Builder

The Model Builder is an interactive tool to design and build your unique knowledge graph data model. Create entities, relationships, and fields - along with customisation - to establish the foundation for your data.

### Accessing Edit Mode

To begin editing your data model ensure that "Edit Mode" is enabled. This can be toggled from the Data page in the top right corner.

<p align="center">
 <img src="/img/screenshots/docs-graph-edit-mode.png" alt="Brickgraph banner logo" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
</p>

Once Edit Mode is enabled you will see additional options appear in the top menu that allow you to create new Entities or Relationships (the ➕ button).

---

### Views

The Model Builder has two distinct views; Graph and List. Graph view visualises the Entities and Relationships in your model as a connected network and can be interacted with simply by selecting the entity or relationship you'd like to view/navigate to. If you are not in Edit Mode clicking any Entity/Relationship will navigate to the respective Data Editor. If you are in Edit Mode then a dialog will appear with options to edit that object (<a href="#edit-existing">see below for more</a>).

<table>
  <tr>
    <td><img src="/img/screenshots/docs-schema-graph.png" alt="Brickgraph banner logo" width="400" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);"></td>
    <td><img src="/img/screenshots/docs-schema-list.png" alt="Brickgraph banner logo" width="400" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);"></td>
  </tr>
</table>

---

### Entities & Relationships

#### Create new

To create a new entity or relationship in your data model; ensure that Edit Mode is enabled, then click the Plus (➕) icon next to the view options. This will pull up a dialog to create either a new Entity or new Relationship. Fill out the fields for configuring the Entity/Relationship as well as add any fields (see below for adding new fields and field types). Relationships do not have any default fields associated to them, but new Entities do have "label" and "description" as defaults - with "Label" unable to edit (you can, however, change the field type and field details - other than the "id" value).

#### Edit existing

Similarly, editing Entity/Relationship pulls up a similar dialog as "Create". Here you can add or remove fields, as well as edit the configuration for the Entity/Relationship by clicking on the label of the object - when you hover over the label title a pencil icon (✏️) will appear.

#### Deleting

Deleting an Entity/Relationship requires confirmation as Brickgraph will also delete all of it's associated data. Please be careful about deleting Entities or Relationships.

### Fields

#### Adding new fields

To add a new field to an Entity/Relationship click the "Add Field" button at the bottom of the dialog. This will pull up the Add Field dialog where you can configure the field. Depending on the field type selected there may be additional options to configure - such as default value, options (for single and multiple select), and decimal places (for number fields).

<p align="center">
 <img src="/img/screenshots/docs-schema-add-field.png" alt="Brickgraph banner logo" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
</p>

#### Field types and options

###### Text

###### Text Area

###### Single Select

###### Multiple Select

###### Number

###### Percentage

###### Currency

###### True / False (Boolean)

###### Date

###### Email

###### Link

###### Rating

###### Address

###### Relationship (Inward and Outward)
