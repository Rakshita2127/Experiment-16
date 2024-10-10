# Experiment-16
## Theory:
Runtime anomalies or unusual circumstances that a program runs into are known as exceptions. In C++, exception handling is a technique that enables a program to handle unforeseen or exceptional circumstances (like runtime errors) in an organized manner, guaranteeing that the program can either continue to run or end gracefully. 
###
For this, C++ offers the following specific keywords:
###
`try`: Indicates a code block with the ability to raise an exception.
###
`catch`: Indicates a block of code that is run in response to a specific exception.
### 
`throw`: An exception is thrown using this command.
###
1. The `throw` statement gains control when an exception is found.
2. Depending on the type of exception, the `throw` statement jumps to the relevant `catch` block.
3.  Once caught, the `catch` block executes, after which the program can either recover or terminate based on the logic implemented.

## Program 1
### Aim: 
Prompt the user to enter a positive number. If the user enters a positive number, display that number. If the user enters a negative number throw an exception.
### Software used: 
Visual Studio Code
### Output:
<img width="740" alt="image" src="https://github.com/user-attachments/assets/5dc8e570-5d58-43ea-88ad-2bb2bc43ed03">

### Conclusion:
We applied exception handling in C++ to check whether a negative or positive integer. 

## Program 2
### Aim: 
Prompt the user to enter a year greater than 2000. If the user enters the year greater than 2000, then display that year. If the user enters a year less than 2000 throw an exception.
### Software used: 
Visual Studio Code
### Output:
<img width="785" alt="image" src="https://github.com/user-attachments/assets/4ed3a26c-67ec-4d85-8a03-cfa2ed5912a5">

### Conclusion:
We applied exception handling in C++ to check whether the entered year belongs to the 21st century or not. 
