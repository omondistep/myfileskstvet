# TOPIC 6: INDEX NUMBERS
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## 1. Definition

Index numbers are **statistical devices designed to measure the relative change in the level of a variable or group of variables** with respect to time, geographical location, etc.

They express the value of a variable in the **current period** as a percentage of its value in the **base period**.

**Base year index is always = 100**

Key definitions:
- **Croxton & Cowden:** "Devices for measuring differences in the magnitude of a group of related variables."
- **Spiegel:** "A statistical measure designed to show changes in a variable with respect to time, geographic location or other characteristics."

---

## 2. Uses of Index Numbers

1. **Economic barometers** — measure inflation/deflation, economic cycles
2. **Policy formulation** — guide decisions on wages, dearness allowance (DA)
3. **Study trends** — track imports, exports, production over time
4. **Forecasting** — predict future economic activity
5. **Measure purchasing power** — determine real wages
6. **Deflating** — convert nominal values to real values:
```
Real Wage = (Money Wage / CPI) × 100
Purchasing Power of Money = 1 / CPI
```

---

## 3. Classification of Index Numbers

| Type | Measures | Examples |
|---|---|---|
| Price Index | Changes in price level | CPI, WPI |
| Quantity Index | Changes in volume of production/sales | Production index |
| Value Index | Changes in total value | Sales value index |
| Special Purpose | Specific uses | Stock market index |

---

## 4. Problems in Constructing Index Numbers

1. **Purpose** — define clearly what the index will measure
2. **Selection of commodities** — choose representative items relevant to the purpose
3. **Selection of base period** — must be a normal period (free from wars, strikes, floods); not too distant from current period
4. **Data collection** — from reliable sources (trade journals, official publications)
5. **Selection of weights** — reflect relative importance of each item
6. **Choice of average** — GM is theoretically best but AM is used in practice
7. **Choice of formula** — depends on purpose and available data

**Fixed Base vs Chain Base:**
- Fixed base: one base year used throughout
- Chain base: each year compared to the previous year (gives better picture of change)

---

## 5. Methods of Constructing Index Numbers

### A. UNWEIGHTED INDICES

#### i) Simple Aggregative Method
```
P₀₁ = (ΣP₁ / ΣP₀) × 100
```
**Limitations:**
- Units of measurement affect the result
- No consideration of relative importance of commodities

#### ii) Simple Average of Relatives

Using AM:
```
P₀₁ = (1/n) × Σ[(P₁/P₀) × 100]
```
Using GM:
```
P₀₁ = Antilog[(1/n) × Σ log(P₁/P₀ × 100)]
```

---

### B. WEIGHTED INDICES

#### i) Laspeyre's Index (base year quantities as weights)
```
P₀₁ = [Σ(P₁Q₀) / Σ(P₀Q₀)] × 100
```
- Has **upward bias** (overestimates price rise)
- Preferred in practice — weights don't change each year

#### ii) Paasche's Index (current year quantities as weights)
```
P₀₁ = [Σ(P₁Q₁) / Σ(P₀Q₁)] × 100
```
- Has **downward bias** (underestimates price rise)
- Expensive — weights must be recalculated each year

#### iii) Fisher's Ideal Index
```
P₀₁ = √(Laspeyre's × Paasche's)
   = √[Σ(P₁Q₀)/Σ(P₀Q₀) × Σ(P₁Q₁)/Σ(P₀Q₁)] × 100
```
Called **"ideal"** because:
1. Based on GM (theoretically best average)
2. Uses both base and current year quantities
3. Satisfies **Time Reversal Test** and **Factor Reversal Test**
4. Balances upward bias of Laspeyre's and downward bias of Paasche's

#### iv) Dorbish & Bowley's Index (arithmetic mean of Laspeyre's and Paasche's)
```
P₀₁ = (Laspeyre's + Paasche's) / 2
```

#### v) Marshall-Edgeworth Index
```
P₀₁ = [Σ(P₁(Q₀+Q₁)) / Σ(P₀(Q₀+Q₁))] × 100
```

---

## 6. Fisher's Tests

### Time Reversal Test
An index satisfies this test if:
```
P₀₁ × P₁₀ = 1
```
(The index for period 1 relative to period 0, multiplied by the index for period 0 relative to period 1, equals 1.)

Laspeyre's and Paasche's do NOT satisfy this test. Fisher's DOES.

### Factor Reversal Test
```
P₀₁ × Q₀₁ = V₀₁ = Σ(P₁Q₁) / Σ(P₀Q₀)
```
Only Fisher's satisfies both tests — hence "ideal."

---

## 7. Worked Example 1 — Simple Aggregative Method

**Problem:** Calculate index for 1995 (base 1991):

| Commodity | Unit    | P₀ (1991) | P₁ (1995) |
|-----------|---------|-----------|-----------|
| A         | Kg      | 2.50      | 4.00      |
| B         | Dozen   | 5.40      | 7.20      |
| C         | Metre   | 6.00      | 7.00      |
| D         | Quintal | 150.00    | 200.00    |
| E         | Litre   | 2.50      | 3.00      |
| **Total** |         | **166.40**| **221.20**|

```
P₀₁ = (221.20 / 166.40) × 100 = 132.93
```
**Prices increased by 32.93% from 1991 to 1995.**

---

## 8. Worked Example 2 — Laspeyre's, Paasche's and Fisher's

**Problem:** Compute price index numbers:

| Commodity | P₀ | P₁ | Q₀ | Q₁ |
|-----------|----|----|----|----|
| A         | 2  | 4  | 8  | 6  |
| B         | 5  | 6  | 10 | 8  |
| C         | 4  | 5  | 14 | 10 |
| D         | 2  | 2  | 19 | 13 |

**Calculations:**

| Item | P₀Q₀ | P₁Q₀ | P₀Q₁ | P₁Q₁ |
|------|------|------|------|------|
| A    | 16   | 32   | 12   | 24   |
| B    | 50   | 60   | 40   | 48   |
| C    | 56   | 70   | 40   | 50   |
| D    | 38   | 38   | 26   | 26   |
| **Σ**| **160** | **200** | **118** | **148** |

**Laspeyre's:**
```
P₀₁ = (200/160) × 100 = 125
```

**Paasche's:**
```
P₀₁ = (148/118) × 100 = 125.42
```

**Fisher's:**
```
P₀₁ = √(125 × 125.42) = √15677.5 = 125.21
```

---

## 9. Consumer Price Index (CPI)

Also called **Cost of Living Index**. Measures change in cost of living for a specific group of people.

### Steps to Construct CPI:
1. Define the class of people (workers, teachers, etc.)
2. Conduct family budget enquiry — find spending patterns
3. Collect retail prices for commodities
4. Group commodities: Food, Clothing, Fuel & Lighting, House Rent, Miscellaneous

### Method 1 — Aggregate Expenditure Method:
```
CPI = [Σ(P₁Q₀) / Σ(P₀Q₀)] × 100
```

### Method 2 — Family Budget Method (Weighted Average of Relatives):
```
CPI = ΣPV / ΣV

where P = (P₁/P₀) × 100  and  V = P₀Q₀
```
Both methods give the **same result**.

---

## 10. Worked Example 3 — CPI

**Problem:** Construct CPI for 2007 (base 2006):

| Group | P₀ | P₁ | Q₀ | P₀Q₀ (V) | P₁Q₀ | P=(P₁/P₀)×100 | PV |
|-------|----|----|----|----|------|---|---|
| Food  | 200| 250| 40 | 8000 | 10000 | 125 | 1000000 |
| Clothing | 150 | 175 | 20 | 3000 | 3500 | 116.7 | 350100 |
| Fuel  | 50 | 60 | 30 | 1500 | 1800 | 120 | 180000 |
| Rent  | 300| 330| 10 | 3000 | 3300 | 110 | 330000 |
| Misc. | 100| 120| 25 | 2500 | 3000 | 120 | 300000 |
| **Σ** | | | | **18000** | **21600** | | **2160100** |

**Method 1:**
```
CPI = (21600/18000) × 100 = 120
```

**Method 2:**
```
CPI = 2160100/18000 = 120
```

**Real Wage calculation:**
If money wage in 2007 = Ksh 24,000:
```
Real Wage = (24000/120) × 100 = Ksh 20,000
```
The worker's purchasing power is equivalent to Ksh 20,000 in 2006 terms.

---

## 11. Quantity Index Numbers

### Laspeyre's Quantity Index (base year prices as weights):
```
Q₀₁ = [Σ(Q₁P₀) / Σ(Q₀P₀)] × 100
```

### Paasche's Quantity Index (current year prices as weights):
```
Q₀₁ = [Σ(Q₁P₁) / Σ(Q₀P₁)] × 100
```

### Fisher's Quantity Index:
```
Q₀₁ = √(Laspeyre's Q × Paasche's Q)
```

---

## 12. Limitations of Index Numbers

1. Based on samples — cannot include every item
2. Errors introduced at every stage (selection, weighting, formula)
3. No single formula is perfect — all have some bias
4. Laspeyre's has upward bias; Paasche's has downward bias
5. Quality changes over time are not captured
6. Misuse for purposes other than intended gives unreliable conclusions

---

## 13. WPI vs CPI

| Feature | WPI (Wholesale Price Index) | CPI (Consumer Price Index) |
|---|---|---|
| Measures | Price changes in economy as a whole | Cost of living for a specific group |
| Prices used | Wholesale prices | Retail prices |
| Scope | National | Local/specific group |
| Retail prices | Rise faster than wholesale | Includes retail markup |

---

## 14. Practice Questions

**Q1.** Calculate Laspeyre's, Paasche's and Fisher's index for the following:

| Item | P₀ | P₁ | Q₀ | Q₁ |
|------|----|----|----|----|
| Rice | 10 | 15 | 50 | 60 |
| Wheat| 8  | 10 | 40 | 50 |
| Oil  | 20 | 28 | 30 | 25 |
| Sugar| 12 | 15 | 20 | 22 |

**Q2.** A worker earned Ksh 15,000 in 2020. CPI in 2025 = 145. What is the real wage in 2025 terms?

**Q3.** Explain why Fisher's index is called the "ideal" index number.

**Q4.** Distinguish between fixed base and chain base methods of constructing index numbers.

**Q5.** The following data relates to a family's expenditure:

| Item | Weight | Price Relative |
|------|--------|----------------|
| Food | 40     | 125            |
| Clothing | 15 | 110            |
| Fuel | 10     | 130            |
| Rent | 20     | 105            |
| Misc.| 15     | 115            |

Calculate the weighted average price index.

> **Solution Q5:**
> Index = Σ(W × P) / ΣW = (40×125 + 15×110 + 10×130 + 20×105 + 15×115) / 100
> = (5000 + 1650 + 1300 + 2100 + 1725) / 100 = 11775/100 = **117.75**
