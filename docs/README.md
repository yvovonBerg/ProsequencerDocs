![](/img/cover.jpg)

# ProSequencer for UE4

> Welcome to the Prosequencer for Unreal Engine documentation!  

# What is ProSequencer?

Prosequencer UE4 is a plugin for Unreal Engine 4 that allows you to convert (split) camera cuts to shots.

- Split shots (convert camera cuts to shot sections)
- Rename shots (Rename the section, the folder name and the level sequence asset it self.)
- Split individual shots (And create level sequence assets)
- Batch rename shots


# How to get help

> Stuck or do you have an idea for a great feature? Let me know! 
[CGToolsmith Service Center](https://cgtoolsmith.atlassian.net/servicedesk/customer/portals)


# Create shots

![](/img/ProSequencerTool_UI_2.jpg)

1. Create a new sequence with camera cuts
2. Open the ProSequencer menu 
3. Enter the correct settings:

- Shot folder base path: This is the root directory the split shots will be saved in: (base_path/shot_folder).
On default this path will be the current directory of the current level sequence. (Tip: when pressing 'Reload path' the 'Shot folder base path' will be changed to the current opened sequence)
- Shot folder name: This is the name of the directory where the split shots will be saved (base_path/shot_folder). Note: this option will only properly work when creating shots (not batch renaming).
- Shot prefix: The prefix of the shot name.
- Shot digits: The amount of digits in the shot name
- Shot increments: The increments between the digits in the shot name
- Rename shots: Enable / Disable the renaming of shots based on above settings
- Cleanup other cameras: Cleanup other cameras (Other than the connected camera to the camera cut) that are in each individual shots. 
- Cleanup master assets: Cleanup the master sequence with all assets.

4. Press create shots


# Split shot at current time

1. Open a sequence with shots (not camera cuts)

2. Move the times slider to the correct time

3. Press 'Split shot at current time'

4. The shot will be split (A new asset will be created as well). Note: Keep in mind that this feature will use the current settings from the tool.


# Batch rename all shots

1. Open a sequence with shots (Not camera cuts)

2. Press 'batch rename all shots'

3. Note: Keep in mind that this feature will use the current settings from the tool. Not working quite well ? Try pressing batch rename all shots again.


![](/img/prosequencer_menu.jpg)
![](/img/prosequencer_UI_1.jpg)
![](/img/ProSequencerTool_UI_3.jpg)

