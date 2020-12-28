# intal
A library implemented in C for the integers of arbitrary length (intal)

An intal is a non-negative integer of arbitrary length. 
It is stored in the form of a string of ASCII characters terminated by a null character ‘\0’. 
It consists of decimal digits (‘0’ to ‘9’) and is stored in big-endian style i.e. the most significant digit is at the head of the string. 
The different data types supported by C for storing integer values are short, int and long. They use 2, 4 and 8 bytes respectively. 
The largest unsigned value that can be stored in long long is 18466744073709551615, which is merely 20 digits long. 
On the other hand, the intal library that we are developing can store a number consisting of a maximum of 1000 digits and perform various different operations with it. 
The integer is stored in the form of a string, thereby making the storage memory efficient. 
The different applications implemented in this library are - 
1. Addition
2. Subtraction
3. Multiplication
4. Modulo
5. Comparison
6. Finding the minimum number in array of intals
7. Finding the maximum number in array of intals
8. Sorting an array of intals
9. Finding binomial coefficient 
10. GCD of two intals 
11. Factorial 
12. Search operation on array of intals
