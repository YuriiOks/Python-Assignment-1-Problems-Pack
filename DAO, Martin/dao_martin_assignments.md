# Assignment for DAO, Martin

## Task 1

**Problem:** Get the reverse (in reverse order) entry of the three-digit number `n` entered by the user.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 184 | 481 |
| 2   | 123 | 321 |
| 3   | 567 | 765 |


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

**Problem:** Write a program to print a pattern of `*` characters as shown in the output for a given value of `n`.

### Input:
- An integer representing the number of rows in the pattern.

### Output:
- A pattern of `*` characters as shown in the examples.


### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 5      | *<br>\*\*<br>\*\*\*<br>\*\*\*\*<br>\*\*\*\*\* |
| 2   | 3      | *<br>\*\*<br>\*\*\* |
| 3   | 7      | *<br>\*\*<br>\*\*\*<br>\*\*\*\*<br>\*\*\*\*\*<br>\*\*\*\*\*\*<br>\*\*\*\*\*\*\* |

### Note:

The problem tests the ability to use loops and conditional statements to print a pattern of characters.




## Task 5

**Problem:** Determine the sum of all elements of the sequence that ends with the number `0`. A sequence of integers that ends with the number `0` is entered (the number `0` itself is not included in the sequence, but is used as a sign of its end).

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 2<br>5<br>3<br>0 | 10 |
| 2   | 1<br>2<br>3<br>4<br>5<br>0 | 15 |
| 3   | 0 | 0 |



# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
