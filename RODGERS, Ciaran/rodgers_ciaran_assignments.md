# Assignment for RODGERS, Ciaran

## Task 1

**Problem:** Determine if the number `a` is divisible by `b` without a remainder using only arithmetic operations. Branching, loops, and functions are prohibited. Output "YES" if divisible, otherwise "NO".

### Input:
- Two integers `a` and `b`.

### Output:
- "YES" if `a` is divisible by `b`, otherwise "NO".

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 10<br>2| YES     |
| 2   | 5<br>3 | NO      |
| 3   | 15<br>5| YES     |

### Note:
Tests the application of arithmetic and boolean algeebra operations to solve divisibility.


## Task 2
**Problem:** Write a program to calculate the body mass index, which is calculated by the formula: `index = mass / (height * height)`. The user enters the values of height (in meters) and mass (in kilograms), and the program calculates the body mass index and outputs the corresponding message: 
- `underweight` (low mass, index less than `18.5`), 
- `normal weight` (normal mass, index `18.5-24.9`), 
- `overweight` (excessive mass, index more than `24.9`).

| No. | Inputs      | Outputs                                       |
| --- | ----------- | --------------------------------------------- |
| 1   | 1.79<br>88    | Your body mass index is: 27.46, that is overweight. |
| 2   | 1.90<br>85    | Your body mass index is: 23.55, that is normal weight. |
| 3   | 1.60<br>50    | Your body mass index is: 19.53, that is normal weight. |



## Task 3
**Problem:** Given a `four-digit number`. Check if it is a `palindrome`. A palindrome is a number, word, or text that reads the same left to right and right to left. For example, in our case, palindrome numbers will be: `1221`, `4444`, `9119`, etc.

### Input:
- An `integer` representing the four-digit number.

### Output:
- A `boolean` indicating whether the number is a palindrome.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 4556 | False |
| 2   | 8118 | True |
| 3   | 1221 | True |

### Note:
The problem tests the ability to `work with digits` of a number and `compare` their values.



## Task 4


**Problem:** Write a program to output all integers from `20` to `n` inclusive (where `n > 20`), where `n` is an integer entered by the user.


### Input:
- An integer representing the upper limit of the range.

### Output:
- A sequence of integers from `20` to `n` inclusive.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 25     | 20 21 22 23 24 25 |
| 2   | 30     | 20 21 22 23 24 25 26 27 28 29 30 |
| 3   | 37     | 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34 35 36 37 |
| 4   | 20     | 20 |

### Note:
The problem tests the ability to use loops and conditional statements to print a sequence of numbers.



## Task 5

**Problem:** Write a program to print all integers formed from the input number by discarding the last digit from each previous number.

### Input:

- An integer representing the input number.

### Output:

- A sequence of integers formed from the input number by discarding the last digit from each previous number.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 138945 | 13894<br> 1389<br> 138<br> 13<br> 1 |
| 2 | 123456 | 12345<br> 1234<br> 123<br> 12<br> 1 |
| 3 | 987654 | 98765<br> 9876<br> 987<br> 98<br> 9 |




# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
