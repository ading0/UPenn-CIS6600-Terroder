## about
Written by Andrew Ding and Xinran Tao for UPenn's CIS6600 in spring 2024.

## Introduction
_Terroder_ is a terrain creation plugin that creates realistic terrain from a low-resolution "uplift" texture.

## Usage
- Install Maya, or have it installed.
- Install the following dependency packages:
    - packages: 
        - numpy
        - pillow
        - opencv-python
    - These packages must be installed for the mayapy executable, e.g. navigate to the folder with mayapy and execute: ```mayapy -m pip install <flags> <package>```
        - default (no specified) flags should work for all packages
    - For more detailed instructions on installing Python packages for Maya plugins, see [this page on Autodesk's website](https://help.autodesk.com/view/MAYAUL/2024/ENU/?guid=GUID-72A245EC-CDB4-46AB-BEE0-4BBBF9791627).
- Copy ```terroder_node_plugin.py``` to an appropriate folder, and use Maya's plugin manager to load it as a python plugin. The singular file is the entire plugin.
- The plugin creates a new top-level menu, as seen below:
![](readme_images/top_level_menu.png)
- One of the items in the _Terroder_ menu provides a help dialog:
![](readme_images/help_menu.png)
- Use the _Create Terroder Mesh_ option to get started.

## Example Output
![](readme_images/output_table.png)
![](readme_images/output_highlight.png)
