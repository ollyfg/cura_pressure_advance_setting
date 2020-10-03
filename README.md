# Cura Pressure Advance Setting Plugin

This plugin adds a setting named "Pressure Advance" to the Material category in the Custom print setup of Cura. The plugin inserts a "SET_PRESSURE_ADVANCE" command in the Gcode to set the Pressure Advance Factor for klipper-based printers.

Though it has not been tested, this plugin should work with the "Material Settings" plugin, allowing you to set different pressure advance values for different materials.

## Installing

The recommended way to install this plugin is via the Cura Marketplace. Just search for "Pressure Advance".

### Manual Installation

1. Find your Cura Plugin directory. Open Cura and in the top menu click `Help > Show Configuratiion Folder`, in the folder that opens, look for a directory called `plugins`.

2. Clone or download this repository. Place it in the plugin directory. If you download this repository you will need to unzip it first.

## Packaging

From the directory above this repository:

```
zip -rq plugin.zip cura_pressure_advance_setting
```
