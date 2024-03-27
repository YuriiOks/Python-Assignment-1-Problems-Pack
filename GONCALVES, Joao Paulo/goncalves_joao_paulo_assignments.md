# Assignment for GONCALVES, Joao Paulo

## Task 1

**Problem:** Determine if a given four-digit number is symmetric. If it is, print 1; otherwise, print any other integer. Assume the number is left-padded with zeros if it has less than four digits.

### Input:
- A four-digit integer or fewer, left-padded with zeros if necessary.

### Output:
- 1 if the number is symmetric, or another integer if it is not.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 2002   | 1       |
| 2   | 1234   | 0       |
| 3   | 1221   | 1       |


## Task 2

**Problem:** Write a program that asks the user to enter a person's age (an integer). The program should output a message about whether the person is an infant, a child, a teenager, or an adult according to the following rules: 
- if the person is `1` year old or less, he or she is an infant, 
- if the person is older than `1` year but younger than `13` years, they are a child, 
- if the person is not younger than `13` years but younger than `20` years, they are a teenager 
- and if the person is older than `20` years, they are an adult.

### Input:
- An integer representing the age of the person.

### Output:
- A string message indicating the age group of the person.

### Examples:

| No. | Inputs | Outputs               |
| --- | ------ | --------------------- |
| 1   | 3      | You are a child.      |
| 2   | 14     | You are a teenager.   |
| 3   | 25     | You are an adult.     |

### Note:
The problem tests the ability to use conditional statements to classify an input into one of several categories.



## Task 3

**Problem:** Given a `three-digit integer`. Determine the `sum of the first and last digits` of the number and `compare` it with the `value of the second digit` of the number. Accordingly, output the message: `>`, `<` and `=`.

### Input:
- An `integer` representing the three-digit number.

### Output:
- A `string` indicating the comparison result.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 122 | > |
| 2   | 121 | = |
| 3   | 263 | < |

### Note:
The problem tests the ability to work with digits of a number and compare their values.




## Task 4

**Problem:** Given `n` integers. Each number is entered on a separate line. Calculate the sum of the numbers.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 10<br>0<br>1<br>2<br>3<br>4<br>5<br>6<br>7<br>8<br>9 | 45 |
| 2   | 3<br>1<br>2<br>3 | 6 |
| 3   | 1<br>1 | 1 |


## Task 5

**Problem:** Write a program to print all two-digit numbers, the sum of the squares of the digits of which is divisible by `n`. The number `n` is an integer entered by the user.

### Input:

- An integer representing the number `n`.

### Output:

- A sequence of two-digit numbers, the sum of the squares of the digits of which is divisible by `n`.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 5 | 	12, 13, 17, 18, 21, 24, 26, 29, 31, 34, 36, 39, 42, 43, 47, 48, 50, 55, 62, 63, 67, 68, 71, 74, 76, 79, 81, 84, 86, 89, 92, 93, 97, 98 |
| 2 | 7 | 70, 77 |
| 3 | 10 | 13, 17, 24, 26, 29, 31, 34, 36, 39, 42, 43, 47, 48, 51, 53, 54, 57, 58, 62, 63, 67, 68, 71, 74, 76, 79, 82, 83, 87, 88, 91, 93, 94, 97, 98 |
| 4 | 100 | 68, 86|
| 5 | 162 | 99 |

### Note:

The problem tests the ability to use loops and conditional statements to print a sequence of numbers.





# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
