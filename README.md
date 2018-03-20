# Error Correction Code Using Bit Manipulation #

Last Modified: January 13, 2017

### What is this repository for? ###

* COMP2401 Assignment 1
* Objectives: To understand and implement bit manipulation of integers to transmit a message by correctly setting parity bits. Then receive correct messages with the functions for error correction and converting from short integer to char.

### How do I get set up? ###

Compile the transmit program
gcc –o tran transmit.c bit_manipulation.c

Compile the receive program
gcc –o recv receive.c bit_manipulation.c

Start the transmit program with ./tran

The program will prompt the user to enter a message.
Then print the transmitted message as a sequence of short integers.

Start the receive message with ./recv

The program will prompt the user to enter the transmitted message. 
Here you will have to copy the output from transmit program. 
The program should output the uncorrected transmitted message and the corrected message.


### Sample Usage ###
$ ./tran
Please enter a message to transmit: hello world


Transmitted message (short integers):
3732 3144 3264 7360 3326 1280 3945 7420 3378 2240 3286 

$ ./recv
Please enter the transmitted message: 3732 3144 3264 7360 3326 1280 3945 7420 3378 2240 3286


Transmitted Message:
xel�o w�bLl


Corrected Transmitted Message:
hello world


### Authors ###

Tamara Alhajj
Prof. Doron Nussbaum
