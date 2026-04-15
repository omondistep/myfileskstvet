# BSC7124 APPLY MATHS FOR ECONOMICS
## COMPREHENSIVE REVISION GUIDE

**Unit Code:** ECO/CU/BUS/BC/2/6  
**Duration:** 60 hours  
**Course:** Diploma in Technical Trainer Education

---

## TABLE OF CONTENTS

1. [Elementary Statistics - Data Organization and Presentation](#unit-1)
2. [Descriptive Statistics - Measures of Central Tendency and Dispersion](#unit-2)
3. [Correlation and Regression Analysis](#unit-3)
4. [Basic Probability Theory](#unit-4)
5. [Probability Distributions](#unit-5)
6. [Index Numbers](#unit-6)
7. [Practice Problems and Solutions](#unit-7)
8. [Additional Reference Materials](#unit-8)

---

## COURSE OVERVIEW

### Unit Description
This unit equips learners with competencies to carry out correlation and regression analysis, perform elementary statistics, carry out descriptive statistics, apply set theory, apply basic probability theory, and determine index numbers for work applications.

### Learning Outcomes
1. Carry out Correlation and Regression analysis for work
2. Perform Elementary statistics for work
3. Carry out Descriptive statistics for work
4. Apply Basic probability theory for work
5. Determine Index numbers

---

<a name="unit-1"></a>
## UNIT 1: ELEMENTARY STATISTICS - DATA ORGANIZATION AND PRESENTATION

### 1.1 Types of Data

**Discrete Data:**
- Counted data (e.g., people, cars, animals)
- Cannot accommodate decimals/fractions
- Examples: Number of students, number of defects

**Continuous Data:**
- Measured data (e.g., distance, mass, weight, height, temperature, time, marks, volume)
- Does accommodate decimals/fractions
- Examples: Height in cm, temperature in °C

### 1.2 Types of Classes

**Inclusive Type Classes:**
```
0-9
10-19
20-29
```

**Exclusive Type Classes:**
```
0-10
10-20
20-30
```

### 1.3 Frequency Distribution Tables

**Sturges Rule for Determining Number of Classes:**
```
k = 1 + 3.322 log N
```
Where:
- k = number of classes
- N = total frequency

**Class Width Formula:**
```
h = Range / k
Range = Maximum value - Minimum value
```

### 1.4 Methods of Data Collection
- Primary data collection (surveys, experiments, observations)
- Secondary data collection (published sources, databases)
- Sampling techniques

### 1.5 Sampling Techniques
- Simple random sampling
- Systematic sampling
- Stratified sampling
- Cluster sampling
- Convenience sampling

### 1.6 Data Presentation Methods

**Tables:**
- Frequency distribution tables
- Cumulative frequency tables

**Diagrams:**
- Bar charts
- Pie charts
- Line graphs

**Histograms:**
- Graphical representation of frequency distribution
- Bars touch each other (continuous data)
- Area represents frequency

**Frequency Polygons:**
- Line graph connecting midpoints of histogram bars
- Useful for comparing multiple distributions

**Cumulative Frequency Curves (OGIVE):**

**Less Than Ogive:**
- Plots cumulative frequency against upper class boundaries
- Rising curve from left to right

**More Than Ogive:**
- Plots cumulative frequency against lower class boundaries
- Falling curve from left to right

**Interquartile Range from Ogive:**
- Q1 (First Quartile) = 25th percentile
- Q3 (Third Quartile) = 75th percentile
- IQR = Q3 - Q1

### Key Formulas

**Class Mark (Midpoint):**
```
x = (Lower limit + Upper limit) / 2
```

**Relative Frequency:**
```
Relative frequency = Frequency / Total frequency
```

---

<a name="unit-2"></a>
## UNIT 2: DESCRIPTIVE STATISTICS - MEASURES OF CENTRAL TENDENCY AND DISPERSION

### 2.1 Measures of Central Tendency

**Arithmetic Mean:**

For ungrouped data:
```
x̄ = Σx / n
```

For grouped data:
```
x̄ = Σfx / Σf
```

Using assumed mean method:
```
x̄ = A + (Σfd / Σf)
where d = x - A
```

**Median:**

For ungrouped data (arranged in order):
```
Median = (n+1)/2 th term (if n is odd)
Median = average of (n/2)th and (n/2 + 1)th terms (if n is even)
```

For grouped data:
```
Median = L + [(n/2 - cf) / f] × h
```
Where:
- L = lower boundary of median class
- n = total frequency
- cf = cumulative frequency before median class
- f = frequency of median class
- h = class width

**Mode:**

For ungrouped data: Most frequently occurring value

For grouped data:
```
Mode = L + [(f₁ - f₀) / (2f₁ - f₀ - f₂)] × h
```
Where:
- L = lower boundary of modal class
- f₁ = frequency of modal class
- f₀ = frequency of class before modal class
- f₂ = frequency of class after modal class
- h = class width

### 2.2 Measures of Dispersion

**Range:**
```
Range = Maximum value - Minimum value
```

**Quartile Deviation (Semi-Interquartile Range):**
```
QD = (Q₃ - Q₁) / 2
```

**Mean Deviation:**

From mean:
```
MD = Σ|x - x̄| / n
```

From median:
```
MD = Σ|x - M| / n
```

**Variance:**

For population:
```
σ² = Σ(x - μ)² / N
```

For sample:
```
s² = Σ(x - x̄)² / (n-1)
```

**Standard Deviation:**

For population:
```
σ = √[Σ(x - μ)² / N]
```

For sample:
```
s = √[Σ(x - x̄)² / (n-1)]
```

Alternative formula:
```
σ = √[(Σx² / n) - (x̄)²]
```

**Coefficient of Variation:**
```
CV = (σ / x̄) × 100%
```
- Used to compare variability between different datasets
- Lower CV indicates more consistent data

### 2.3 Measures of Skewness

**Pearson's Coefficient of Skewness:**
```
Sk = (Mean - Mode) / Standard Deviation
```

Or:
```
Sk = 3(Mean - Median) / Standard Deviation
```

**Interpretation:**
- Sk = 0: Symmetric distribution
- Sk > 0: Positively skewed (right-skewed)
- Sk < 0: Negatively skewed (left-skewed)

### 2.4 Measures of Kurtosis

Measures the "peakedness" of a distribution:
- Leptokurtic: More peaked than normal
- Mesokurtic: Normal distribution
- Platykurtic: Flatter than normal

### 2.5 Moments

**rth moment about the mean:**
```
μᵣ = Σ(x - x̄)ʳ / n
```

**First four moments:**
- μ₁ = 0 (always)
- μ₂ = variance
- μ₃ = related to skewness
- μ₄ = related to kurtosis

---

<a name="unit-3"></a>
## UNIT 3: CORRELATION AND REGRESSION ANALYSIS

### 3.1 Correlation

**Definition:**
Correlation is a statistical tool that studies the relationship between two variables. Two variables are correlated if a change in one variable results in a corresponding change in the other variable.

### 3.2 Types of Correlation

**Positive Correlation:**
- Both variables move in the same direction
- Increase in X leads to increase in Y
- Examples: Height and weight, income and expenditure, rainfall and crop yield

**Negative (Inverse) Correlation:**
- Variables move in opposite directions
- Increase in X leads to decrease in Y
- Examples: Price and demand, age and value of car, temperature and woolen garment sales

**Perfect Correlation:**
- r = +1 (perfect positive)
- r = -1 (perfect negative)

**No Correlation:**
- r = 0

### 3.3 Methods of Studying Correlation

1. Scatter Diagram Method
2. Karl Pearson's Coefficient of Correlation
3. Spearman's Rank Correlation

### 3.4 Karl Pearson's Coefficient of Correlation

**Formula:**
```
r = Σ(dx × dy) / √[Σdx² × Σdy²]
```

Where:
- dx = x - x̄
- dy = y - ȳ

**Alternative formula:**
```
r = [nΣxy - (Σx)(Σy)] / √{[nΣx² - (Σx)²][nΣy² - (Σy)²]}
```

**Properties:**
- -1 ≤ r ≤ +1
- r is independent of change of origin and scale
- r is dimensionless

**Interpretation:**
- |r| = 1: Perfect correlation
- 0.8 < |r| < 1: Very high correlation
- 0.6 < |r| < 0.8: High correlation
- 0.4 < |r| < 0.6: Moderate correlation
- 0.2 < |r| < 0.4: Low correlation
- |r| < 0.2: Very low correlation
- r = 0: No correlation

### 3.5 Spearman's Rank Correlation Coefficient

**Formula:**
```
ρ = 1 - [6Σd²] / [n(n² - 1)]
```

Where:
- d = difference between ranks
- n = number of pairs

**When ranks are repeated:**
```
ρ = 1 - [6(Σd² + CF)] / [n(n² - 1)]
```

Correction Factor (CF) for each repeated rank:
```
CF = (m³ - m) / 12
```
Where m = number of times rank is repeated

**Use Cases:**
- When data is qualitative (beauty, intelligence, honesty)
- When exact measurement is difficult
- When data is already in rank form


### 3.6 Regression Analysis

**Definition:** A mathematical measure of the average relationship between two or more variables.

- **Dependent variable:** The variable being predicted (Y)
- **Independent variable:** The variable used for prediction (X)

**Two Regression Lines:**

Line of regression of Y on X:
```
Y = a + bX
byx = Σ(dx·dy) / Σdx²
a = ȳ - byx·x̄
```

Line of regression of X on Y:
```
X = c + dY
bxy = Σ(dx·dy) / Σdy²
c = x̄ - bxy·ȳ
```

**Relationship between r and regression coefficients:**
```
r = √(byx × bxy)
```
- If both regression coefficients are negative, r is negative
- If both are positive, r is positive

**Forecasting:** Use the regression equation of Y on X to predict Y for a given X value.

---

<a name="unit-4"></a>
## UNIT 4: BASIC PROBABILITY THEORY

### 4.1 Key Definitions

- **Probability:** The likelihood or chance of an event occurring. Range: 0 ≤ P(x) ≤ 1
- **Expectation:** Product of probability of success and number of attempts

### 4.2 Types of Events

| Event Type | Definition |
|---|---|
| Independent | Occurrence of one does NOT affect the other (drawing WITH replacement) |
| Dependent | Occurrence of one DOES affect the other (drawing WITHOUT replacement) |
| Mutually Exclusive | Only one can occur at a time |

### 4.3 Laws of Probability

**Addition Law** (for mutually exclusive events — "either...or"):
```
P(A or B) = P(A) + P(B)
```

For non-mutually exclusive events:
```
P(A or B) = P(A) + P(B) - P(A and B)
```

**Multiplication Law** (for "both...and"):

Independent events:
```
P(A and B) = P(A) × P(B)
```

Dependent events:
```
P(A and B) = P(A) × P(B|A)
```

### 4.4 Complementary Events
```
P(A') = 1 - P(A)
P(at least one) = 1 - P(none)
```

---

<a name="unit-4"></a>
## UNIT 4: BASIC PROBABILITY THEORY

### 4.1 Key Definitions

- **Probability:** The likelihood or chance of an event occurring. Range: 0 ≤ P(x) ≤ 1
- **Expectation:** Product of probability of success and number of attempts

### 4.2 Types of Events

| Event Type | Definition |
|---|---|
| Independent | Occurrence of one does NOT affect the other (drawing WITH replacement) |
| Dependent | Occurrence of one DOES affect the other (drawing WITHOUT replacement) |
| Mutually Exclusive | Only one can occur at a time |

### 4.3 Laws of Probability

**Addition Law** (mutually exclusive — "either...or"):
```
P(A or B) = P(A) + P(B)
```
For non-mutually exclusive:
```
P(A or B) = P(A) + P(B) - P(A and B)
```

**Multiplication Law** ("both...and"):

Independent events:
```
P(A and B) = P(A) × P(B)
```
Dependent events:
```
P(A and B) = P(A) × P(B|A)
```

### 4.4 Complementary Events
```
P(A') = 1 - P(A)
P(at least one) = 1 - P(none)
```

---

<a name="unit-5"></a>
## UNIT 5: PROBABILITY DISTRIBUTIONS

### 5.1 Binomial Distribution

**Conditions (all four must hold):**
1. Fixed number of trials (n)
2. Trials are independent
3. Each trial is SUCCESS or FAILURE only
4. Probability p remains constant each trial

**Notation:** X ~ B(n, p)

**Formula:**
```
P(X = x) = ⁿCₓ · pˣ · qⁿ⁻ˣ
```
Where q = 1 - p, and ⁿCₓ = n! / [x!(n-x)!]

**Mean and Variance:**
```
Mean (μ) = np
Variance (σ²) = npq
Standard Deviation (σ) = √(npq)
```

**Note on independence:** If n ≤ 0.05N, trials may be treated as independent even without replacement.

---

### 5.2 Poisson Distribution

**Use when:** n is large and p is small (n > 20 and np < 5)

**Notation:** X ~ Po(λ), where λ = np

**Formula:**
```
P(X = x) = (e⁻λ · λˣ) / x!
```
Where e = 2.7183

**Mean and Variance:**
```
E(X) = λ
Var(X) = λ
```

---

### 5.3 Normal Distribution

**Notation:** X ~ N(μ, σ²)

**Key Properties:**
- Bell-shaped, symmetric about the mean
- Mean = Median = Mode
- Total area under curve = 1

**Empirical Rule:**
```
±1σ from mean → ~68% of data
±2σ from mean → ~95% of data
±3σ from mean → ~99% of data
```

**Standardisation (Z-score):**
```
Z = (X - μ) / σ
```
Standard normal: Z ~ N(0, 1)

**Using Z-tables:**
- Find area between z = 0 and z = value from table
- Use symmetry for negative z values
- P(Z > z) = 0.5 - P(0 < Z < z)
- P(Z < z) = 0.5 + P(0 < Z < z)

---

<a name="unit-5"></a>
## UNIT 5: PROBABILITY DISTRIBUTIONS

### 5.1 Binomial Distribution

**Conditions (all four must hold):**
1. Fixed number of trials (n)
2. Trials are independent
3. Each trial is SUCCESS or FAILURE only
4. Probability p remains constant each trial

**Notation:** X ~ B(n, p)

**Formula:**
```
P(X = x) = nCx · p^x · q^(n-x)
```
Where q = 1 - p, and nCx = n! / [x!(n-x)!]

**Mean and Variance:**
```
Mean (μ) = np
Variance (σ²) = npq
Standard Deviation (σ) = √(npq)
```

### 5.2 Poisson Distribution

**Use when:** n > 20 and np < 5 (large n, small p)

**Notation:** X ~ Po(λ), where λ = np

**Formula:**
```
P(X = x) = (e^-λ · λ^x) / x!    where e = 2.7183
```

**Mean and Variance:**
```
E(X) = λ    Var(X) = λ
```

### 5.3 Normal Distribution

**Notation:** X ~ N(μ, σ²)

**Key Properties:**
- Bell-shaped, symmetric about the mean
- Mean = Median = Mode
- Total area under curve = 1

**Empirical Rule:**
```
±1σ  →  ~68% of data
±2σ  →  ~95% of data
±3σ  →  ~99% of data
```

**Standardisation (Z-score):**
```
Z = (X - μ) / σ
```
Standard normal: Z ~ N(0, 1)

**Using Z-tables:**
- P(Z > z) = 0.5 - P(0 < Z < z)
- P(Z < z) = 0.5 + P(0 < Z < z)
- For negative z, use symmetry: P(Z < -z) = P(Z > z)

---

<a name="unit-6"></a>
## UNIT 6: INDEX NUMBERS

### 6.1 Definition
Index numbers are statistical devices designed to measure the relative change in the level of a variable or group of variables with respect to time or geographical location.

**Base year index is always = 100**

### 6.2 Uses of Index Numbers
1. Economic barometers (measure inflation/deflation)
2. Guide economic policies and planning
3. Study trends and tendencies
4. Forecast future economic activity
5. Measure purchasing power of money
6. Deflating nominal values to real values

### 6.3 Classification
- **Price index numbers** – measure changes in price level
- **Quantity index numbers** – measure changes in volume of production/sales
- **Value index numbers** – measure changes in total value

### 6.4 Methods of Constructing Index Numbers

**A. Unweighted Indices**

**i) Simple Aggregative Method:**
```
P₀₁ = (ΣP₁ / ΣP₀) × 100
```

**ii) Simple Average of Relatives (using AM):**
```
P₀₁ = (1/n) × Σ[(P₁/P₀) × 100]
```

**B. Weighted Indices**

**i) Laspeyre's Index** (base year quantities as weights):
```
P₀₁ = [Σ(P₁Q₀) / Σ(P₀Q₀)] × 100
```

**ii) Paasche's Index** (current year quantities as weights):
```
P₀₁ = [Σ(P₁Q₁) / Σ(P₀Q₁)] × 100
```

**iii) Fisher's Ideal Index** (geometric mean of Laspeyre's and Paasche's):
```
P₀₁ = √(Laspeyre's × Paasche's)
```
Called "ideal" because it satisfies both the Time Reversal Test and Factor Reversal Test.

### 6.5 Laspeyre's vs Paasche's
- Laspeyre's has **upward bias** (overestimates price rise)
- Paasche's has **downward bias** (underestimates price rise)
- Fisher's balances both biases

### 6.6 Consumer Price Index (CPI)

**Aggregate Expenditure Method:**
```
CPI = [Σ(P₁Q₀) / Σ(P₀Q₀)] × 100
```

**Family Budget Method:**
```
CPI = ΣPV / ΣV
where P = (P₁/P₀) × 100,  V = P₀Q₀
```
Both methods give the same result.

**Real Wages:**
```
Real Wage = (Money Wage / CPI) × 100
```

### 6.7 Tests for Index Numbers (Fisher's Tests)
1. **Time Reversal Test:** P₀₁ × P₁₀ = 1
2. **Factor Reversal Test:** P₀₁ × Q₀₁ = V₀₁

---

<a name="unit-7"></a>
## UNIT 7: PRACTICE PROBLEMS AND SOLUTIONS

### Correlation & Regression

**Problem 1:** Find the regression equations and correlation coefficient from:

| X | 25 | 28 | 35 | 32 | 31 | 36 | 29 | 38 | 34 | 32 |
|---|----|----|----|----|----|----|----|----|----|----|
| Y | 43 | 46 | 49 | 41 | 36 | 32 | 31 | 30 | 33 | 39 |

**Solution outline:**
- x̄ = 320/10 = 32,  ȳ = 380/10 = 38
- Σdx² = 140,  Σdy² = 398,  Σdxdy = -93
- byx = -93/140 = -0.664
- bxy = -93/398 = -0.234
- r = -√(0.664 × 0.234) = **-0.394**
- Regression of Y on X:  Y - 38 = -0.664(X - 32)  →  **Y = 59.25 - 0.664X**
- For X = 30:  Y = 59.25 - 0.664(30) = **39.33 marks**

---

### Probability

**Problem 2:** A bag has 8 red, 15 white, 24 black, 17 orange balls (total = 64). Two drawn WITH replacement.

- P(2 red) = (8/64)² = 0.0156
- P(no orange) = (47/64)² = 0.5396
- P(at least 1 black) = 1 - P(no black) = 1 - (40/64)² = 0.6094

---

### Normal Distribution

**Problem 3:** Mass of 200 people: μ = 67 kg, σ = 7 kg. Normally distributed.

- P(60 < X < 74): Z = ±1 → area = 0.6826 → **134 people**
- P(X > 81): Z = (81-67)/7 = 2 → area = 0.5 - 0.4772 = 0.0228 → **~5 people**
- P(53 < X < 88): Z = -2 and Z = 3 → area = 0.9759 → **~195 people**

---

### Index Numbers

**Problem 4:** Calculate index for 1995 (base 1991):

| Commodity | P₀ (1991) | P₁ (1995) |
|-----------|-----------|-----------|
| A | 2.50 | 4.00 |
| B | 5.40 | 7.20 |
| C | 6.00 | 7.00 |
| D | 150.00 | 200.00 |
| E | 2.50 | 3.00 |
| **Total** | **166.40** | **221.20** |

```
P₀₁ = (221.20 / 166.40) × 100 = 132.93
```
**Prices increased by 32.93% from 1991 to 1995.**

---

<a name="unit-8"></a>
## UNIT 8: ADDITIONAL REFERENCE MATERIALS

### Key Textbooks
1. **Spiegel, M.R.** – *Statistics* (Schaum's Outline Series) – Covers all topics in this unit with worked examples
2. **Gupta, S.C. & Kapoor, V.K.** – *Fundamentals of Mathematical Statistics* – Comprehensive coverage of probability and distributions
3. **Croxton, F.E. & Cowden, D.J.** – *Applied General Statistics* – Classic reference for index numbers and descriptive statistics
4. **Walpole, R.E.** – *Introduction to Statistics* – Good for probability distributions and regression

### Online Resources
- **Khan Academy** (khanacademy.org) – Free video lessons on statistics and probability
- **Stat Trek** (stattrek.com) – Online stat tutorials, tables, and calculators
- **NIST/SEMATECH e-Handbook** (itl.nist.gov) – Engineering statistics reference
- **Wolfram Alpha** (wolframalpha.com) – Compute statistical values and verify calculations

### Z-Table Quick Reference

| Z | Area (0 to Z) |
|---|---|
| 0.50 | 0.1915 |
| 1.00 | 0.3413 |
| 1.28 | 0.3997 |
| 1.50 | 0.4332 |
| 1.64 | 0.4495 |
| 1.96 | 0.4750 |
| 2.00 | 0.4772 |
| 2.33 | 0.4901 |
| 2.58 | 0.4951 |
| 3.00 | 0.4987 |

### Formula Summary Sheet

| Topic | Formula |
|---|---|
| Pearson's r | Σ(dx·dy) / √(Σdx²·Σdy²) |
| Spearman's ρ | 1 - 6Σd²/n(n²-1) |
| Regression byx | Σ(dx·dy) / Σdx² |
| Binomial P(x) | nCx · pˣ · qⁿ⁻ˣ |
| Poisson P(x) | e⁻λ · λˣ / x! |
| Z-score | (X - μ) / σ |
| Laspeyre's | Σ(P₁Q₀)/Σ(P₀Q₀) × 100 |
| Paasche's | Σ(P₁Q₁)/Σ(P₀Q₁) × 100 |
| Fisher's | √(Laspeyre's × Paasche's) |
| CPI (real wage) | (Money Wage / CPI) × 100 |
| Sturges Rule | k = 1 + 3.322 log N |
| CV | (σ / x̄) × 100% |

### Exam Tips
1. Always show your working — method marks are awarded
2. For correlation, state the degree (high/low) AND nature (positive/negative)
3. For normal distribution, always draw a sketch and shade the required area
4. For index numbers, clearly label base year (P₀, Q₀) and current year (P₁, Q₁)
5. Check: regression coefficient signs must match the sign of r
6. For Poisson approximation, verify n > 20 AND np < 5 before applying

---
*End of Revision Guide — BSC7124 Apply Maths for Economics*
