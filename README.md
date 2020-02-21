# Caress_Bela
## Description
*Caress* is an electro-acoustic instrument built that combines the [Bela](http://bela.io) platform, with [Pure Data](http://puredata.info) and a custom made physical instrument.  *Caress* consists of contact microphones with [custom preamps](https://github.com/irllabs/eagle/tree/master/piezo-preamp-tickler), light sensors, joysticks, buttons and knobs.  While PureData offers infinite possibilities with regards to interactive sound, *Caress* focues on a tactile and expressive sound-making expressive enabled by a synthesis approach inspired by the late [David Wessel's work on "control intimacy"](https://www.mitpressjournals.org/doi/pdf/10.1162/014892602320582945) and  [Adrian Freed's work on "resonators"](http://www.richarddudas.com/documents/jehan_freed_dudas_icmc1999.pdf).

![caress_bela - play](https://github.com/irllabs/caress_bela/blob/master/documentation/caress_play.png "caress_bela - play")

## Installation
Since the *Caress* is built atop the Bela platform, the first steps require [getting started with the Bela](https://github.com/BelaPlatform/Bela/wiki/Getting-started-with-Bela).   Once you have a Bela up and running:

### caress
Bela works by reading a specific folder for project files and external dependencies/objects.

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
- [MO controller board](https://github.com/batchku/MO/blob/master/PCBs/MO/.MO-v2-6.brd.lck) 
 
    - 2 x strips
    - 2 x joysticks
    
- 2 x piezo-preamps
- 5V litho battery pack

### Controls

![caress_bela - controls](https://github.com/irllabs/caress_bela/blob/master/documentation/caress_controls.png "caress_bela - controls")

## Notes

ml.lib is installed in pd-extentions folder if you wish you use any objects in future Bela projects.
