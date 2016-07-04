# gs1-Gcode-Scanner
Program to scan G-code files and check for command quantities and potential errors

Usable, but still under development.

This is a quick reference for using GS1 (Gcode Scan 1). This program is for scanning multiple G-code files to assess quantity of various commands and potentially catch errors.

The program is in the folder as gs1.exe. It must be accessed via the command line. Use Windows Power Shell for best results. CD the file, and then usage is as follows:

./gs1 filename.txt % X filename.txt % X filename.txt % X filename.txt % X

Where X is the particular G-code instruction you're looking for (Q23, 2122001, G03 etc.).

filename.txt would be the G-code file you wish to scan. File input is case sensitive and you must eliminate spaces or you will get an error.

You can do up to 4 seperate files, or you can do one file to scan for 4 different commands, but you still must enter the file name each time.

After you hit enter you will get a screen showing the total lines per file, quantities of the commands which you query, and a visual representation to compare total lines vs. commands.

Press ? to get further assistance/tools.

2016 Shawn Fratis
