# Assignment for WOJNA, Kacper

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
**Problem:** Depending on the size of the amount, the tax from it is calculated according to the following scheme: 
- if the amount does not exceed a certain value `a`, then the tax is not calculated; 
- if the amount is greater than `a` but does not exceed `b`, then the tax is `10%`; 
- if the amount is greater than `b` but does not exceed `c`, then the tax is `25%`; 
- if the amount is greater than `c`, then the tax is `50%`. 

Determine what tax (real number) will be calculated from the amount of size `s`. The data (integers) are entered in the following order: `a`, `b`, `c`, `s`.

| No. | Inputs | Outputs                        |
| --- | ------ | ------------------------------ |
| 1   | 1000<br>10000<br>100000<br>15000 | 1500.0 |
| 2   | 1000<br>10000<br>100000<br>5000  | 500.0  |
| 3   | 1000<br>10000<br>100000<br>500000 | 250000.0 |




## Task 3

**Problem:** Write a program in which a three-digit integer and a digit are entered. It is necessary to determine whether the entered digit is in the number.

### Input:
- An integer representing the three-digit number.
- An integer representing the digit.

### Output:
- A boolean indicating whether the digit is in the number.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 125 2 | True |
| 2   | 543 1 | False |
| 3   | 123 3 | True |

### Note:
The problem tests the ability to work with digits of a number.



## Task 4

**Problem:** Write a program that prints integers from `1` to `n` (1 < `n` ≤ 1000) with the following condition: for numbers divisible by 3, it prints `*3*` instead of the number, for numbers divisible by 5, it prints `*5*`, and for numbers divisible by 3 and 5 simultaneously, the message will be `*35*`.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 15     | 1<br>2<br>\*3\*<br>4<br>\*5\*<br>\*3\*<br>7<br>8<br>\*3\*<br>\*5\*<br>11<br>\*3\*<br>13<br>14<br>\*35\* |
| 2   | 20     | 1<br>2<br>\*3\*<br>4<br>\*5\*<br>\*3\*<br>7<br>8<br>\*3\*<br>\*5\*<br>11<br>\*3\*<br>13<br>14<br>\*35\*<br>16<br>17<br>\*3\*<br>19<br>\*5\* |
| 3   | 10     | 1<br>2<br>\*3\*<br>4<br>\*5\*<br>\*3\*<br>7<br>8<br>\*3\*<br>\*5\* |


## Task 5

**Problem:** Write a program to calculate the sum of the factorials of all integers from `1` to `n` inclusive.

### Input:

- An integer representing the upper limit of the range.

### Output:

- An integer representing the sum of the factorials of all integers from `1` to `n` inclusive.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 3 | 9 |
| 2 | 4 | 33 |
| 3 | 5 | 153 |

### Note:

The problem tests the ability to use loops and conditional statements to calculate the sum of a series.




# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
