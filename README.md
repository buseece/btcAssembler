# btcAssembler

This project aims to design a program which translates *.bc files to *.asm files.
Example .bc files can be found under .bc files folder.

Needed information about the project can be found under Documentation.

How to run the project:

Open Terminal, go to the file where bitc.java exist
Write “javac bitc.java” to compile
Write “java bitc example.bc” to run it with input file example.bc
You will get “example.asm” file under bitc project file
//There are 2 ways to run it with assembler
If you are using DOSBOX //after you have configured DOSBOX
	Put “example.asm” under DOSBOX
	Write 	“c:”  //to mount
	Write “a86 example.asm”
	Write 	“example.com” to run
	You will get the output
else //you may configure a86 assembler in Windows XP etc
	In terminal where a86 is ready write “a86 example.asm”
	Write 	“example.com” to run
	You will get the output
