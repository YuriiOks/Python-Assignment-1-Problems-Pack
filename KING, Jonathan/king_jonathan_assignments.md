# Assignment for KING, Jonathan

## Task 1

**Problem:** An integer `n` is entered, it is necessary to "cut off" the last `k` digits from it. For example, when `n` = 123456 and `k` = 3 the answer should be 123.

| No. | Inputs     | Outputs |
| --- | ---------- | ------- |
| 1   | 456712<br>2 | 4567 |
| 2   | 123456<br>3 | 123  |
| 3   | 123456<br>6 | 0    |

## Task 2
**Problem:** Write a program that determines the behavior of a spacecraft launching at the equator, depending on its initial speed `v`, given in km/s (real numbers). There are four possible cases: 
- if `v < 7.8` km/s, the device will fall to the Earth's surface; 
- if `7.8 ≤ v < 11.2` km/s, the device will become a satellite of the Earth; 
- if `11.2 ≤ v < 16.4` km/s, the device will become a satellite of the Sun; 
- if `v ≥ 16.4` km/s, the spacecraft will leave the Solar System.

| No. | Inputs | Outputs                               |
| --- | ------ | ------------------------------------- |
| 1   | 12.5   | The device will become a satellite of the Sun. |
| 2   | 8.3    | The device will become a satellite of the Earth. |
| 3   | 0      | The device will fall to the Earth's surface. |
| 4   | 20     | The device will leave the Solar System. |



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

**Problem:** Write a program to calculate the sum of all integers from `1` to `n` inclusive.

### Input:
- An integer representing the upper limit of the range.

### Output:
- An integer representing the sum of all integers from `1` to `n` inclusive.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 100    | 5050 |
| 2   | 16     | 136 |
| 3   | 1      | 1 |

### Note:
The problem tests the ability to solve a quadratic equation and handle different cases of discriminant values.



## Task 5

**Problem:** Write a program to print all odd numbers from `1` to `b`, where `b` is an integer entered by the user. You cannot use the branching construct.

### Input:

- An integer representing the upper limit of the range.

### Output:

- A sequence of odd numbers from `1` to `b` inclusive.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 15 | 1 3 5 7 9 11 13 15 |
| 2 | 8 | 1 3 5 7 |
| 3 | 5 | 1 3 5 |

### Note:

The problem tests the ability to use loops and conditional statements to print a sequence of numbers.




# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
