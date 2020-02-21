# Caress_Bela
## Description
Caress piezo-instrument running on Bela via Pd

![caress_bela - play](https://github.com/irllabs/caress_bela/blob/master/documentation/caress_play.png "caress_bela - play")

## Installation
### caress
Bela works by reading a specific folder for project files and external objects.

After logging into your Bela - either through the [Web IDE](http://bela.local) or SSH - Copy both the __caress__ and __pd-externals__ folders into:
```
/root/Bela/projects
```
#### run on boot
After uploading the files, use the Bela IDE > Settings to set _caress_ as the project to [run on boot](https://github.com/BelaPlatform/Bela/wiki/Running-Bela-projects-automatically-on-boot) 

### tests_and_tools
The same process can be applied to try out any of the other projects residing in the _tests_and_tools_ folder (which have been placed there as they aren't required for the main caress patch to run)

## Usage
The caress_bela should run directly after startup (On/Off switch in the middle of device) if properly connected to all hardware: 
- MO controller board 
 
    - 2 x strips
    - 2 x joysticks
    
- 2 x piezo-preamps
- 5V litho battery pack

### Controls

![caress_bela - controls](https://github.com/irllabs/caress_bela/blob/master/documentation/caress_controls.png "caress_bela - controls")

## Notes

ml.lib is installed in pd-extentions folder if you wish you use any objects in future Bela projects.
