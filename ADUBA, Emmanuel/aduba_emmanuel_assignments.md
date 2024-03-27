# Assignment for ADUBA, Emmanuel

## Task 1

**Problem:** Given the number of seconds `n` that have passed since the beginning of the day, calculate what time the electronic clock will show in `h:mm:ss` format.

### Input:
- An integer `n` representing the number of seconds.

### Output:
- The time in `h:mm:ss` format.

### Examples:

| No. | Inputs   | Outputs    |
| --- | -------- | ---------- |
| 1   | 3602     | 1:00:02    |
| 2   | 4556789  | 17:46:29   |
| 3   | 4568     | 1:16:08    |

### Note:
Assumes a 24-hour clock format

## Task 2

**Problem:** Write a program to output the text version of school grades: `1, 2, 3` (initial level), `4, 5, 6` (average level), `7, 8, 9` (sufficient level), `10, 11, 12` (high level). If the grade is outside the range `1` to `12`, the program should output "level is absent".

### Input:
- An integer representing the school grade.

### Output:
- A string message indicating the level of the grade or a message indicating that the level is absent.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 7      | sufficient level |
| 2   | 10     | high level |
| 3   | 15     | level is absent |

### Note:
The problem tests the ability to use conditional statements to classify an input into one of several categories.



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

**Problem:** Write a program to print all integers from `a` to `b` inclusive that are multiples of `c`. The numbers `a`, `b`, and `c` are integers entered by the user.

### Input:
- Three integers representing the lower limit `a`, upper limit `b`, and the multiple `c`.

### Output:
- A sequence of integers from `a` to `b` inclusive that are multiples of `c`.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 1<br>10<br>2 | 2 4 6 8 10 |
| 2   | 3<br>15<br>3 | 3 6 9 12 15 |
| 3   | 5<br>20<br>5 | 5 10 15 20 |

### Note:
The problem tests the ability to work with digits of a number and compare their values.




## Task 5

**Problem:** Given integers `a` and `b`. Calculate `a` to power of `b` without using the exponentiation operation.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 2<br>3  | 8       |
| 2   | 3<br>3  | 27      |
| 3   | 5<br>2  | 25      |



# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
