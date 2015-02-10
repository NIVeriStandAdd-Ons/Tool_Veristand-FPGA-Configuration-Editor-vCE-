##  Veristand FPGA Configuration Editor (VCE) ##

VCE is a graphical editor that allows to manipulate .fpgaconfig files.

### LabVIEW Version ###

2014

### Built Availability ###

There are two builds available in the *Export\2014* folder. It is divided in two different parts:

- **EXE** contains the executable only that can be run from whatever location on disc
- **Installer** is the windows installer that places the executable above in the <LabVIEW folder>\Project so it can be called from the LV *Tools* menu.

For building code for other releases, please open the *Veristand FPGA Configuration Editor.lvproj* LV project and build the *VCE* and then vCE-Installer build specifications respectively.

### Quality, Limitations ###

Code has a limited set of feature required to manipulate .fpgaconfig files associated to FPGA bitfiles. More information located in *Documentation\getting_started.pdf* document

### Dependencies ###

LV runtime 2014 is needed to run the exe.
To open and modify source code, you need LabVIEW Development environment 2014 or later.

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*