# BOP-Case
A 3D-printed gasket mounted, invertable case for the BOP keyboard

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

<img src="https://github.com/Technofrikus/BOP-Case/blob/main/pictures/Bop%20case%206.jpg?raw=true" alt="header" width="800"/>


---
### About the BOP

[The BOP](https://github.com/blewis308/BOP-Keyboard) is a 6x20 ortholinear keyboard made by [fruitykeeb](https://www.fruitykeeb.xyz). The GB ran in May 2021. They keyboard itself is made with an FR4-Bottom-Plate and Standoffs. But I wanted a "real" case for it.

This case is designed to be as flat as possible, to reduce height of the keyboard for better typing. The bottom plate and the standoffs have to be removed. Only the top plate and PCB are used.

**Untested Detail:**

I used Millmax-Sockets to mount the Teensy as low as possible to the PCB (not a good idea, it moves too easily in the sockets and looses connection from time to time). So I dont know what the normal height of the Teensy is when mounted the default way. There is 8,8mm space between the PCB and the lower case. Please doublecheck that your Teensy is not higher.

### Version 1.1
I did not print this version yet. I printed version 1.0 and no major changes were made. Just be aware that small issues could still be there. Please let me know if there are.


### Features of the case
- Gasket mounted
- split in the middle, so can be printed on middle sized printes (biggest part is 208x136mm)
- Typing angles: -6, 0, 6 degrees
- High profile, no floating keycaps

---

[3D files of the case](3D-files/)

[More pictures](pictures/)


---
## Hardware needed
- Printed Case (obviously), feet optional, only needed for a typing angle other than 0 degree
- 10x M3x20 button head screws (ISO 7380 or similar. But not ISO 4762, they are too tall!) 
- 4x M3x5 screws to mount the feet (slightly longer or shorter length work as well)
- 2mm EPDM foam or similar for the gaskets
- some glue for the gaskets
- scissors for cutting the gaskets

---

## Printing tips
- Please use support for the top left and bottom left part. But only on the connectors (dovetails). Not everywhere.
- Several holes are closed with a 0,2mm thin layer, so no supports are needed there. Please just push through them with a screw.
- When printing in PLA with the powder coated bed (Prusa) I would recommend using a brim. Otherwise warping might occur.
- The tabs for the screws will be cut by the screws. So maybe increase the perimeters a little.
- The dovetail connections are tight, tight, tight, so a well calibrated printer might be necessary. Also: they are not easy to disassemble. 
- Total printing time is about 23hrs in quality settings with 0,2mm layer height.

---

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
