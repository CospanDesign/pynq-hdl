# pynq-hdl

Collection of Pynq HDL Projects used to demonstrate a specific feature

Each project contains:

* An archive that contains a Vivado project along with all the source code.
* PDFs for each of the block diagrams.
* A Bitfile and TCL file that can be used for programming a Pynq board.


To use any of the following projects the user must use the current master of [Cospan Design Pynq Fork](https://github.com/CospanDesign/PYNQ)

Description of each project

* Simple VDMA: Used to demonstrate transferring video frames between two VDMA cores within the FPGA. To use this the Pynq software must have support for VDMA. A notebook demonstrating this simple VDMA can be found here [pynq notebooks](https://github.com/CospanDesign/pynq-notebooks)
* Simple HLS VDMA: Used to demonstrate a simple HLS core (the core only passes through the frames). To use this the Pynq software must have support for VDMA. A notebook demonstrating the Simple HLS VDMA pass through can be found here [pynq notebooks](https://github.com/CospanDesign/pynq-notebooks)
* HLS Corners: Used to demonstrate corner detection using an HLS core. A notebook demonstrating HLS Corners can be found here [pynq notebooks](https://github.com/CospanDesign/pynq-notebooks)
