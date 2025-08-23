# Road Tools

<table style="width:100%;">
<tr>
<td style="width:50%;"><img src="docs/img/highwayrender3.png" alt="Demo" width="100%"></td>
<td style="width:50%;">
A blender addon that generates customisable roads from edges and intersections from points.<br>

<ul>
  <li>Generate straight and curved roads</li>
  <li>Add intersections automatically</li>
  <li>Works with Blender 4.x+</li>
</ul>
</td>
</tr>
</table>

## Quick Install
1. Download the `.zip` from [Blender Market](https://blendermarket.com/your-addon).
2. In Blender: `Edit > Preferences > Add-ons > Install...`
3. Select the `.zip` and enable **Road Tools**.

## Usage

### Add Road Object
To get started creating your roads, in the 3d-viewport open the `N` Panel, click the `Road Tools` Subpanel and press the `Add new road object` button. This appends the default road object along with it's assets. 

### Presets
this panel let's you load and save road presets. <br>
The addon comes with a few premade presets. In edit mode, select the edges you want to apply the preset to and pick one from the dropdown menu. If the preset doesn't load automatically, press the `load` button. 

#### Preset customisation
Whilst in edit mode, a subpanel `customise road` is available. Opening it reveals ways in which you can customise the selected road edges.

> **Note:**  Customising the road edges does not change the whole preset itself, it only updates attributes for the selection

To apply the customisations, press the `Apply Customisations` button. 
To make the customisation more responsive, you can use the `live toggle update` button (a white circle to the left of the `Apply Customisations` button).  
The `live toggle update` lets you apply the changes live to the selected edges without the need to press the `Apply Customisations` button, however it leaves all the customisation menus visible, regardles if they will work for the selected road type. 

#### Save custom presets
After customising your road, you can save it as a custom preset. **Make sure the `Live toggle update` button is off**, select the customised edge and press the `Save` button.
You can upload a custom image for your road pressing the image button located to the right of the `Save` button. (square image icon).

#### Delete presets
You can delete any preset (other than "!Default") by selecting it from the dropdown menu and pressing the `X` located to the right of the dropdown menu. 

### File paths
Road presets and their image thumbnails have their own files in these locations:

**Windows**
- Preset variables: `C:\Users\<YourName>\AppData\Roaming\Blender Foundation\Blender\<version>\scripts\addons\road_tools\road_presets.json`
- Preset images: `C:\Users\<YourName>\AppData\Roaming\Blender Foundation\Blender\<version>\scripts\addons\road_tools\images`

**MacOS**
- Preset variables: `/Users/<YourName>/Library/Application Support/Blender/<version>/scripts/addons/road_tools/road_presets.json`
- Preset images: `/Users/<YourName>/Library/Application Support/Blender/<version>/scripts/addons/road_tools/images`

**Linux**
- Preset variables: `/home/<YourName>/.config/blender/<version>/scripts/addons/road_tools/road_presets.json`
- Preset images: `/home/<YourName>/.config/blender/<version>/scripts/addons/road_tools/images`






