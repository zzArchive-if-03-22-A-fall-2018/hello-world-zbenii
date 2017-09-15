### IF.03.01 Procedural Programming Winter 2017

## Objective
The goal of this assignment is to make you familiar with a first C program and the tool chain how to build it.

## Materials

- Atom or any other editor
- gcc
- terminal.

## Required Tasks
1. We will do all our examples under Linux / Unix. So if you are running your machine under Linux oder MacOS you are already done and may go to the next section.
If you run your computer under Windows, you have to do a bit of preparation work. First of all you have to decide, whether you want to run your machine in dual boot mode or in a virtual box. Prepare your machine in one or the other way. If you decide to use a virtualization you may choose Virtual Box from http: //www.virtualbox.org/wiki/Downloads or use Hyper-V the Windows on-board virtualization software.
Then you create a new virtual machine with the operating system ”Linux” and the Version ”Ubuntu”. Install Ubuntu in its latest LTS (Long Term Support) on this machine. You can get it either from https://duke.htl-leonding.ac.at/ browse_ftp.php?dir=Software/!Betriebssysteme_BootCDs/ or directly from http://www.ubuntu.com/download/ubuntu/download.

2. Set up a directory `PRPR` in the directory `Documents` of your home directory and in this directory another dir `01_hello_world`. Type the program `hello_world.c` with Atom as given in the lecture’s template. This time, don’t forget the block header comment on top of the file and adjust it according to your personal data (your name should be really your name, etc.). You find and image of the block header comment at the very top of our Moodle course.

**IMPORTANT:** Change the program such that it does not print out ”Hello world” but your complete name (i.e., first name and last name) instead of ”world”. For example in my case the program should print out ”Hello Peter Bauer”.
Then open a new terminal and type in the following sequence of commands:
   - `cd ∼/Documents/PRPR/01 hello world 1`
   - `gcc -o hello -Wall -pedantic -std=c99 hello world.c`
   - `./hello`
Then make a screen shot of this terminal window and upload the screen shot together with your hello world.c as solution for your assignment. A sample of such a session is given in figure 1. Take care that the screenshot is in a shape that one can read the content of the terminal.

## Evaluation
All coding assignments will get checked. Most common reasons that your assignment is marked down are:

- Program does not build or builds with warnings
- One or more items in the *Required Tasks* section are not satisfied
- Submitted code is visually sloppy and hard to read

## Things to Learn
- Output in C
- Build C Programs
- Run programs from the terminal
- Work with the terminal

