# Notes - Umap



## Create direct/raw-links in github to use in umap

```
https://raw.githubusercontent.com/<your_Github_username>/<your_repository_name>/<branch_name>/../<file_name>.<extension_name>
```

Example:
```
https://raw.githubusercontent.com/kvanmol/TestRepo/main/accommodation_camping.p.AC39AC.32.png
```

## Using properties in your URL
It is possible to refer to properties in your URL by using curly brackets:
```
https://raw.githubusercontent.com/<your_Github_username>/<your_repository_name>/<branch_name>/../{property}.<extension_name>
```
### managing self-defined properties
Properties are managed at layer level. Properties of objects in a layer can be modified by means of a **table editor** <img src="https://wiki.openstreetmap.org/w/images/0/0a/UMap_layer_line_edit-properties.jpg?20190514132115" height="20">. The table editor allows also addition of new, **self-defined properties**.

Example of table editor:

<img src="https://wiki.openstreetmap.org/w/images/thumb/0/0c/UMap_table_example_2.jpg/800px-UMap_table_example_2.jpg?20190514172259" height="150">

New properties will also be shown in the panel to modify an object (feature like point or linestring).

<img src="https://wiki.openstreetmap.org/w/images/d/db/UMap_panel_marker_properties_custom.jpg?20190515115756" width="200">



## Sources
- https://help.openstreetmap.org/questions/60128/questions-arising-from-my-attempts-to-use-umap
- https://github.com/orgs/community/discussions/44370
- https://wiki.openstreetmap.org/wiki/UMap/Guide