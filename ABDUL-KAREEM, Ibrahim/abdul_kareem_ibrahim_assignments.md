# Assignment for ABDUL-KAREEM, Ibrahim

## Task 1

**Problem:** Write a program to convert the entered seconds into days, hours, minutes and seconds.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 6785   | 0 day(s), 1 hour(s), 53 minute(s), 5 second(s) |
| 2   | 456789 | 5 day(s), 6 hour(s), 53 minute(s), 9 second(s) |
| 3   | 86401  | 1 day(s), 0 hour(s), 0 minute(s), 1 second(s)  |

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
**Problem:** Write a program in which the user enters the value of the current date: day, month, and year (integer numbers), and the program outputs tomorrow's date in the format: `dd.mm.yyyy`.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 1<br>1<br>2020 | 02.01.2020 |
| 2   | 28<br>2<br>2020 | 29.02.2020 |
| 3   | 31<br>12<br>2020 | 01.01.2021 |


**Notes:** All the examples above are solved using Python. You can find the solutions in the [examples](./examples) folder. Covered with explanations and comments, these examples will help you understand the practical implementation of the concepts covered in this module. Python tests are also included to verify the correctness of the solutions.

## Task 4

**Problem:** Write a program to print integers from `1` to `n` with the number of `#` characters equal to the value of the number.

### Input:
- An integer representing the upper limit of the range.

### Output:
- A sequence of integers from `1` to `n` inclusive, with the number of `#` characters equal to the value of the number.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 5      | 1 #<br>2 ##<br>3 ###<br>4 ####<br>5 ##### |
| 2   | 3      | 1 #<br>2 ##<br>3 ### |
| 3   | 7      | 1 #<br>2 ##<br>3 ###<br>4 ####<br>5 #####<br>6 ######<br>7 ####### |

### Note:
The problem tests the ability to use conditional statements to classify an input into one of several categories.



## Task 5

**Problem:** A surveillance camera automatically registers the speed of passing cars, rounding the speed values to integers. It is necessary to determine the average registered speed of all cars. If the speed of at least one car was more than 60 km/h, print Yes, otherwise print No. The program receives the number of registered cars `n` (1 ≤ `n` ≤ 30) as input, then the speeds of the cars are indicated. The speed value cannot be less than 1 and more than 300. The program should first print the average speed with an accuracy of one decimal place, then Yes or No.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 3<br>50<br>45<br>65 | 53.3<br>Yes |
| 2   | 2<br>100<br>200 | 150.0<br>Yes |
| 3   | 1<br>30 | 30.0<br>No |


# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
