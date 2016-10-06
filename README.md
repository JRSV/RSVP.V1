# JRSV_Presets
State Saving System for Pure Data

JRSV_presets is a state saving system for Pure  Data (http://puredata.info/). It was created to offer Pure Data users a way to record presets for the GUI objects inside patches.

## Getting Started

Download the package and  set the path in Pure Data. Call the provided objects in your Pure Data file. It is also recomended to always use the package locally for each project. This way you can customize the library for each project; this allows you to change the colors and size of the GUIs.

    [GUI-creator <arg>] 
    
The argument will be the unique ID which the GUIs will be created with.
This module will allow you to create the GUIs available by clicking the options.
Then create the abstraction to save and recall the presets:

    [PresetManager <arg>]
    
The argument will provide the prefix name for the text file recorded in the same path as the patch.
Modify the GUI values and record and recall your values.

### Tutorial

for more information and video tutorials from YOUTUBE please visit:
(http://www.jrsv.net/pure-data-preset-system)

### Prerequisities

JRSV_presets depends on the following libraries available through the "DEKEN" package manager inside PD (comes with vanilla 0.47-1 or can be installed separetly). Make sure to download and install each package .  Set the path to the libraries in PD preferences and if necessary load/declare the libraries

  - HCS
  - iemguts
  - iemlib
  - flatgui
  - cyclone
  - tof
  - zexy

### Author

José Rafael Subía Valdez (www.jrsv.net)

### License

This Project is released under GPL version 3 license agreement. More details available in the https://raw.githubusercontent.com/JRSV/JRSV_Presets-0.1/master/LICENSE.txt file

### Acknowledgments

I would like too thank all the PD community that activily participate in the different gathering points of information (LIST and FACEBOOK) specially to the following  people that helped me with ideas and solutions to the problems:

   - Matt Barber
   - Liam Goodacre
   - Thomas Grill
    
