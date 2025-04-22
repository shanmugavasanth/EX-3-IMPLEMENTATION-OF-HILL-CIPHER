## EX : 3 IMPLEMENTATION OF HILL CIPHER

## AIM:

To develop a simple C program to implement Hill Cipher.

## DESIGN STEPS:

Step 1:

Design of Hill Cipher algorithnm

Step 2:

Implementation using C or pyhton code

Step 3:

1.	Convert each letter of the message to a number (A = 0, B = 1, ..., Z = 25) and divide the message into blocks of size n.
2.	Select an invertible n × n matrix as the cipher key (modulo 26 for the English alphabet).
3.	Multiply each block of n letters by the cipher key matrix (modulo 26) to get the encrypted numbers.
4.	Convert the encrypted numbers back into letters using the reverse of step 1.
5.	Multiply the encrypted blocks by the inverse of the cipher key matrix (modulo 26) to recover the original message.
6.	Ensure the key matrix is invertible (mod 26) for decryption to be possible.


## PROGRAM:

## OUTPUT:

## RESULT:
