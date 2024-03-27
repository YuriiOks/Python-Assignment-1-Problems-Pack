# Assignment for LEGISTER, Tia

## Task 1

**Problem:** A positive three-digit integer is entered. Find the sum of the digits of the number.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 153    | 9       |
| 2   | 123    | 6       |
| 3   | 565    | 16      |

## Task 2
**Problem:** A software manufacturer in the field of information security sells one set of programs for £2700. If multiple units of goods are purchased, a discount system works: 
- `10-19` units of goods - `10%`, 
- `20-49` - `20%`, 
- `50-99` - `30%`, 
- `100` or more - `40%`. 

Write a program that receives from the user an integer - the number of purchased software sets and outputs a message about the amount of the discount (if any) and the total amount of the purchase with the discount.

| No. | Inputs | Outputs                                                   |
| --- | ------ | --------------------------------------------------------- |
| 1   | 26     | The amount of discount is 20%, total amount of the purchase after the discount is £56160.00 |
| 2 | 3 | The amount of discount is 0%, total amount of the purchase after the discount is £8100.00 |
| 3 | 110 | The amount of discount is 40%, total amount of the purchase after the discount is £178200.00 |




## Task 3
**Problem:** Write a program where the user enters the value of the current date: day, month, and year (whole numbers), and the program outputs the `next day's date` in the format: `dd.mm.yyyy`.

### Input:
- Three `integers` representing the day, month, and year.

### Output:
- A `string` representing the next day's date in the format `dd.mm.yyyy`.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 28<br>2<br>2024 | 29.2.2024 |
| 2   | 31<br>12<br>2020 | 1.1.2021 |
| 3   | 1<br>1<br>2020 | 2.1.2020 |

### Note:
The problem tests the ability to work with dates and calendar calculations.



## Task 4

**Problem:** Given an integer `n` (1 ≤ `n` ≤ 9). Print a triangle of numbers from `1` to `n` as shown in the example.

| No. | Inputs | Outputs             |
| --- | ------ | ------------------- |
| 1   | 9      | 1<br>22<br>333<br>4444<br>55555<br>666666<br>7777777<br>88888888<br>999999999 |
| 2   | 5      | 1<br>22<br>333<br>4444<br>55555 |
| 3   | 1      | 1 |


## Task 5

**Problem:** Write a program to calculate the average of all integers in a sequence that ends with the number `0`. The number `0` is not included in the sequence, but is used as a sign of its end.

### Input:

- A sequence of integers that ends with the number `0`.

### Output:

- A floating-point number representing the average of all integers in the sequence.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 3<br>4<br>5<br>0 | 4.0 |
| 2 | 1<br>2<br>3<br>4<br>5<br>0 | 3.0 |
| 3 | 10<br>20<br>30<br>40<br>50<br>0 | 30.0 |

### Note:

The problem tests the ability to use loops and conditional statements to calculate the average of a sequence of numbers.




# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
