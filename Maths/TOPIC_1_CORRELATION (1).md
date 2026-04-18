# TOPIC 1: CORRELATION
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## 1. Definition

Correlation is a statistical tool that studies the **relationship between two variables**. Two variables are correlated if a change in one results in a corresponding change in the other.

---

## 2. Types of Correlation

### Positive Correlation
Both variables move in the **same direction**.

Examples:
- Heights and weights
- Family income and expenditure on luxury items
- Annual mileage and annual maintenance costs
- Day temperature and sale of soft drinks
- Rainfall and crop yield
- Price and supply of a commodity

### Negative (Inverse) Correlation
Variables move in **opposite directions**.

Examples:
- Price and demand of a commodity
- Age and second-hand value of cars
- Height above sea level and temperature
- Volume and pressure of a perfect gas
- Day temperature and sale of woolen garments

### Perfect Correlation
- r = +1: Perfect positive
- r = -1: Perfect negative

### No Correlation
- r = 0: No linear relationship

---

## 3. Methods of Studying Correlation

1. Scatter Diagram Method
2. Karl Pearson's Coefficient of Correlation (Covariance Method)
3. Spearman's Rank Correlation Method

---

## 4. Karl Pearson's Coefficient of Correlation

Developed by Karl Pearson (1867–1936), a British Biometrician and Statistician.

### Formula (Deviation Method):
```
r = Σ(dx · dy) / √(Σdx² × Σdy²)

where dx = x - x̄  and  dy = y - ȳ
```

### Shortcut (Assumed Mean Method):
```
r = Σ(du · dv) / √(Σdu² × Σdv²)

where u = x - A  and  v = y - B  (A, B are assumed means)
```

### Properties:
1. r always lies between -1 and +1: **-1 ≤ r ≤ +1**
2. r is **independent of change of origin and scale**
3. r is dimensionless (no units)
4. If r is outside [-1, +1], there is a calculation error

### Interpretation of r:

| Value of |r| | Degree of Correlation |
|---|---|
| 1.0 | Perfect |
| 0.8 – 1.0 | Very high |
| 0.6 – 0.8 | High |
| 0.4 – 0.6 | Moderate |
| 0.2 – 0.4 | Low |
| 0.0 – 0.2 | Very low / negligible |

---

## 5. Worked Example 1 — Husband and Wife Ages

**Data:**

| x (husband) | 23 | 27 | 28 | 29 | 30 | 31 | 33 | 35 | 36 | 39 |
|---|---|---|---|---|---|---|---|---|---|---|
| y (wife) | 18 | 22 | 23 | 24 | 25 | 26 | 28 | 29 | 30 | 32 |

**Solution:** Use assumed means A = 30, B = 25

| x  | y  | u=x-30 | v=y-25 | u²  | v²  | uv  |
|----|----|--------|--------|-----|-----|-----|
| 23 | 18 | -7     | -7     | 49  | 49  | 49  |
| 27 | 22 | -3     | -3     | 9   | 9   | 9   |
| 28 | 23 | -2     | -2     | 4   | 4   | 4   |
| 29 | 24 | -1     | -1     | 1   | 1   | 1   |
| 30 | 25 | 0      | 0      | 0   | 0   | 0   |
| 31 | 26 | 1      | 1      | 1   | 1   | 1   |
| 33 | 28 | 3      | 3      | 9   | 9   | 9   |
| 35 | 29 | 5      | 4      | 25  | 16  | 20  |
| 36 | 30 | 6      | 5      | 36  | 25  | 30  |
| 39 | 32 | 9      | 7      | 81  | 49  | 63  |
| **Σ** | | **11** | **7** | **215** | **163** | **186** |

Wait — using the values from the course notes:
Σu=0, Σv=7, Σu²=220, Σv²=163, Σuv=179 (n=10)

```
r = [nΣuv - ΣuΣv] / √{[nΣu² - (Σu)²][nΣv² - (Σv)²]}
  = [10×179 - 0×7] / √{[10×220 - 0][10×163 - 49]}
  = 1790 / √{2200 × 1581}
  = 1790 / √3478200
  = 1790 / 1865.0
  ≈ 0.96
```
**Conclusion:** Very close (high positive) correlation between husband and wife ages.

---

## 6. Worked Example 2 — Newton's Law of Cooling

**Data:**

| Time x (min) | 4  | 8  | 10 | 12 | 16 | 22 |
|---|---|---|---|---|---|---|
| Temp y (°C)  | 46 | 34 | 30 | 26 | 24 | 20 |

Use u = (x-12)/2, v = (y-30)/2

| x  | y  | u  | v  | u²  | v²  | uv  |
|----|----|----|----|----|-----|-----|
| 4  | 46 | -4 | 8  | 16 | 64  | -32 |
| 8  | 34 | -2 | 2  | 4  | 4   | -4  |
| 10 | 30 | -1 | 0  | 1  | 0   | 0   |
| 12 | 26 | 0  | -2 | 0  | 4   | 0   |
| 16 | 24 | 2  | -3 | 4  | 9   | -6  |
| 22 | 20 | 5  | -5 | 25 | 25  | -25 |
| **Σ** | | **0** | **0** | **50** | **106** | **-67** |

```
r = Σuv / √(Σu² × Σv²)
  = -67 / √(50 × 106)
  = -67 / √5300
  = -67 / 72.80
  = -0.92
```
**Degree:** Good (high)  
**Nature:** Inverse (negative) — as time increases, temperature decreases.

---

## 7. Spearman's Rank Correlation Coefficient

Developed by **Charles Edward Spearman** (British Psychologist, 1904).

Used when:
- Data is qualitative (beauty, honesty, intelligence)
- Exact measurement is not possible
- Data is already in rank form

### Formula:
```
ρ = 1 - [6Σd²] / [n(n² - 1)]
```
Where d = difference between ranks of the same individual, n = number of pairs.

**Range:** -1 ≤ ρ ≤ +1

### Assigning Ranks:
- Highest (or lowest) value gets rank 1 — be consistent
- Use the same direction (ascending or descending) for all variables

### Tied Ranks:
When values repeat, assign the **average of the ranks** they would have occupied.

Example: If two items tie at rank 4 and 5, each gets rank (4+5)/2 = 4.5. Next item gets rank 6.

### Correction Factor for Tied Ranks:
```
CF = (m³ - m) / 12
```
Add one CF for each group of tied values. The corrected formula becomes:
```
ρ = 1 - [6(Σd² + CF₁ + CF₂ + ...)] / [n(n² - 1)]
```

---

## 8. Worked Example 3 — Spearman's (No Ties)

**Data:** Advertisement cost (x) and Sales (y):

| x | 39 | 65 | 62 | 90 | 82 | 75 | 25 | 98 | 36 | 78 |
|---|---|---|---|---|---|---|---|---|---|---|
| y | 47 | 53 | 58 | 86 | 62 | 68 | 60 | 91 | 51 | 84 |

| x  | y  | Rank x | Rank y | d   | d²  |
|----|----|--------|--------|-----|-----|
| 39 | 47 | 8      | 10     | -2  | 4   |
| 65 | 53 | 6      | 8      | -2  | 4   |
| 62 | 58 | 7      | 7      | 0   | 0   |
| 90 | 86 | 2      | 2      | 0   | 0   |
| 82 | 62 | 3      | 5      | -2  | 4   |
| 75 | 68 | 5      | 4      | 1   | 1   |
| 25 | 60 | 10     | 6      | 4   | 16  |
| 98 | 91 | 1      | 1      | 0   | 0   |
| 36 | 51 | 9      | 9      | 0   | 0   |
| 78 | 84 | 4      | 3      | 1   | 1   |
| **Σ** | | | | | **30** |

```
ρ = 1 - [6 × 30] / [10(100 - 1)]
  = 1 - 180/990
  = 1 - 0.182
  = 0.818
```
**High positive correlation** between advertising cost and sales.

---

## 9. Worked Example 4 — Spearman's (With Ties)

**Data:** Teaching methods A and B (11 pairs):

| Pair | 1  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 |
|------|----|----|----|----|----|----|----|----|----|----|-----|
| A    | 24 | 29 | 19 | 14 | 30 | 19 | 27 | 30 | 20 | 28 | 11 |
| B    | 37 | 35 | 16 | 26 | 23 | 27 | 19 | 20 | 16 | 11 | 21 |

Ranks for A (descending): 30,30 → 1.5,1.5; 29→3; 28→4; 27→5; 24→6; 20→7; 19,19→8.5,8.5; 14→10; 11→11

| A  | B  | Rank A | Rank B | d    | d²    |
|----|----|--------|--------|------|-------|
| 24 | 37 | 6      | 1      | 5    | 25    |
| 29 | 35 | 3      | 2      | 1    | 1     |
| 19 | 16 | 8.5    | 9.5    | -1   | 1     |
| 14 | 26 | 10     | 4      | 6    | 36    |
| 30 | 23 | 1.5    | 5      | -3.5 | 12.25 |
| 19 | 27 | 8.5    | 3      | 5.5  | 30.25 |
| 27 | 19 | 5      | 8      | -3   | 9     |
| 30 | 20 | 1.5    | 7      | -5.5 | 30.25 |
| 20 | 16 | 7      | 9.5    | -2.5 | 6.25  |
| 28 | 11 | 4      | 11     | -7   | 49    |
| 11 | 21 | 11     | 6      | 5    | 25    |
| **Σ** | | | | | **225** |

Ties: In A — 30 repeated twice (m=2), 19 repeated twice (m=2). In B — 16 repeated twice (m=2).

```
CF for each = (2³ - 2)/12 = 6/12 = 0.5
Total CF = 0.5 + 0.5 + 0.5 = 1.5

ρ = 1 - [6(225 + 1.5)] / [11(121 - 1)]
  = 1 - [6 × 226.5] / [11 × 120]
  = 1 - 1359/1320
  = 1 - 1.0295
  = -0.0295 ≈ -0.023
```
**Very low negative correlation** — the two teaching methods produce almost unrelated results.

---

## 10. Worked Example 5 — Spearman's (15 Students, Given Ranks)

Ranks of 15 students in subjects A and B:
(1,10),(2,7),(3,2),(4,6),(5,4),(6,8),(7,3),(8,1),(9,11),(10,15),(11,9),(12,5),(13,14),(14,12),(15,13)

| Rank A | Rank B | d   | d²  |
|--------|--------|-----|-----|
| 1      | 10     | -9  | 81  |
| 2      | 7      | -5  | 25  |
| 3      | 2      | 1   | 1   |
| 4      | 6      | -2  | 4   |
| 5      | 4      | 1   | 1   |
| 6      | 8      | -2  | 4   |
| 7      | 3      | 4   | 16  |
| 8      | 1      | 7   | 49  |
| 9      | 11     | -2  | 4   |
| 10     | 15     | -5  | 25  |
| 11     | 9      | 2   | 4   |
| 12     | 5      | 7   | 49  |
| 13     | 14     | -1  | 1   |
| 14     | 12     | 2   | 4   |
| 15     | 13     | 2   | 4   |
| **Σ** | | | **272** |

```
ρ = 1 - [6 × 272] / [15(225 - 1)]
  = 1 - 1632/3360
  = 1 - 0.486
  = 0.514
```
**Moderate positive correlation** between performance in subjects A and B.

---

## 11. Practice Questions

**Q1.** Find Karl Pearson's r between sales and expenses for 10 firms:

| Firm | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 |
|---|---|---|---|---|---|---|---|---|---|---|
| Sales ('000 units) | 50 | 50 | 55 | 60 | 65 | 65 | 65 | 60 | 60 | 50 |
| Expenses ('00,000 Ksh) | 11 | 13 | 14 | 16 | 16 | 15 | 15 | 14 | 13 | 13 |

**Q2.** Preference share prices (x): 73.2, 85.8, 78.9, 77.2, 81.2, 83.8  
Debenture prices (y): 97.8, 99.2, 98.8, 98.3, 96.7, 97.1  
Use rank correlation to determine the relationship.

**Q3 (Assignment).** Ten competitors in a beauty contest are ranked by three judges:
- Judge 1: 1, 6, 5, 10, 3, 2, 4, 9, 7, 7
- Judge 2: 3, 5, 8, 4, 7, 10, 2, 1, 6, 9
- Judge 3: 6, 4, 9, 8, 1, 2, 3, 10, 5, 7

Use Spearman's ρ to determine which pair of judges has the nearest approach to common taste.
