# TOPIC 2: REGRESSION EQUATIONS
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## 1. Definition

Regression analysis is a **mathematical measure of the average relationship between two or more variables**. It is used to predict the value of one variable from the known value of another.

### Two Types of Variables:
- **Dependent variable (Y):** The variable whose value is to be predicted
- **Independent variable (X):** The variable whose value is used for prediction

---

## 2. Two Lines of Regression

For two variables X and Y, there are always **two** regression lines:

1. **Line of regression of Y on X** — gives the best estimate of Y for any given X
2. **Line of regression of X on Y** — gives the best estimate of X for any given Y

> The two lines intersect at the point (x̄, ȳ) — the means of X and Y.

---

## 3. Regression Equations (Formulas)

### Line of Regression of Y on X:
```
Y - ȳ = byx (X - x̄)
```
Or in the form Y = a + bX where:
```
byx = Σ(dx · dy) / Σdx²     (regression coefficient of Y on X)
a = ȳ - byx · x̄
```

### Line of Regression of X on Y:
```
X - x̄ = bxy (Y - ȳ)
```
Or in the form X = c + dY where:
```
bxy = Σ(dx · dy) / Σdy²     (regression coefficient of X on Y)
c = x̄ - bxy · ȳ
```

Where: dx = X - x̄,  dy = Y - ȳ

---

## 4. Relationship Between r and Regression Coefficients

```
r = √(byx × bxy)
```

**Important rules:**
- If both byx and bxy are **negative**, then r is **negative**
- If both are **positive**, then r is **positive**
- byx and bxy always have the **same sign**
- r² = byx × bxy (coefficient of determination)

---

## 5. Forecasting Using Regression

- To predict **Y** for a given X → use the **Y on X** regression line
- To predict **X** for a given Y → use the **X on Y** regression line

---

## 6. Worked Example 1 — Marks in Economics and Statistics

**Problem:** From the data below find:
(a) The two regression equations
(b) The coefficient of correlation
(c) The most likely marks in Statistics when marks in Economics = 30

| X (Economics) | 25 | 28 | 35 | 32 | 31 | 36 | 29 | 38 | 34 | 32 |
|---|---|---|---|---|---|---|---|---|---|---|
| Y (Statistics) | 43 | 46 | 49 | 41 | 36 | 32 | 31 | 30 | 33 | 39 |

**Solution:**

x̄ = 320/10 = **32**,  ȳ = 380/10 = **38**

Let dx = X - 32,  dy = Y - 38

| X  | Y  | dx | dy | dx²  | dy²  | dx·dy |
|----|----|----|----|------|------|-------|
| 25 | 43 | -7 | 5  | 49   | 25   | -35   |
| 28 | 46 | -4 | 8  | 16   | 64   | -32   |
| 35 | 49 | 3  | 11 | 9    | 121  | 33    |
| 32 | 41 | 0  | 3  | 0    | 9    | 0     |
| 31 | 36 | -1 | -2 | 1    | 4    | 2     |
| 36 | 32 | 4  | -6 | 16   | 36   | -24   |
| 29 | 31 | -3 | -7 | 9    | 49   | 21    |
| 38 | 30 | 6  | -8 | 36   | 64   | -48   |
| 34 | 33 | 2  | -5 | 4    | 25   | -10   |
| 32 | 39 | 0  | 1  | 0    | 1    | 0     |
| **Σ** | | **0** | **0** | **140** | **398** | **-93** |

**(a) Regression Coefficients:**
```
byx = Σ(dx·dy) / Σdx² = -93/140 = -0.664

bxy = Σ(dx·dy) / Σdy² = -93/398 = -0.234
```

**Regression of Y on X:**
```
Y - 38 = -0.664(X - 32)
Y - 38 = -0.664X + 21.25
Y = -0.664X + 59.25
```

**Regression of X on Y:**
```
X - 32 = -0.234(Y - 38)
X - 32 = -0.234Y + 8.89
X = -0.234Y + 40.89
```

**(b) Correlation Coefficient:**
```
r = √(byx × bxy) = √((-0.664) × (-0.234)) = √0.1554 = 0.394
```
Since both regression coefficients are negative, **r = -0.394**

**(c) Forecast for X = 30:**
```
Y = -0.664(30) + 59.25
Y = -19.92 + 59.25
Y = 39.33 marks
```

---

## 7. Worked Example 2 — Rainfall and Crop Yield

**Problem:** Yield y (tons/acre) and rainfall x (cm) for 7 years:

| X | 12 | 14 | 15 | 11 | 13 | 14 | 12 |
|---|---|---|---|---|---|---|---|
| Y | 6  | 8  | 8  | 5  | 7  | 9  | 6  |

Find: (a) Regression of Y on X and X on Y  
(b) Estimate yield when rainfall = 14 cm  
(c) Estimate rainfall when yield = 8 tons/acre

**Solution:**

n = 7

| X  | Y  | X²  | Y²  | XY  |
|----|----|-----|-----|-----|
| 12 | 6  | 144 | 36  | 72  |
| 14 | 8  | 196 | 64  | 112 |
| 15 | 8  | 225 | 64  | 120 |
| 11 | 5  | 121 | 25  | 55  |
| 13 | 7  | 169 | 49  | 91  |
| 14 | 9  | 196 | 81  | 126 |
| 12 | 6  | 144 | 36  | 72  |
| **Σ** | | **ΣX=91** | **ΣY=49** | **ΣX²=1195** | **ΣY²=355** | **ΣXY=648** |

x̄ = 91/7 = 13,  ȳ = 49/7 = 7

```
Σdx² = ΣX² - n·x̄² = 1195 - 7×169 = 1195 - 1183 = 12
Σdy² = ΣY² - n·ȳ² = 355 - 7×49 = 355 - 343 = 12
Σdx·dy = ΣXY - n·x̄·ȳ = 648 - 7×13×7 = 648 - 637 = 11
```

**Regression Coefficients:**
```
byx = 11/12 = 0.917
bxy = 11/12 = 0.917
```

**(a) Regression of Y on X:**
```
Y - 7 = 0.917(X - 13)
Y = 0.917X - 11.92 + 7
Y = 0.917X - 4.92
```

**Regression of X on Y:**
```
X - 13 = 0.917(Y - 7)
X = 0.917Y - 6.42 + 13
X = 0.917Y + 6.58
```

**(b) Yield when X = 14 cm:**
```
Y = 0.917(14) - 4.92 = 12.84 - 4.92 = 7.92 ≈ 7.9 tons/acre
```

**(c) Rainfall when Y = 8 tons/acre:**
```
X = 0.917(8) + 6.58 = 7.34 + 6.58 = 13.92 ≈ 13.9 cm
```

---

## 8. Practice Questions

**Q1 (Homework).** Obtain the two regression equations and correlation coefficient:

| X | 43 | 44 | 46 | 40 | 44 | 42 | 45 | 42 | 38 | 40 | 42 | 57 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Y | 29 | 31 | 19 | 18 | 19 | 27 | 27 | 29 | 41 | 30 | 26 | 10 |

**Q2.** The following data shows income (X, Ksh '000) and savings (Y, Ksh '000):

| X | 15 | 16 | 17 | 18 | 19 | 20 | 21 |
|---|---|---|---|---|---|---|---|
| Y | 2  | 3  | 3  | 4  | 4  | 5  | 6  |

(a) Find the regression equation of Y on X  
(b) Estimate savings when income = Ksh 22,000  
(c) Find the correlation coefficient

**Q3.** Explain why there are two regression lines and under what condition they coincide.

> **Answer to Q3:** The two lines coincide only when r = ±1 (perfect correlation). When r = 0, the lines are perpendicular to each other.

---

## 9. Key Points to Remember

1. Always compute x̄ and ȳ first
2. byx and bxy must have the **same sign**
3. Use Y on X line to predict Y; use X on Y line to predict X — never mix them
4. r = √(byx × bxy); sign of r = sign of regression coefficients
5. The two regression lines always pass through (x̄, ȳ)
6. If r = ±1, both lines are identical
7. If r = 0, the lines are at right angles (perpendicular)
