<h6>arithmetic.zetamac.com</h6>

1. Read and evaluate the arithmetic question from left to right.

addition, record: 21 in 120s
```
Carry-over addition table.
```
| x | y | sum | quick math |
|:---:|:---:|:---:|:---|
| 5 | 5 | 10 | x2 |
| 5 | 6 | 11 | x2+1 |
| 5 | 7 | 12 | x2+2 |
| 5 | 8 | 13 | x2+3 |
| 5 | 9 | 14 | 5-1+carry |
| 6 | 6 | 12 | x2 |
| 6 | 7 | 13 | x2+1 |
| 6 | 8 | 14 | x2+2 |
| 6 | 9 | 15 | 6-1+carry |
| 7 | 7 | 14 | x2 |
| 7 | 8 | 15 | x2+1 |
| 7 | 9 | 16 | 7-1+carry |
| 8 | 8 | 16 | x2 |
| 8 | 9 | 17 | 8-1+carry |
| 9 | 9 | 18 | x2 |

1. Subtraction can be simplified through rounding-up and adding what was taken using complements.

subtraction, record: 21 in 120s
```
Borrowing subtraction table.
```
| x | y | diff | quick math |
|:---:|:---:|:---:|:---|
| 9 | 9 | 0 | zero |
| `8 | 9 | 9 | gap 1, then 9 |
| `7 | 8 | 9 | gap 1, then 9 |
| `6 | 7 | 9 | gap 1, then 9 |
| `5 | 6 | 9 | gap 1, then 9 |
| `4 | 5 | 9 | gap 1, then 9 |
| `3 | 4 | 9 | gap 1, then 9 |
| `2 | 3 | 9 | gap 1, then 9 |
| `1 | 2 | 9 | gap 1, then 9 |
| `7 | 9 | 9 | gap 2, then 8 |
| `6 | 8 | 9 | gap 2, then 8 |
| `5 | 7 | 9 | gap 2, then 8 |
| `4 | 6 | 8 | gap 2, then 8 |
| `3 | 5 | 8 | gap 2, then 8 |
| `2 | 4 | 8 | gap 2, then 8 |
| `1 | 3 | 8 | gap 2, then 8 |
| `6 | 9 | 7 | gap 3, then 7 |
| `5 | 8 | 7 | gap 3, then 7 |
| `4 | 7 | 7 | gap 3, then 7 |
| `3 | 6 | 7 | gap 3, then 7 |
| `2 | 5 | 7 | gap 3, then 7 |
| `1 | 4 | 7 | gap 3, then 7 |
| `5 | 9 | 6 | gap 4, then 6 |
| `4 | 8 | 6 | gap 4, then 6 |
| `3 | 7 | 6 | gap 4, then 6 |
| `2 | 6 | 6 | gap 4, then 6 |
| `1 | 5 | 6 | gap 4, then 6 |
| `4 | 9 | 5 | gap 5, then 5 |
| `3 | 8 | 5 | gap 5, then 5 |
| `2 | 7 | 5 | gap 5, then 5 |
| `1 | 6 | 5 | gap 5, then 5 |
| `3 | 9 | 4 | gap 6, then 4 |
| `2 | 8 | 4 | gap 6, then 4 |
| `1 | 7 | 4 | gap 6, then 4 |
| `2 | 9 | 3 | gap 7, then 3 |
| `1 | 8 | 3 | gap 7, then 3 |
| `1 | 9 | 2 | gap 8, then 2 |

multiplication, record: 13 in 120

| x | y | prod | quick math |
|:---:|:---:|:---:|:---|
| ... | ... | ... | ... |

```
Case: xy * xy
x^2 append y^2 + x*y*2*10

Case: x5 * x5
x*(x+1) append 25

Case: xy * xz, where y + z = 10
x*(x+1) append y*z
```

division, record: 14 in 120

| x | y | prod | quick math |
|:---:|:---:|:---:|:---|
| ... | ... | ... | ... |

<h6>Targeted Practice Mode</h6>

80 in 8: 51 in 8 minutes.
Total attempts: 23

Integer Questions: 18 in 2 minutes.
Total attempts: 36

Decimal Questions: 18 in 2 minutes.
Total attempts: 200

```
Case: x_1.x_2 / y_1.y_2 = x_1 x_2 / y_1 y_2

Case: x * 0.0y = x * y / 100

Case: x / 0.0y = x * 100 / y

Case: x.5 * x.5
x*(x+1) append 25 / 100
```

Fraction Questions: 16 in 2 minutes.
Total attempts: 210

```
Case (Question format): Unsimplified fractions specific to the multiple choice question format
Scan the choices to accomodate unsimplified fractions in the question format

Case (Question format): x/y /? = i/j
? = (x/i) / (y/j)

Case: Integer - Improper fraction = x - y/z
Usually, convert y/z to a mixed fraction by finding the largest multiple of z that is still smaller than y, and then perform the subtraction
A quicker way is to find the smallest multiple of z that is still larger than y, which is easier to subtract from the integer and then the subtraction

Case: small Fraction - ? = small Fraction
Since the numbers are small, looking for the LCD is still faster than cross-multiplication
```
