# Assignment for Quartey Richard

## Task 1

**Problem:** An integer `n` is entered, it is necessary to "cut off" the last `k` digits from it. For example, when `n` = 123456 and `k` = 3 the answer should be 123.

| No. | Inputs     | Outputs |
| --- | ---------- | ------- |
| 1   | 456712<br>2 | 4567 |
| 2   | 123456<br>3 | 123  |
| 3   | 123456<br>6 | 0    |

## Task 2
**Problem:** Given a two-digit number. Determine which of its digits is larger: 
- the first (output `1`) 
- or the second (output `2`), 
- or the digits are equal (output `=`).
- If the number is less than `10` or greater than `99`, output `0`.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 23     | 2       |
| 2   | 37     | 2       |
| 3   | 22     | =       |
| 4   | 10     | 1       |
| 5   | -1    | 0       |



## Task 3
**Problem:** Given a natural number `n` (`n ≤ 9999`). Determine whether `all four digits` of this number are `different` (considering four digits). For example, in the number `5623`, all digits are different, in the number `0012` - no.

### Input:
- An `integer` representing the four-digit number.

### Output:
- A `boolean` indicating whether all digits in the number are different.

### Examples:

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 1234 | True |
| 2   | 1981 | False |

### Note:
The problem tests the ability to `work with digits` of a number and `compare` their uniqueness.



## Task 4

**Problem:** Given a natural number `n`. Determine the number of digits in it.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 12367832 | 8       |
| 2   | 142      | 3       |
| 3   | 0        | 1       |


## Task 5

**Problem:** Given a sequence of natural numbers, ending with the number `0`. Determine the value of the largest element in the sequence.

| No. | Inputs | Outputs |
| --- | ------ | ------- |
| 1   | 5<br>3<br>8<br>0 | 8 |
| 2   | 1<br>2<br>3<br>4<br>5<br>0 | 5 |
| 3   | 17<br>12<br>3<br>0 | 17 |



# Running Your Code and Tests Locally 🖥️

To run your code and tests locally, you can use the following commands:

1. Run the code:
```bash
python Task_1.py
```
