# USR-26-27-Electrical
The repository for Utah Student Robotics' 2026-2027 competition season. Modularity went pretty well for us last year, so we're leaning even more into it this year!
![[IMG_0287.png|219]]
## Folders
As follows are the various folders in this repo and what they are used for.
### Backplane
- The base-board of our entire robot.
- We reuse existing industry-standard 8-bit "ISA" connectors, which are 62-pin slot-connectors that were most famously used as the expansion slot of choice for the first x86-based PCs produced by IBM.
- See [[Backplane]] for the **slot pinout!**
### Libraries
- These are our KiCAD Symbol and Footprint libraries. Make sure that whatever Symbols and Footprints you use are placed into *these libraries!* We don't want a mess of unsorted library files!
- Make sure to use relative paths! See the table below:

| **Library Type**  | **Path**                                                 |
| ----------------- | -------------------------------------------------------- |
| Schematic symbols | ``${KIPRJMOD}/../Libraries/Symbols/USR-26-27.kicad_sym`` |
| PCB footprints    | ``${KIPRJMOD}/../Libraries/Footprints/USR-26-27.pretty`` |
## Contributing
- Please make a **branch** if you plan to make a new PCB! This way, we have less risk of merge conflicts happening from people working on different PCBs at the same time!
- Add documentation as you go so that we know what is going on!
	- Documentation should be written in the form of **Markdown (.md)** files placed within the project folders.