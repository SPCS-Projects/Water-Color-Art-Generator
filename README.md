# Watercolor Art Generator

## Overview
This Python script generates watercolor art images by overlaying randomly deformed shapes of different colors. Each run produces a unique composition with vibrant colors and varied shapes, resembling a watercolor painting.

## Dependencies
This script requires the "pycairo" library, it can be installed with `pip install pycairo` or by doing `pip install -r requirements.txt` while in the script directory

## Command-line Arguments
If no arguments are provided it will use default settings  
--width: Width of the generated image (default: 1000).  
--height: Height of the generated image (default: 1500).  
-i, --initial: Initial deformations of shapes (default: 120).  
-d, --deviation: Deviation in deformations (default: 50).  
-bd, --basedeforms: Number of base deformations (default: 1).  
-fd, --finaldeforms: Number of final deformations (default: 3).  
-mins, --minshapes: Minimum number of shapes (default: 20).  
-maxs, --maxshapes: Maximum number of shapes (default: 25).  
  
### Example
python watercolor_art_generator.py --width 1200 --height 1800 -i 150 -d 70 -bd 2 -fd 4 -mins 15 -maxs 30   