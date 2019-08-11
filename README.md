# YAGF: Yet Another Grid Framework
###### Created by Nico & Oscar, «The Dream Team» :smirk:

This framework is a grid based layout framework that has two modes:
## Bootstrap mode:
In this mode, the selectors work in a similar manner to Bootstrap (rows divided in 12 columns), but with the difference that you can select the starting and ending column, i.e.: **col-md-2-4** will make the cell extend from column 2 to 4. This has the advantage against Bootstrap that you can leave empty columns without using another class selector. You can even move the cells around (change the order on screen) for different resolutions.

## Grid mode:
In this mode, the container is divided in a grid 6 columns width by 3 rows height. You can select a range in this grid using an Excel-like syntax, i.e.: **range-md-a1-b2** will select the top left four cells in medium resolution and **range-lg-b5-c6** will select the bottom right four cells in large resolutions.
To compensate for the three row limit you can either nest grids into grids, or you can change the corresponding values in the defs.sass segment and recompile the code.

[Demo Live preview](https://oscarnava.github.io/custom-grid-framework/)
