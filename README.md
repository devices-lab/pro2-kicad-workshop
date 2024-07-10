# PCB design walkthrough with KiCad

![Render of the solder:bit Gamepad PCB](/renders/front.png "A render of the solder:bit Gamepad version of the board")

A KiCad workshop for the pro² device prototyping and production summer school. 

## Tasks

You are given the task of extending the solder:bit Gamepad boards with more NeoPixels. A design review has highlighted that we need more blinking lights than the 5x5 LED matrix on the micro:bit can supply!

1. Download the existing design files by cloning this repository.
2. Get familiar with the NeoPixel (WS2812B) datasheet and the exisiting schematic for version 0.5.
2. Open up KiCad, and begin with the Schematic Editor - adding symbols, assiginging footprints, adding values, etc.
3. Move onto the PCB Editor and import the changes from the schematic - moving footprints, routing, zone filling, DRC, etc.
4. Build a bill of materials (BOM) and a set of Gerber fabrication files for the next workshop!
5. Use Git for version control of your KiCad project.

![KiCad 8.0 Schematic Editor preview](/renders/media/schematic_editor.png)
![KiCad 8.0 PCB Editor preview](/renders/media/pcb_editor.png)

Don’t worry if you don’t manage to get all the steps here completed, as we also supply a set of completed production files (BOM and Gerber files) in the same repository which can be used for the next session.

## Handy web links

[KiCad 8.0 documentation](https://docs.kicad.org/8.0/en/)
[Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

## Credits

Thanks to [Dr John Vidler](https://github.com/JohnVidler) and [Aron Eggens](https://github.com/mac-aron), the Computing and Communications departement at Lancaster University, and everyone at the [Devices Lab](https://github.com/devices-lab).
