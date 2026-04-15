# TOPIC 4: DESCRIPTIVE STATISTICS — MEASURES OF CENTRAL TENDENCY AND DISPERSION
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## PART A: MEASURES OF CENTRAL TENDENCY

A measure of central tendency is a single value that represents the centre of a dataset.

---

## 1. Arithmetic Mean (x̄)

### Ungrouped Data:
```
x̄ = Σx / n
```

### Grouped Data (Direct Method):
```
x̄ = Σfx / Σf
```

### Grouped Data (Assumed Mean / Shortcut Method):
```
x̄ = A + (Σfd / Σf)     where d = x - A
```

### Grouped Data (Step Deviation Method):
```
x̄ = A + (Σfu / Σf) × h     where u = (x - A)/h
```

---

## 2. Median

The middle value when data is arranged in order.

### Ungrouped Data:
```
If n is odd:  Median = [(n+1)/2]th value
If n is even: Median = average of (n/2)th and (n/2 + 1)th values
```

### Grouped Data:
```
Median = L + [(n/2 - cf) / f] × h
```
Where:
- L = lower boundary of median class
- n = total frequency
- cf = cumulative frequency of class before median class
- f = frequency of median class
- h = class width

**Median class:** The class where cumulative frequency first reaches or exceeds n/2.

---

## 3. Mode

The most frequently occurring value.

### Ungrouped Data:
The value that appears most often.

### Grouped Data:
```
Mode = L + [f₁ - f₀] / [2f₁ - f₀ - f₂] × h
```
Where:
- L = lower boundary of modal class
- f₁ = frequency of modal class (highest frequency)
- f₀ = frequency of class before modal class
- f₂ = frequency of class after modal class
- h = class width

**Modal class:** The class with the highest frequency.

---

## 4. Worked Example — Grouped Data

**Data:** Wages of 50 workers (Ksh '000):

| Class | f  | x  | d=x-35 | fd  | fd²  | cf |
|-------|----|----|--------|-----|------|----|
| 10–20 | 8  | 15 | -20    | -160| 3200 | 8  |
| 20–30 | 14 | 25 | -10    | -140| 1400 | 22 |
| 30–40 | 16 | 35 | 0      | 0   | 0    | 38 |
| 40–50 | 8  | 45 | 10     | 80  | 800  | 46 |
| 50–60 | 4  | 55 | 20     | 80  | 1600 | 50 |
| **Σ** | **50** | | | **-140** | **7000** | |

**Mean:**
```
x̄ = A + (Σfd/Σf) = 35 + (-140/50) = 35 - 2.8 = 32.2 (Ksh '000)
```

**Median:**
n/2 = 25 → median class = 30–40 (cf before = 22, f = 16)
```
Median = 30 + [(25 - 22)/16] × 10 = 30 + 1.875 = 31.875 (Ksh '000)
```

**Mode:**
Modal class = 30–40 (f₁=16, f₀=14, f₂=8)
```
Mode = 30 + [(16-14)/(2×16-14-8)] × 10 = 30 + [2/10] × 10 = 32 (Ksh '000)
```

---

## PART B: MEASURES OF DISPERSION

Dispersion measures how spread out the data is around the central value.

---

## 5. Range
```
Range = Maximum value - Minimum value
```
Simple but affected by extreme values.

---

## 6. Quartile Deviation (Semi-Interquartile Range)
```
QD = (Q₃ - Q₁) / 2
```

**Finding Q1 and Q3 from grouped data:**
```
Q1 = L + [(n/4 - cf) / f] × h      (use class where cf first reaches n/4)
Q3 = L + [(3n/4 - cf) / f] × h     (use class where cf first reaches 3n/4)
```

---

## 7. Mean Deviation

### From Mean:
```
MD(x̄) = Σ|x - x̄| / n          (ungrouped)
MD(x̄) = Σf|x - x̄| / Σf        (grouped)
```

### From Median:
```
MD(M) = Σ|x - M| / n           (ungrouped)
MD(M) = Σf|x - M| / Σf         (grouped)
```

---

## 8. Standard Deviation and Variance

### Ungrouped Data:
```
σ² = Σ(x - x̄)² / n             (population variance)
σ  = √[Σ(x - x̄)² / n]          (population SD)

s² = Σ(x - x̄)² / (n-1)         (sample variance)
s  = √[Σ(x - x̄)² / (n-1)]      (sample SD)
```

**Shortcut formula:**
```
σ = √[(Σx²/n) - (x̄)²]
```

### Grouped Data (Direct Method):
```
σ = √[Σf(x - x̄)² / Σf]
```

### Grouped Data (Assumed Mean Method):
```
σ = √[(Σfd²/Σf) - (Σfd/Σf)²]     where d = x - A
```

### Grouped Data (Step Deviation Method):
```
σ = h × √[(Σfu²/Σf) - (Σfu/Σf)²]     where u = (x - A)/h
```

---

## 9. Coefficient of Variation (CV)

Used to **compare variability** between two or more datasets with different units or means.
```
CV = (σ / x̄) × 100%
```
- Lower CV → more consistent / less variable
- Higher CV → more variable / less consistent

---

## 10. Worked Example — Standard Deviation (Grouped)

Using the wages data from Part A:

Using step deviation: A = 35, h = 10, u = (x-35)/10

| Class | f  | x  | u  | fu  | fu²  |
|-------|----|----|----|----|------|
| 10–20 | 8  | 15 | -2 | -16| 32   |
| 20–30 | 14 | 25 | -1 | -14| 14   |
| 30–40 | 16 | 35 | 0  | 0  | 0    |
| 40–50 | 8  | 45 | 1  | 8  | 8    |
| 50–60 | 4  | 55 | 2  | 8  | 16   |
| **Σ** | **50** | | | **-14** | **70** |

```
σ = h × √[(Σfu²/Σf) - (Σfu/Σf)²]
  = 10 × √[(70/50) - (-14/50)²]
  = 10 × √[1.4 - 0.0784]
  = 10 × √1.3216
  = 10 × 1.1496
  = 11.50 (Ksh '000)

CV = (11.50/32.2) × 100 = 35.7%
```

---

## PART C: MEASURES OF SKEWNESS AND KURTOSIS

---

## 11. Skewness

Skewness measures the **asymmetry** of a distribution.

### Pearson's Coefficient of Skewness:
```
Sk = (Mean - Mode) / σ
```
Or (when mode is ill-defined):
```
Sk = 3(Mean - Median) / σ
```

### Interpretation:
- Sk = 0: Symmetric (normal) distribution
- Sk > 0: Positively skewed (right tail longer; Mean > Median > Mode)
- Sk < 0: Negatively skewed (left tail longer; Mean < Median < Mode)

---

## 12. Kurtosis

Kurtosis measures the **peakedness** of a distribution.

| Type | Description | β₂ value |
|---|---|---|
| Mesokurtic | Normal distribution | β₂ = 3 |
| Leptokurtic | More peaked than normal | β₂ > 3 |
| Platykurtic | Flatter than normal | β₂ < 3 |

---

## 13. Moments

The **rth moment about the mean** (central moment):
```
μᵣ = Σ(x - x̄)ʳ / n
```

**First four moments:**
- μ₁ = 0 (always zero)
- μ₂ = variance (σ²)
- μ₃ = related to skewness: β₁ = μ₃² / μ₂³
- μ₄ = related to kurtosis: β₂ = μ₄ / μ₂²

**Moment about an arbitrary point A:**
```
μ'ᵣ = Σ(x - A)ʳ / n
```

**Converting moments about A to moments about the mean:**
```
μ₁ = μ'₁ - d          where d = x̄ - A
μ₂ = μ'₂ - (μ'₁)²
μ₃ = μ'₃ - 3μ'₂·μ'₁ + 2(μ'₁)³
μ₄ = μ'₄ - 4μ'₃·μ'₁ + 6μ'₂·(μ'₁)² - 3(μ'₁)⁴
```

---

## 14. Worked Example — Moments

**Problem (from course notes):** The first four moments of a distribution about the value 4 are: -1.5, 17, -30, 108.

Find: (a) Moments about the mean  (b) Moments about the origin  (c) Moments about x = 2

**Given:** μ'₁ = -1.5, μ'₂ = 17, μ'₃ = -30, μ'₄ = 108 (about A = 4)

**(a) Moments about the mean:**

First, find x̄:
```
x̄ = A + μ'₁ = 4 + (-1.5) = 2.5
```

```
μ₁ = 0 (always)

μ₂ = μ'₂ - (μ'₁)² = 17 - (-1.5)² = 17 - 2.25 = 14.75

μ₃ = μ'₃ - 3μ'₂·μ'₁ + 2(μ'₁)³
   = -30 - 3(17)(-1.5) + 2(-1.5)³
   = -30 + 76.5 + 2(-3.375)
   = -30 + 76.5 - 6.75 = 39.75

μ₄ = μ'₄ - 4μ'₃·μ'₁ + 6μ'₂·(μ'₁)² - 3(μ'₁)⁴
   = 108 - 4(-30)(-1.5) + 6(17)(2.25) - 3(5.0625)
   = 108 - 180 + 229.5 - 15.1875
   = 142.3125
```

**(b) Moments about the origin (A = 0):**

Use the moments about the mean with d = x̄ - 0 = 2.5:
```
μ'₁(origin) = x̄ = 2.5
μ'₂(origin) = μ₂ + (x̄)² = 14.75 + 6.25 = 21
μ'₃(origin) = μ₃ + 3μ₂·x̄ + (x̄)³ = 39.75 + 3(14.75)(2.5) + 15.625 = 166.0
μ'₄(origin) = μ₄ + 4μ₃·x̄ + 6μ₂·(x̄)² + (x̄)⁴ = 142.3125 + 4(39.75)(2.5) + 6(14.75)(6.25) + 39.0625 = 878.5
```

**(c) Moments about x = 2:**

d = x̄ - 2 = 2.5 - 2 = 0.5
```
μ'₁(x=2) = d = 0.5
μ'₂(x=2) = μ₂ + d² = 14.75 + 0.25 = 15
μ'₃(x=2) = μ₃ + 3μ₂·d + d³ = 39.75 + 3(14.75)(0.5) + 0.125 = 62.0
μ'₄(x=2) = μ₄ + 4μ₃·d + 6μ₂·d² + d⁴ = 142.3125 + 4(39.75)(0.5) + 6(14.75)(0.25) + 0.0625 = 244.5
```

---

## 15. Practice Questions

**Q1.** The following are test scores of 10 students:
72, 85, 68, 91, 74, 83, 69, 88, 76, 80

Calculate: (a) Mean  (b) Median  (c) Standard Deviation  (d) CV  (e) Pearson's Skewness coefficient

**Q2.** Using the frequency table below, calculate mean, median, mode, standard deviation and CV:

| Class | 0–10 | 10–20 | 20–30 | 30–40 | 40–50 |
|---|---|---|---|---|---|
| Freq  | 5    | 10    | 20    | 10    | 5     |

**Q3.** Two machines A and B produce bolts. Machine A: mean length = 5.02 cm, SD = 0.04 cm. Machine B: mean length = 10.01 cm, SD = 0.06 cm. Which machine is more consistent?

> **Answer:** CV(A) = (0.04/5.02)×100 = 0.80%. CV(B) = (0.06/10.01)×100 = 0.60%. Machine B is more consistent (lower CV).

---

## 16. Key Points to Remember

1. Mean uses all values; it is affected by extreme values (outliers)
2. Median is not affected by extreme values — use it for skewed data
3. Mode is the only measure that can be used for qualitative data
4. For a symmetric distribution: Mean = Median = Mode
5. For positively skewed: Mean > Median > Mode
6. For negatively skewed: Mean < Median < Mode
7. Standard deviation is in the **same units** as the data; variance is in squared units
8. CV has **no units** — use it to compare datasets with different units or scales
