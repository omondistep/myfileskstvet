# BSC7124 APPLY MATHS FOR ECONOMICS
## SAMPLE QUESTIONS AND SOLUTIONS

---

## SECTION A: DATA ORGANIZATION AND PRESENTATION

### Question 1
The following marks were scored by 20 students in a test:
45, 62, 38, 71, 55, 49, 63, 57, 44, 68, 52, 39, 61, 47, 73, 58, 42, 66, 53, 60

(a) Using Sturges Rule, determine the number of classes and class width.
(b) Construct a frequency distribution table using exclusive classes.
(c) Draw a histogram and frequency polygon.
(d) Construct a cumulative frequency table and estimate the median from the ogive.

### Solution 1

**(a) Sturges Rule:**
```
N = 20
k = 1 + 3.322 log(20) = 1 + 3.322 × 1.301 = 1 + 4.32 = 5.32 ≈ 5 classes

Range = 73 - 38 = 35
Class width h = 35 / 5 = 7  (round up to 10 for convenience)
```

**(b) Frequency Distribution Table:**

| Class | Tally | Frequency | Midpoint |
|-------|-------|-----------|----------|
| 35-45 | IIII  | 4         | 40       |
| 45-55 | IIII I| 5         | 50       |
| 55-65 | IIII II| 7        | 60       |
| 65-75 | IIII  | 4         | 70       |
| **Total** | | **20**  |          |

**(d) Cumulative Frequency Table:**

| Class | Freq | Less Than CF | More Than CF |
|-------|------|-------------|--------------|
| 35-45 | 4    | 4           | 20           |
| 45-55 | 5    | 9           | 16           |
| 55-65 | 7    | 16          | 11           |
| 65-75 | 4    | 20          | 4            |

**Median from ogive:** At CF = n/2 = 10, read off x-axis ≈ **55**

---

## SECTION B: MEASURES OF CENTRAL TENDENCY AND DISPERSION

### Question 2
The ages of 10 employees in a company are:
23, 27, 31, 25, 29, 35, 28, 33, 26, 30

Calculate: (a) Mean  (b) Median  (c) Mode  (d) Standard Deviation  (e) Coefficient of Variation

### Solution 2

**(a) Mean:**
```
Σx = 23+27+31+25+29+35+28+33+26+30 = 287
x̄ = 287 / 10 = 28.7 years
```

**(b) Median:**
Arranged: 23, 25, 26, 27, 28, 29, 30, 31, 33, 35
```
n = 10 (even)
Median = (5th + 6th) / 2 = (28 + 29) / 2 = 28.5 years
```

**(c) Mode:**
No value repeats → **No mode** (or the distribution is amodal)

**(d) Standard Deviation:**

| x  | x - x̄ | (x - x̄)² |
|----|--------|----------|
| 23 | -5.7   | 32.49    |
| 25 | -3.7   | 13.69    |
| 26 | -2.7   | 7.29     |
| 27 | -1.7   | 2.89     |
| 28 | -0.7   | 0.49     |
| 29 | 0.3    | 0.09     |
| 30 | 1.3    | 1.69     |
| 31 | 2.3    | 5.29     |
| 33 | 4.3    | 18.49    |
| 35 | 6.3    | 39.69    |
| **Σ** | **0** | **122.10** |

```
σ = √(122.10 / 10) = √12.21 = 3.49 years
```

**(e) Coefficient of Variation:**
```
CV = (σ / x̄) × 100 = (3.49 / 28.7) × 100 = 12.16%
```

---

### Question 3 (Grouped Data)
The following table shows the wages of 50 workers:

| Wages (Ksh '000) | 10-20 | 20-30 | 30-40 | 40-50 | 50-60 |
|------------------|-------|-------|-------|-------|-------|
| No. of Workers   | 8     | 14    | 16    | 8     | 4     |

Calculate: (a) Mean  (b) Median  (c) Mode  (d) Standard Deviation

### Solution 3

Let A = 35 (assumed mean), h = 10

| Class | f  | x  | d=(x-35)/10 | fd  | fd²  | cf |
|-------|----|----|-------------|-----|------|----|
| 10-20 | 8  | 15 | -2          | -16 | 32   | 8  |
| 20-30 | 14 | 25 | -1          | -14 | 14   | 22 |
| 30-40 | 16 | 35 | 0           | 0   | 0    | 38 |
| 40-50 | 8  | 45 | 1           | 8   | 8    | 46 |
| 50-60 | 4  | 55 | 2           | 8   | 16   | 50 |
| **Σ** | **50** | | | **-14** | **70** | |

**(a) Mean:**
```
x̄ = A + (Σfd/Σf) × h = 35 + (-14/50) × 10 = 35 - 2.8 = 32.2 (Ksh '000)
```

**(b) Median:**
```
n/2 = 25 → median class is 30-40 (cf before = 22)
Median = 30 + [(25 - 22)/16] × 10 = 30 + 1.875 = 31.875 (Ksh '000)
```

**(c) Mode:**
```
Modal class = 30-40 (highest frequency f₁=16, f₀=14, f₂=8)
Mode = 30 + [(16-14)/(2×16-14-8)] × 10 = 30 + [2/10] × 10 = 32 (Ksh '000)
```

**(d) Standard Deviation:**
```
σ = h × √[(Σfd²/Σf) - (Σfd/Σf)²]
  = 10 × √[(70/50) - (-14/50)²]
  = 10 × √[1.4 - 0.0784]
  = 10 × √1.3216
  = 10 × 1.1496
  = 11.50 (Ksh '000)
```

---

---

## SECTION C: CORRELATION AND REGRESSION

### Question 4
The following data shows the advertising expenditure (X) and sales (Y) of a company over 6 years:

| X (Ksh '000) | 10 | 12 | 14 | 16 | 18 | 20 |
|---|---|---|---|---|---|---|
| Y (Ksh '000) | 40 | 45 | 50 | 55 | 60 | 65 |

(a) Calculate Karl Pearson's coefficient of correlation.
(b) Find the two regression equations.
(c) Estimate sales when advertising expenditure is Ksh 22,000.

### Solution 4

x̄ = 90/6 = 15,  ȳ = 315/6 = 52.5

| X  | Y  | dx=X-15 | dy=Y-52.5 | dx²  | dy²   | dx·dy |
|----|----|---------|-----------|------|-------|-------|
| 10 | 40 | -5      | -12.5     | 25   | 156.25| 62.5  |
| 12 | 45 | -3      | -7.5      | 9    | 56.25 | 22.5  |
| 14 | 50 | -1      | -2.5      | 1    | 6.25  | 2.5   |
| 16 | 55 | 1       | 2.5       | 1    | 6.25  | 2.5   |
| 18 | 60 | 3       | 7.5       | 9    | 56.25 | 22.5  |
| 20 | 65 | 5       | 12.5      | 25   | 156.25| 62.5  |
| **Σ** | | **0** | **0**  | **70**| **437.5**|**175**|

**(a) Pearson's r:**
```
r = Σ(dx·dy) / √(Σdx² × Σdy²)
  = 175 / √(70 × 437.5)
  = 175 / √30625
  = 175 / 175
  = 1.0
```
**Perfect positive correlation** — advertising and sales move together exactly.

**(b) Regression Equations:**
```
byx = Σ(dx·dy) / Σdx² = 175/70 = 2.5
Y on X:  Y - 52.5 = 2.5(X - 15)  →  Y = 2.5X + 15

bxy = Σ(dx·dy) / Σdy² = 175/437.5 = 0.4
X on Y:  X - 15 = 0.4(Y - 52.5)  →  X = 0.4Y - 6
```

**(c) Forecast for X = 22:**
```
Y = 2.5(22) + 15 = 55 + 15 = Ksh 70,000
```

---

### Question 5
Ten students were ranked by two examiners as follows:

| Student    | A | B | C | D | E | F | G | H | I | J |
|------------|---|---|---|---|---|---|---|---|---|---|
| Examiner 1 | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10|
| Examiner 2 | 3 | 5 | 2 | 1 | 6 | 4 | 9 | 7 | 8 | 10|

Calculate Spearman's rank correlation coefficient and comment.

### Solution 5

| Student | R1 | R2 | d=R1-R2 | d²  |
|---------|----|----|---------|-----|
| A       | 1  | 3  | -2      | 4   |
| B       | 2  | 5  | -3      | 9   |
| C       | 3  | 2  | 1       | 1   |
| D       | 4  | 1  | 3       | 9   |
| E       | 5  | 6  | -1      | 1   |
| F       | 6  | 4  | 2       | 4   |
| G       | 7  | 9  | -2      | 4   |
| H       | 8  | 7  | 1       | 1   |
| I       | 9  | 8  | 1       | 1   |
| J       | 10 | 10 | 0       | 0   |
| **Σ**   |    |    |         | **34** |

```
ρ = 1 - [6Σd²] / [n(n²-1)]
  = 1 - [6 × 34] / [10(100-1)]
  = 1 - 204/990
  = 1 - 0.206
  = 0.794
```
**High positive correlation** — the two examiners largely agree in their rankings.

---

---

## SECTION D: PROBABILITY

### Question 6
A bag contains 5 red, 4 blue and 3 green balls. Two balls are drawn at random without replacement. Find the probability that:
(a) Both are red
(b) One is red and one is blue
(c) At least one is green
(d) None is blue

### Solution 6

Total balls = 12

**(a) Both red:**
```
P(R₁ and R₂) = P(R₁) × P(R₂|R₁) = (5/12) × (4/11) = 20/132 = 5/33 ≈ 0.1515
```

**(b) One red, one blue:**
```
P(RB or BR) = P(R then B) + P(B then R)
= (5/12)(4/11) + (4/12)(5/11)
= 20/132 + 20/132 = 40/132 = 10/33 ≈ 0.3030
```

**(c) At least one green:**
```
P(at least 1 green) = 1 - P(no green)
P(no green) = (9/12) × (8/11) = 72/132 = 6/11
P(at least 1 green) = 1 - 6/11 = 5/11 ≈ 0.4545
```

**(d) None is blue:**
```
P(no blue) = (8/12) × (7/11) = 56/132 = 14/33 ≈ 0.4242
```

---

### Question 7
In a class, 60% of students passed Maths and 70% passed English. 40% passed both subjects. A student is selected at random. Find the probability that the student:
(a) Passed Maths or English
(b) Passed English but not Maths
(c) Passed neither subject

### Solution 7

P(M) = 0.6,  P(E) = 0.7,  P(M∩E) = 0.4

**(a) Passed Maths or English:**
```
P(M∪E) = P(M) + P(E) - P(M∩E) = 0.6 + 0.7 - 0.4 = 0.9
```

**(b) Passed English but not Maths:**
```
P(E only) = P(E) - P(M∩E) = 0.7 - 0.4 = 0.3
```

**(c) Passed neither:**
```
P(neither) = 1 - P(M∪E) = 1 - 0.9 = 0.1
```

---

## SECTION E: PROBABILITY DISTRIBUTIONS

### Question 8 — Binomial Distribution
A factory produces items of which 5% are defective. A sample of 10 items is selected. Find the probability that:
(a) Exactly 2 are defective
(b) At most 1 is defective
(c) At least 1 is defective

### Solution 8

n = 10, p = 0.05, q = 0.95

**Formula:** P(X=x) = ¹⁰Cₓ (0.05)ˣ (0.95)¹⁰⁻ˣ

**(a) P(X = 2):**
```
P(X=2) = ¹⁰C₂ × (0.05)² × (0.95)⁸
= 45 × 0.0025 × 0.6634
= 45 × 0.001659
= 0.0746
```

**(b) P(X ≤ 1) = P(X=0) + P(X=1):**
```
P(X=0) = (0.95)¹⁰ = 0.5987
P(X=1) = 10 × 0.05 × (0.95)⁹ = 10 × 0.05 × 0.6302 = 0.3151
P(X≤1) = 0.5987 + 0.3151 = 0.9138
```

**(c) P(X ≥ 1):**
```
P(X≥1) = 1 - P(X=0) = 1 - 0.5987 = 0.4013
```

---

### Question 9 — Poisson Distribution
On average, 2 customers arrive at a bank counter per minute. Find the probability that in a given minute:
(a) No customer arrives
(b) Exactly 3 customers arrive
(c) More than 2 customers arrive

### Solution 9

λ = 2, e⁻² = 0.1353

**Formula:** P(X=x) = (e⁻λ × λˣ) / x!

**(a) P(X = 0):**
```
P(X=0) = e⁻² × 2⁰ / 0! = 0.1353 × 1 / 1 = 0.1353
```

**(b) P(X = 3):**
```
P(X=3) = e⁻² × 2³ / 3! = 0.1353 × 8 / 6 = 0.1804
```

**(c) P(X > 2) = 1 - P(X≤2):**
```
P(X=1) = 0.1353 × 2 / 1 = 0.2707
P(X=2) = 0.1353 × 4 / 2 = 0.2707
P(X≤2) = 0.1353 + 0.2707 + 0.2707 = 0.6767
P(X>2) = 1 - 0.6767 = 0.3233
```

---

### Question 10 — Normal Distribution
The heights of 500 students are normally distributed with mean 165 cm and standard deviation 8 cm.

(a) How many students have height between 157 cm and 173 cm?
(b) How many students are taller than 181 cm?
(c) Find the height exceeded by only 10% of students.

### Solution 10

μ = 165, σ = 8

**(a) P(157 < X < 173):**
```
Z₁ = (157-165)/8 = -1.0  →  area = 0.3413
Z₂ = (173-165)/8 = +1.0  →  area = 0.3413
P(157 < X < 173) = 0.3413 + 0.3413 = 0.6826
Number of students = 0.6826 × 500 = 341 students
```

**(b) P(X > 181):**
```
Z = (181-165)/8 = 2.0  →  area from 0 to 2 = 0.4772
P(X > 181) = 0.5 - 0.4772 = 0.0228
Number of students = 0.0228 × 500 = 11 students
```

**(c) Height exceeded by 10%:**
```
P(X > x) = 0.10  →  P(0 < Z < z) = 0.40
From Z-table: z = 1.28
x = μ + zσ = 165 + 1.28 × 8 = 165 + 10.24 = 175.24 cm
```

---

---

## SECTION F: INDEX NUMBERS

### Question 11
Calculate price index numbers for 2025 with 2020 as base using:
(a) Simple Aggregative Method
(b) Laspeyre's Method
(c) Paasche's Method
(d) Fisher's Ideal Method

| Commodity | P₀ (2020) | P₁ (2025) | Q₀ (2020) | Q₁ (2025) |
|-----------|-----------|-----------|-----------|-----------|
| A         | 10        | 15        | 50        | 60        |
| B         | 20        | 25        | 40        | 45        |
| C         | 30        | 40        | 30        | 35        |
| D         | 40        | 50        | 20        | 25        |

### Solution 11

**Calculations:**

| Item | P₀ | P₁ | Q₀ | Q₁ | P₀Q₀ | P₁Q₀ | P₀Q₁ | P₁Q₁ |
|------|----|----|----|----|------|------|------|------|
| A    | 10 | 15 | 50 | 60 | 500  | 750  | 600  | 900  |
| B    | 20 | 25 | 40 | 45 | 800  | 1000 | 900  | 1125 |
| C    | 30 | 40 | 30 | 35 | 900  | 1200 | 1050 | 1400 |
| D    | 40 | 50 | 20 | 25 | 800  | 1000 | 1000 | 1250 |
| **Σ**| **100** | **130** | | | **3000** | **3950** | **3550** | **4675** |

**(a) Simple Aggregative:**
```
P₀₁ = (ΣP₁ / ΣP₀) × 100 = (130/100) × 100 = 130
```
**Prices increased by 30%**

**(b) Laspeyre's Index:**
```
P₀₁ = (ΣP₁Q₀ / ΣP₀Q₀) × 100 = (3950/3000) × 100 = 131.67
```

**(c) Paasche's Index:**
```
P₀₁ = (ΣP₁Q₁ / ΣP₀Q₁) × 100 = (4675/3550) × 100 = 131.69
```

**(d) Fisher's Ideal Index:**
```
P₀₁ = √(Laspeyre's × Paasche's) = √(131.67 × 131.69) = √17337.08 = 131.68
```

**Interpretation:** Prices increased by approximately 31.7% from 2020 to 2025.

---

### Question 12 — Consumer Price Index
The following data relates to the consumption pattern of a worker's family:

| Item Group | Price 2020 | Price 2025 | Quantity 2020 |
|------------|------------|------------|---------------|
| Food       | 200        | 280        | 40            |
| Clothing   | 150        | 180        | 20            |
| Fuel       | 50         | 70         | 30            |
| Rent       | 300        | 360        | 10            |
| Misc.      | 100        | 130        | 25            |

(a) Calculate the CPI for 2025 with 2020 as base.
(b) If the worker earned Ksh 30,000 in 2020 and Ksh 38,000 in 2025, calculate real wages for both years.

### Solution 12

**(a) CPI using Aggregate Expenditure Method:**

| Item | P₀ | P₁ | Q₀ | V=P₀Q₀ | P₁Q₀ |
|------|----|----|----|----|------|
| Food | 200| 280| 40 | 8000 | 11200|
| Clothing | 150| 180| 20 | 3000 | 3600 |
| Fuel | 50 | 70 | 30 | 1500 | 2100 |
| Rent | 300| 360| 10 | 3000 | 3600 |
| Misc.| 100| 130| 25 | 2500 | 3250 |
| **Σ**| | | | **18000** | **23750** |

```
CPI = (ΣP₁Q₀ / ΣP₀Q₀) × 100 = (23750/18000) × 100 = 131.94
```

**(b) Real Wages:**

For 2020 (base year):
```
Real Wage = (30000/100) × 100 = Ksh 30,000
```

For 2025:
```
Real Wage = (38000/131.94) × 100 = Ksh 28,803
```

**Interpretation:** Despite a nominal increase of Ksh 8,000, the worker's purchasing power actually **decreased** by Ksh 1,197 due to inflation.

---

### Question 13 — Quantity Index
Calculate quantity index numbers for the data in Question 11 using:
(a) Laspeyre's Quantity Index
(b) Paasche's Quantity Index

### Solution 13

Using data from Question 11:

**(a) Laspeyre's Quantity Index (base year prices as weights):**
```
Q₀₁ = (ΣQ₁P₀ / ΣQ₀P₀) × 100 = (3550/3000) × 100 = 118.33
```

**(b) Paasche's Quantity Index (current year prices as weights):**
```
Q₀₁ = (ΣQ₁P₁ / ΣQ₀P₁) × 100 = (4675/3950) × 100 = 118.35
```

**Interpretation:** Quantity produced/consumed increased by approximately 18.3% from 2020 to 2025.

---

## SECTION G: MIXED PROBLEMS

### Question 14 — Comprehensive Problem
A company recorded the following sales (Y, in Ksh millions) and advertising expenditure (X, in Ksh '000) over 5 years:

| Year | X  | Y  |
|------|----|----|
| 2020 | 10 | 25 |
| 2021 | 15 | 30 |
| 2022 | 20 | 35 |
| 2023 | 25 | 40 |
| 2024 | 30 | 45 |

(a) Calculate the coefficient of correlation.
(b) Obtain the regression equation of Y on X.
(c) Estimate sales if advertising expenditure is Ksh 35,000.
(d) Calculate the coefficient of determination and interpret.

### Solution 14

x̄ = 100/5 = 20,  ȳ = 175/5 = 35

| X  | Y  | dx | dy | dx² | dy² | dx·dy |
|----|----|----|----|----|-----|-------|
| 10 | 25 | -10| -10| 100| 100 | 100   |
| 15 | 30 | -5 | -5 | 25 | 25  | 25    |
| 20 | 35 | 0  | 0  | 0  | 0   | 0     |
| 25 | 40 | 5  | 5  | 25 | 25  | 25    |
| 30 | 45 | 10 | 10 | 100| 100 | 100   |
| **Σ**| | **0**| **0**| **250**| **250**| **250** |

**(a) Correlation coefficient:**
```
r = 250 / √(250 × 250) = 250/250 = 1.0
```
**Perfect positive correlation**

**(b) Regression equation Y on X:**
```
byx = 250/250 = 1.0
Y - 35 = 1.0(X - 20)
Y = X + 15
```

**(c) Forecast for X = 35:**
```
Y = 35 + 15 = Ksh 50 million
```

**(d) Coefficient of determination:**
```
r² = (1.0)² = 1.0 = 100%
```
**Interpretation:** 100% of the variation in sales is explained by advertising expenditure. This indicates a perfect linear relationship.

---

### Question 15 — Application Problem
A quality control inspector found that in a batch of 1000 items, the number of defects per item follows a Poisson distribution with mean 0.5. 

(a) Find the probability that a randomly selected item has no defects.
(b) How many items in the batch are expected to have exactly 1 defect?
(c) What is the probability that an item has more than 2 defects?

### Solution 15

λ = 0.5, e⁻⁰·⁵ = 0.6065

**(a) P(X = 0):**
```
P(X=0) = e⁻⁰·⁵ × 0.5⁰ / 0! = 0.6065
```

**(b) Expected items with exactly 1 defect:**
```
P(X=1) = e⁻⁰·⁵ × 0.5¹ / 1! = 0.6065 × 0.5 = 0.3033
Expected number = 0.3033 × 1000 = 303 items
```

**(c) P(X > 2) = 1 - P(X ≤ 2):**
```
P(X=0) = 0.6065
P(X=1) = 0.3033
P(X=2) = 0.6065 × 0.25 / 2 = 0.0758
P(X≤2) = 0.6065 + 0.3033 + 0.0758 = 0.9856
P(X>2) = 1 - 0.9856 = 0.0144
```

---

*End of Sample Questions and Solutions*
