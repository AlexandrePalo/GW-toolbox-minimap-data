# DoA minimap Toolbox data

This is an attempt to centralise all DoA minimap data you may need during your runs:

- [All foes and allies model ids](doa-model-ids.csv),
- [All useful custom lines, markers and polygons](doa-useful-markers.csv).

Furthermore, the [main Excel spreadsheet](<GW Toolbox DoA minimap data.xlsm>) provides convenient macros to select which data you want to export to your \*.ini files as well as an easy way to set colors and other parameters.

## Requirement

- Excel (any version)
- Enable active content from the file

## Credits
- DoA teach discord for miscellaneous markers
- Scuz Mes for macros and centralisation

### Remark :

Before copy pasting anything in your \*.ini files, be sure to keep any useful information you may already have there.

## How to use

### Custom Agents

1. For each foe/ally you want to export with a specific agent design, put an "x" in the "Included" column.
2. Change whatever you want in columns "Color", "Text color", "Shape" and "Size".  
   An empty cell will set the default Guild Wars value (red colors, tear shape and size 1).  
   For colors, just change the background of the cell so you can use any Excel base color or a fancy hex color code via the color picker (see "color example" sheet for more).
3. If you already have a lot of other custom agents in your Toolbox file, you can use a different first id and to not interfere with them.
4. Click the button "Generate" and copy paste into your AgentColors.ini in your Toolbox root folder, usually located in `_X_ :\Users\ _name_ \Documents\GWToolboxpp\ _computer name_`.
5. Feel free to change anything, especially professions, names and macro to display something different. By default, exported names will be : `DoA - [profession code if any] [name]`.

### Custom Markers

1. For each marker/line you want to export, put an "x" in the "Included" column.
2. Change the color the marker is going to be displayed on the minimap but setting the background color of the cell in "Color" column.
3. The default Guild Wars color is white, dimmed for polygons.
4. Click the button "Generate" and copy paste into your Markers.ini in your Toolbox root folder, usually located in `_X_ :\Users\ _name_ \Documents\GWToolboxpp\ _computer name_`.
5. Feel free to change anything, especially names and macro to display something different. By default, exported names will be : `DoA - [area] [name]`.
