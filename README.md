# USR-26-27-Electrical
The repository for Utah Student Robotics' 2026-2027 competition season. Modularity went pretty well for us last year, so we're leaning even more into it this year!
<p align="center">
<img src="Media/IMG_0287.png" width="400" alt="USR Logo">
</p>

## Folders
As follows are the various folders in this repo and what they are used for.
### Backplane
- The base-board of our entire robot.
- We reuse existing industry-standard 8-bit "ISA" connectors, which are 62-pin slot-connectors that were most famously used as the expansion slot of choice for the first x86-based PCs produced by IBM.
- See [Backplane](Backplane/Backplane.md) for the **slot pinout!**
### Demoboard
- A soldering-demo/trainer PCB meant for electrical team newbies to practice their (micro)-soldering.
- "You WILL learn how to microsolder" - Vincent
- See [Demoboard](Demoboard/Demoboard.md) for a tiny bit more details

<hr><hr>

## Libraries
- These are our KiCAD Symbol and Footprint libraries. Make sure that whatever Symbols and Footprints you use are placed into *these libraries!* We don't want a mess of unsorted library files!
- Make sure to use relative paths! See the table below:

| **Library Type**  | **Path**                                                 |
| ----------------- | -------------------------------------------------------- |
| Schematic symbols | ``${KIPRJMOD}/../Libraries/Symbols/USR-26-27.kicad_sym`` |
| PCB footprints    | ``${KIPRJMOD}/../Libraries/Footprints/USR-26-27.pretty`` |
| Design blocks		| ``${KIPRJMOD}/../Libraries/DesignBlocks/USR-26-27.kicad_blocks``  |
| Component 3D Models | ``${KIPRJMOD}/../Libraries/3DModels``	|

<hr><hr>

## Contributing
- Please make a **branch** if you plan to make a new PCB! This way, we have less risk of merge conflicts happening from people working on different PCBs at the same time!
	- When you're done, open a **pull-request**, assign an electrical lead as a reviewer, and wait for it to be reviewed and approved.
- Add documentation as you go so that we know what is going on!
	- Documentation should be written in the form of **Markdown (.md)** files placed within the project folders.

<hr><hr>

<span style="opacity: 0.25;">what are you doing down here the readme's over</span>