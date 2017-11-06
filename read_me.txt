Tamara Alhajj

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
