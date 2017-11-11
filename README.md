# btcAssembler

This project aims to design a program which translates *.bc files to *.asm files.<br />
Example .bc files can be found under .bc files folder.

Needed information about the project can be found under Documentation.<br />

How to run the project:<br />

Open Terminal, go to the file where bitc.java exist<br />
Write “javac bitc.java” to compile<br />
Write “java bitc example.bc” to run it with input file example.bc<br />
You will get “example.asm” file under bitc project file<br />
//There are 2 ways to run it with assembler<br />
If you are using DOSBOX //after you have configured DOSBOX<br />
	Put “example.asm” under DOSBOX<br />
	Write 	“c:”  //to mount<br />
	Write “a86 example.asm”	<br />
	Write 	“example.com” to run<br />
	You will get the output<br />
else //you may configure a86 assembler in Windows XP etc<br />
	In terminal where a86 is ready write “a86 example.asm”	<br />
	Write 	“example.com” to run<br />
	You will get the output<br />
