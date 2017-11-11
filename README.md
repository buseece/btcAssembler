# btcAssembler

This project aims to design a program which translates *.bc files to *.asm files.<br />
The Description of the project can be found under cmpe230fall2017hw1.pdf <br />
Example input files can be found under inputFiles folder. <br />


How to run the project:<br />

1. Open Terminal, go to the file where bitc.java exist<br />
2. Write “javac bitc.java” to compile<br />
3. Write “java bitc example.bc” to run it with input file example.bc<br />
4. You will get “example.asm” file under bitc project file<br />
   //There are 2 ways to run it with assembler<br />
5. If you are using DOSBOX //after you have configured DOSBOX<br />
	* Put “example.asm” under DOSBOX<br />
	* Write 	“c:”  //to mount<br />
	* Write “a86 example.asm”	<br />
	* Write 	“example.com” to run<br />
	* You will get the output<br />
6. Else //you may configure a86 assembler in Windows XP etc<br />
	* In terminal where a86 is ready write “a86 example.asm”	<br />
	* Write 	“example.com” to run<br />
	* You will get the output<br />
