---
title: Map Layers
---

# Map Layers

Brickgraph enables you to integrate different data onto the map for visualization and analysis. These include your own data from the Brickgraph Knowledge Graph alongside external datasets for demographics, boundaries, and more. These can be accessed from the menu at the top left corner of the map.

Currently there are three types of layers;

### Graph Data

You can add data from your knowledge graph by selecting "Graph Data" from the "Add Layer" option. When clicked the Graph Data dialog will appear, which allows you to select the data, filters, and styling options. The only entity options for Graph Data will be those which have an **address** field in the data model.

Filtering the data works the same as in the [Data Editor](/features/graph/data/#filter).

<p align="center">
 <img src="/img/screenshots/docs-map-data-layer.png" alt="Brickgraph Map" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

When the points are displayed on the map you can click on any point to open the Analyse Menu. This menu has options to;

1. Open a data editor dialog for the selected entity
2. Zoom to the location
3. Start a pre-populated Radius layer
4. Start a pre-populated Datasets layer

<p align="center">
 <img src="/img/screenshots/docs-map-point-menu.png" alt="Data Point Menu" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

---

### Radius

Radius layers create a travel-time area around the given address / point. You can either search for an address in the search bar or use the pre-populated location - then specify which data category and point you want to view and highlight, respectively. Then edit the travel mode and time and press **Search** to begin processing.

<p align="center">
 <img src="/img/screenshots/docs-map-radius-dialog.png" alt="Add Radius Layer dialog" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

Once the layer is processed and visible on the map you can select the icon to open a menu with options to view more details about the data. You can also use the layer manager to customize how the Radius layer looks by hiding/showing the marker as well as toggling the heatmap on/off.

<p align="center">
 <img src="/img/screenshots/docs-map-radius-result.png" alt="Add Radius Layer dialog" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

Please keep in mind that Radius data is **currently only available for the United Kingdom**. All other geographies will return empty data but will visualize the travel time area.

---

### Datasets

Dataset layers create boundary areas near the selected location. It is as simple as selected the desired data and the number of features to visualise (the max amount varies).

<p align="center">
 <img src="/img/screenshots/docs-map-datasets-layer.png" alt="Brickgraph Map" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

We are continuously adding new datasets, feel free to request new datasets by contacting [support@brickgraph.io](mailto:support@brickgraph.io)

<p align="center">
 <img src="/img/screenshots/docs-map-dataset-result.png" alt="Dataset Result Layer" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>

### Layer Manager

The menu in the top left corner of the map will list all of the currently applied layers. Depending on the layer type you can apply styling options.

- Radius layers can hide/show marker and/or heatmap data
- Dataset layers can; hide/show the marker; change color settings for the areas; and/or toggle visibility of individual features of the dataset

<p align="center">
 <img src="/img/screenshots/docs-map-layer-manager.png" alt="Map Layer Manager" width="800" style="border-radius: 8px; box-shadow: 0 4px 6px #0f2b53;">
</p>
