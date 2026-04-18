# TOPIC 5: PROBABILITY AND PROBABILITY DISTRIBUTIONS
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## PART A: PROBABILITY

### 1. Definitions

- **Probability:** The likelihood of an event occurring. Range: 0 ≤ P(x) ≤ 1
- **Expectation:** P(success) × number of attempts

### 2. Types of Events

| Type | Definition | Example |
|---|---|---|
| Independent | One event does NOT affect the other | Drawing WITH replacement |
| Dependent | One event DOES affect the other | Drawing WITHOUT replacement |
| Mutually Exclusive | Only one can occur at a time | Head or tail on a coin |

### 3. Laws of Probability

**Addition Law** — "either...or" — mutually exclusive events:
```
P(A or B) = P(A) + P(B)
```
Non-mutually exclusive:
```
P(A or B) = P(A) + P(B) - P(A and B)
```

**Multiplication Law** — "both...and":
```
Independent:  P(A and B) = P(A) × P(B)
Dependent:    P(A and B) = P(A) × P(B|A)
```

**Complement:**
```
P(A') = 1 - P(A)
P(at least one) = 1 - P(none)
```

---

### 4. Worked Example 1

**Problem:** Bag contains 8 red, 15 white, 24 black, 17 orange balls (total = 64). Two drawn WITH replacement.

**(a) P(two red):**
```
= (8/64) × (8/64) = 64/4096 = 0.0156
```

**(b) P(red and white):**
```
= P(RW) + P(WR) = (8/64)(15/64) + (15/64)(8/64) = 2 × 0.02930 = 0.0586
```

**(c) P(no orange):**
```
= (47/64) × (47/64) = 2209/4096 = 0.5393
```

**(d) P(black and red OR black and orange):**
```
= P(BR) + P(RB) + P(BO) + P(OB)
= 2×(24/64)(8/64) + 2×(24/64)(17/64)
= 2×0.04688 + 2×0.09961 = 0.2930
```

**(e) P(at least one black):**
```
= 1 - P(no black) = 1 - (40/64)² = 1 - 0.3906 = 0.6094
```

**(f) P(at most one orange):**
```
= P(0 orange) + P(1 orange)
= (47/64)² + 2×(17/64)(47/64)
= 0.5393 + 0.3906 = 0.9299
```

**(g) P(white first, second not white):**
```
= (15/64) × (49/64) = 735/4096 = 0.1794
```

---

### 5. Worked Example 2 (Assignment)

**Problem:** Bag 1: 3 red, 5 black. Bag 2: 4 green, 7 white. Draw 1 from Bag 1, 2 from Bag 2 WITHOUT replacement.

**(a) P(1 red and 2 white):**
```
= (3/8) × (7/11)(6/10) = (3/8) × (42/110) = 126/880 = 0.1432
```

**(b) P(no green) = P(1 black and 2 white):**
```
= (5/8) × (7/11)(6/10) = (5/8) × 0.3818 = 0.2386
```

**(c) P(1 black and 2 green OR 1 black and 2 white):**
```
P(1 black, 2 green) = (5/8) × (4/11)(3/10) = (5/8) × 0.1091 = 0.0682
P(1 black, 2 white) = 0.2386 (from above)
Total = 0.0682 + 0.2386 = 0.3068
```

---

## PART B: BINOMIAL DISTRIBUTION

### 6. Conditions (all four must hold)
1. Fixed number of trials (n)
2. Trials are independent
3. Each trial: SUCCESS or FAILURE only
4. Probability p is constant each trial

**Notation:** X ~ B(n, p),  q = 1 - p

### 7. Formula
```
P(X = x) = nCx · pˣ · q^(n-x)

nCx = n! / [x!(n-x)!]
```

### 8. Mean and Variance
```
Mean:     μ = np
Variance: σ² = npq
SD:       σ = √(npq)
```

### 9. Worked Example 3

**Problem:** Expected defective discs = 20, variance = 16. Find:
(i) P(defective), (ii) P(non-defective), (iii) number of discs

```
μ = np = 20
σ² = npq = 16

npq/np = q = 16/20 = 0.8
p = 1 - 0.8 = 0.2
n = 20/0.2 = 100 discs
```

**(i) P(defective) = p = 0.2**
**(ii) P(non-defective) = q = 0.8**
**(iii) n = 100 discs**

---

### 10. Worked Example 4

**Problem:** 20 unbiased coins tossed. p = 0.5, n = 20.

**(i) P(exactly 8 heads):**
```
P(X=8) = 20C8 × (0.5)⁸ × (0.5)¹² = 125970 × (0.5)²⁰ = 125970/1048576 = 0.1201
```

**(ii) P(at least 2 heads) = 1 - P(0) - P(1):**
```
P(X=0) = (0.5)²⁰ = 0.000000954
P(X=1) = 20 × (0.5)²⁰ = 0.0000191
P(X≥2) = 1 - 0.0000200 ≈ 0.9999800
```

**(iii) P(at most 3 heads) = P(0)+P(1)+P(2)+P(3):**
```
P(X=2) = 190 × (0.5)²⁰ = 0.000181
P(X=3) = 1140 × (0.5)²⁰ = 0.001087
P(X≤3) ≈ 0.001289
```

---

### 11. Worked Example 5

**Problem:** 10% production defective. Sample of 10.

**(i) P(exactly 2 defective):** n=10, p=0.1, q=0.9
```
P(X=2) = 10C2 × (0.1)² × (0.9)⁸ = 45 × 0.01 × 0.4305 = 0.1937
```

**(ii) P(at most 2 defective):**
```
P(X=0) = (0.9)¹⁰ = 0.3487
P(X=1) = 10 × 0.1 × (0.9)⁹ = 0.3874
P(X=2) = 0.1937
P(X≤2) = 0.9298
```

---

## PART C: POISSON DISTRIBUTION

### 12. When to Use
- n is large and p is small
- Rule: n > 20 AND np < 5 (or nq < 5)
- λ = np (the mean)

**Notation:** X ~ Po(λ)

### 13. Formula
```
P(X = x) = (e^-λ × λˣ) / x!     where e = 2.7183
```

### 14. Mean and Variance
```
E(X) = λ      Var(X) = λ
```

### 15. Worked Example 6

**Problem:** 80% of PC users have proprietary OS. Group of 1000.

```
n=1000, p=0.8
Mean = np = 800
SD = √(npq) = √(1000×0.8×0.2) = √160 = 12.65
```

---

### 16. Worked Example 7

**Problem:** 1 in 200 cars breaks down per day.

**(i) P(none in 250 cars):** λ = 250/200 = 1.25
```
P(X=0) = e^-1.25 = 0.2865
```

**(ii) P(more than 2 in 300 cars):** λ = 300/200 = 1.5
```
P(X=0) = e^-1.5 = 0.2231
P(X=1) = 1.5 × e^-1.5 = 0.3347
P(X=2) = (1.5²/2) × e^-1.5 = 0.2510
P(X≤2) = 0.8088
P(X>2) = 1 - 0.8088 = 0.1912
```

---

## PART D: NORMAL DISTRIBUTION

### 17. Key Properties
- Bell-shaped, symmetric about the mean
- Mean = Median = Mode
- Total area = 1
- Notation: X ~ N(μ, σ²)

### 18. Empirical Rule
```
±1σ → 68% of data
±2σ → 95% of data
±3σ → 99% of data
```

### 19. Standardisation
```
Z = (X - μ) / σ        Z ~ N(0,1)
```

### 20. Z-table Areas (from 0 to Z)

| Z    | Area   |
|------|--------|
| 0.50 | 0.1915 |
| 1.00 | 0.3413 |
| 1.28 | 0.3997 |
| 1.64 | 0.4495 |
| 1.96 | 0.4750 |
| 2.00 | 0.4772 |
| 2.33 | 0.4901 |
| 3.00 | 0.4987 |

### 21. Probability Rules Using Z-table

```
P(0 < Z < a)       → read directly from table
P(-a < Z < 0)      = P(0 < Z < a)   [symmetry]
P(-a < Z < a)      = 2 × P(0 < Z < a)
P(Z > a)           = 0.5 - P(0 < Z < a)
P(Z < a)           = 0.5 + P(0 < Z < a)
P(Z < -a)          = 0.5 - P(0 < Z < a)
P(a < Z < b)       = P(0<Z<b) - P(0<Z<a)   [same side]
P(-a < Z < b)      = P(0<Z<a) + P(0<Z<b)   [opposite sides]
```

### 22. Worked Example 8

**Problem:** 200 people, μ=67 kg, σ=7 kg. How many have mass:

**(i) Between 60 and 74 kg:**
```
Z₁ = (60-67)/7 = -1.0 → area = 0.3413
Z₂ = (74-67)/7 = +1.0 → area = 0.3413
P = 0.3413 + 0.3413 = 0.6826
Number = 0.6826 × 200 = 137 people
```

**(ii) More than 81 kg:**
```
Z = (81-67)/7 = 2.0 → area = 0.4772
P(X>81) = 0.5 - 0.4772 = 0.0228
Number = 0.0228 × 200 = 5 people
```

**(iii) Between 53 and 88 kg:**
```
Z₁ = (53-67)/7 = -2.0 → area = 0.4772
Z₂ = (88-67)/7 = +3.0 → area = 0.4987
P = 0.4772 + 0.4987 = 0.9759
Number = 0.9759 × 200 = 195 people
```

---

### 23. Worked Example 9 — Finding Z areas

**(i) Between z=0 and z=1.2:** → **0.3849**
**(ii) Between z=-0.68 and z=0:** → **0.2518**
**(iii) Between z=-0.46 and z=2.21:** = 0.1772 + 0.4864 = **0.6636**
**(iv) Between z=0.81 and z=1.94:** = 0.4738 - 0.2910 = **0.1828**
**(v) To the left of z=-0.6:** = 0.5 - 0.2257 = **0.2743**
**(vi) To the right of z=-1.28:** = 0.5 + 0.3997 = **0.8997**
**(vii) Right of z=2.05 AND left of z=-1.44:**
```
= (0.5-0.4798) + (0.5-0.4251) = 0.0202 + 0.0749 = 0.0951
```

---

### 24. Worked Example 10 — Finding Z values

**(i) Area between 0 and z = 0.3770:** → z = **1.16**
**(ii) Area to left of z = 0.8621:** → P(0<Z<z) = 0.3621 → z = **1.09**
**(iii) Area between -1.5 and z = 0.0217:**
- Area from 0 to 1.5 = 0.4332
- Case I: z on same side → P(0<Z<z) = 0.4332 - 0.0217 = 0.4115 → z = **-1.35**
- Case II: z on other side → P(0<Z<z) = -(0.4332 + 0.0217) → z = **-1.69**

---

### 25. Worked Example 11 — MPs Learning Standing Orders

**Problem:** Time normally distributed, μ=80 hrs, σ=6 hrs. Sample of 16. P(mean > 90)?

Use standard error: SE = σ/√n = 6/√16 = 1.5
```
Z = (90 - 80)/1.5 = 6.67
P(X̄ > 90) = 0.5 - 0.4999 ≈ 0.0000 (virtually impossible)
```

---

### 26. Worked Example 12 — Finding μ and σ

**Problem:** P(X < 1980) = 0.121 and P(X > 2060) = 0.209

```
P(X < 1980) = 0.121 → P(Z < z₁) = 0.121 → z₁ = -1.165
P(X > 2060) = 0.209 → P(Z > z₂) = 0.209 → z₂ = 0.810

(1980 - μ)/σ = -1.165  ... (1)
(2060 - μ)/σ =  0.810  ... (2)

Subtract (1) from (2):
80/σ = 1.975 → σ = 40.5 hrs

From (1): μ = 1980 + 1.165 × 40.5 = 2027.2 hrs
```

**(iii) P(X > 2010):**
```
Z = (2010 - 2027.2)/40.5 = -0.425
P(X > 2010) = 0.5 + P(0<Z<0.425) = 0.5 + 0.1628 = 0.6628
```

---

### 27. Practice Questions

**Q1 (Assignment).** 500 candidates, μ=45, σ=5. Pass mark=40.
(a) How many passed?
(b) If 4% got distinction scoring X or more, find X.
(c) Find the interquartile range.

**Q2.** X ~ N(μ, σ). 12.3% of distribution > 60 and 5.89% < 40. Find μ and σ.

**Q3 (Assignment).** 800 students, 80 left-handed.
(a) Mean proportion of left-handed students
(b) Standard deviation for left-handed students
