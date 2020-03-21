# How to load program to PIC16F877A using PICKIT3

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

We can upload program in two different ways.
- Using Pickit3 Standalone Programmer
- Using MPLAB IPE

## Using PICKIT3 Standalone Programmer

1.Download the Pickit3 Software from [here](https://github.com/Rkcreativeworks/PICKIT3/raw/master/PICkit3%20Programmer%20Application%20Setup%20v3.10.zip)
2.Extract the files and Install the software by double clicking on the [Setup.exe]() 
3.Connect the programmer to the Development board according to the Pinout shown below
![](https://i.stack.imgur.com/9O7cI.png)
4.After connecting the PICKIT3 to the Development board and connect the programmer to the computer using USB Cable.
5.Run the PicKit3 software as an [Administrator]() otherwise it will not close properly.
6.Download the OS by going to TOOLS->Download Operating System.
7.Choose the operating system file [C:\Program Files (x86)\Microchip\PICkit 3 v3]()
```bash
PK3OSV020005.hex
```
8.After downloading the OS is Sucessfull import the project file and click on write to upload it to the board.

## Using MPLAB IPE Software
- Firstly download and install the XC8 Compiler from [here](http://ww1.microchip.com/downloads/en/DeviceDoc/xc8-v2.05-full-install-windows-installer.exe)
- Download and install MPLAB x IDE from [here](http://ww1.microchip.com/downloads/en/DeviceDoc/MPLABX-v5.15-windows-installer.exe)
- Open MPLAB IPE
- Go to Advance options by entering password   "microchip"
- Go to power and enable the power to target option
- Browse the .hex file and upload
