# Allied Vision Adapter Board CSI-2 for Wandboard i.MX6

![wandboard_imx6-adapter-board](/Images/wandboard_imx6-adapter-board.JPG)

This repository contains open hardware design files for an adapter board supporting the Allied Vision Alvium CSI-2 camera pinout to Wandboards i.MX6 based devices, created by Allied Vision.
The board allows the user to interface with one Alvium MIPI CSI-2 compatible camera over a Flexible Flat Cable (FFC) connector.

## Getting Started

These instructions will get you a copy of the design files to make your own adapter boards for development and testing purposes. 
The board can be produced and assembled using the provided design files. Please take a look at the mechanical layers for more information regarding the PCB stackup recommended for fabrication. 

See our **[website](https://www.alliedvision.com/en/support/technical-documentation/alvium-csi-2-documentation.html)** for further documentation and installation guides of the finished boards.

### Prerequisites

* A running installation of Altium.
* A PCB producer & PCBA manufacturer or some soldering skills.
* One supported embedded board Wandboard i.MX6 series, revision D:
	* Wandboard Solo (i.MX6) WB-IMX6S-BW
	* Wandboard Dual (i.MX6) WB-IMX6U-BW
	* Wandboard Quad (i.MX6) WB-IMX6Q-BW
	* Wandboard QuadPlus (i.MX6) WB-IMX6QP-BW
* One supported MIPI CSI-2 FPC cable
	* Allied Vision part numbers #12316, 12317, 12318
* [One Allied Vision Alvium CSI-2 camera](https://www.alliedvision.com/en/products/embedded-vision-cameras.html)

### Installing

Open the *CSI2-WAND_Rev01.PrjPcb* project file in your Altium environment.

## Built With

* [Altium Designer 19](https://www.altium.com/altium-designer/de)
 
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details