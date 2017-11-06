# README #

### What is this repository for? ###

* Date: January 13, 2017
* COMP2401 Assignment 1 Part 2 Programming – Error Correction Code
* Objective: To understand and implement bit manipulation of integers

### How do I get set up? ###

Compile the transmit program
gcc –o tran transmit.c bit_manipulation.c

Compile the receive program
gcc –o recv receive.c bit_manipulation.c

Start the transmit program with ./tran
The program will prompt the user to enter a message.
Then print the transmitted message as a sequence of short integers.
Objective: correctly setting the parity bits

Start the receive message with ./recv
The program will prompt the user to enter the transmitted message. 
Here you will have to copy the output from transmit program. 
The program should output the uncorrected transmitted message and the corrected message.
Objective: Correctly completing the functions for error correction and converting from short integer to char

### Authors ###

Prof. Doron Nussbaum
Student Tamara Alhajj