# IncrementationProgram
Program to Show Incrementation of MText, MLeaders, Blocks, and Text

IncrementationforAutoCAD
Program that adds or subtracts values from MText, MLeaders, and DBText in AutoCAD

To use program:

Download IncrementationProgram.dll from the main page, save it on computer
Start AutoCAD, type "Netload", Navigate to downloaded .dll file, select file in file explorer, click open on file explorer
Type "IncrementUp" or "IncrementDown" to begin program.
Select objects you want to increment (by default, program only works with MText, MLeaders, Text, and Blocks that have the attribute "STRUCTURENAME" in the block attributes field)
Enter in the value of how much you want to increment up or down
Hit enter
Program will automatically search the text for the last set of digits if input is combination of words and numbers. For example, HH-3-21, incremented by one, will turn HH-3-21 into HH-3-22. If input is just letters, nothing will happen. If input is just numbers, program will work as intended.

When subtracting numbers, 0 is the lowest number available. This program does not support negative numbers.
