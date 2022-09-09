# Week 2 Assignment 3

This assignment lets you practice with conditional blocks (i.e. if statements). One of the common uses of conditional blocks is to check the consistency of input values. Often we design functions or programs to only work on specific types or values of input and we want to avoid the program to return random results or to get stuck when the input is not correct.

TASK: Write a program that, given an input number, it computes its natural logarithm using the numpy log() function. The program should print a clear message if the input number is not an allowed value of the log() function. 

EXPECTED OUTCOME: When called with an input of 2.718 (an approximation of e), the code should return a value close to 1. When called with a value smaller or equal to 0, the code should return a message "The value you entered is not a valid input for the log() function, choose a number greater than 0".