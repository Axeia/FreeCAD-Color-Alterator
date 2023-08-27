# FreeCAD Color Alterator
user.cfg color alterations made easy.

This macro presents you with a window with all the colors found in user.cfg and clicking on the color (in the color column) pops up a color dialog letting you select a different color. 
It should work with any FreeCAD installation of v0.19 or higher, please report an issue if it doesn't.

![The Color Alterator window](https://i.imgur.com/ptKn3qj.png)

## Installation
Please see the FreeCAD wiki on how to install a macro
https://wiki.freecad.org/How_to_install_macros

## Version notes
**v2:**
Added support for Alpha transparency if it's initially present (fixing [issue #2](https://github.com/Axeia/FreeCAD-Color-Alterator/issues/2)) or when ctrl+shift are held when clicking the color column.

*Note: It's strongly discouraged to use alpha transparency as FreeCADs own UI (at least at present) does not allow editting the Alpha channel so if it works and if it works consistently is unknown. I added the feature for those who like to experiment and know that they're playing with fire.*

## License
FreeCAD wants the license for a macro in a specific format so I've put it as 
* CC0-1.0 (Basically public domain, see https://creativecommons.org/publicdomain/zero/1.0/)
* Github allows selecting a license and I didn't find CC0-1.0 so I went with the unlicense which is bascically the same thing

Realistically  all you need to know is that is work done for the 'greater good'. I'm not here to make a profit and you can do whatever you want with the code :)
