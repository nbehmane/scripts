# Nima's Scripts

Here are scripts that I've made to make my life easier. 
NOTE! 
Some of these scripts won't work unless you are on CSL.
These are marked with *

## Installation

Clone the repo, and add the directory to your PATH.

## mkexe

mkexe creates an executable file, with a specified language.

Usage:
$mkexe FILENAME LANGUAGE

Example) 
$mkexe some_bash_script bash
-> will create an executable file called some_bash_script, with the shebang added.

Supported File Types:
Currently only c, python, and bash files are supported.

$mkexe FILENAME c

$mkexe FILENAME bash

$mkexe FILENAME python
  
## exercise  *

Will create an Exercise folder containing the requirements, the Makefile, and a
template main.c

Usage:
$exercise EXERCISE NUMBER

Example)
$exercise 1

## styleCheck  *

Will iterate through a given set of files, and checks them one by one.

Usage:
$styleCheck FILE1 FILE2 FIL3 ...
 
Example)

$styleCheck main.c otherfile.c anotherfile.c yougetthepoint.c

## License
https://www.gnu.org/licenses/gpl-3.0.en.html
