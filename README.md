# How to load program to PIC16F877A using PICKIT3

We can upload program in two different ways.
- Using Pickit3 Standalone Programmer
- Using MPLAB IPE

## Using PICKIT3 Standalone Programmer

- Download the Pickit3 Software from [here](https://github.com/Rkcreativeworks/PICKIT3/raw/master/PICkit3%20Programmer%20Application%20Setup%20v3.10.zip)
- Extract the files and Install the software by double clicking on the [Setup.exe]() 
- Connect the programmer to the Development board according to the Pinout shown below
![](https://i.stack.imgur.com/9O7cI.png)
- After connecting the PICKIT3 to the Development board and connect the programmer to the computer using USB Cable.
- Run the PicKit3 software as an [Administrator]() otherwise it will not close properly.
- Download the OS by going to TOOLS->Download Operating System.
- Choose the operating system file [C:\Program Files (x86)\Microchip\PICkit 3 v3]()
```bash
PK3OSV020005.hex
```
- After downloading the OS is Sucessfull import the project file and click on write to upload it to the board.
