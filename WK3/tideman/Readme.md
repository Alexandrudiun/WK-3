# README
This is a program that implements the Tideman voting system, which allows voters to rank candidates in order of preference. The program takes in a list of candidates as command line arguments and prompts the user for the number of voters. It then asks each voter to rank the candidates in order of preference. Once all votes have been recorded, the program determines the winner using the Tideman method, which involves creating a graph of candidate pairs and eliminating the pair with the most defeats until only one candidate remains.

# Dependencies
csbootcamp.h: a library provided by CS50 Bootcamp containing helper functions such as get_int and get_string for user input
stdio.h: the standard input/output library in C, containing functions such as printf for output and scanf for input
string.h: the string library in C, containing functions such as strcmp for comparing strings
