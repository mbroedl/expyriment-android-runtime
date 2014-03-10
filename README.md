expyriment-android-runtime
==========================

Main repository of **Expyriment** Android Runtime

*GNU General Public License v3*  
Florian Krause (florian@expyriment.org) & Oliver Lindemann (oliver@expyriment.org)

Building the Android app
------------------------

* Download PGS4A (version 0.94) from http://pygame.renpy.org/dl
* Copy all files in this repository into a folder called 'expyriment_app', inside the PGS4A folder
* Copy the (released!) Expyriment source code (the 'expyriment' folder) into the 'expyriment_app' folder
* Run
    ./android.py configure expyriment_app
* Run
    ./android.py build expyriment_app release


Expyriment 
==========
**Expyriment** is an open-source and platform-independent lightweight Python
library for designing and conducting behavioral experiments: http://www.expyriment.org
