# TOPIC 3: ELEMENTARY STATISTICS — DATA ORGANIZATION AND PRESENTATION
## BSC7124 Apply Maths for Economics — Exhaustive Notes

---

## 1. Types of Data

### Discrete Data
- **Counted** data
- Cannot have decimals/fractions
- Examples: number of students, cars, animals, defects

### Continuous Data
- **Measured** data
- Can have decimals/fractions
- Examples: height, weight, temperature, time, marks, distance, volume

---

## 2. Methods of Data Collection

### Primary Data
Collected directly by the researcher:
- Interviews (personal, telephone)
- Questionnaires
- Observation
- Experiments

### Secondary Data
Already collected by someone else:
- Government publications
- Company records
- Journals and newspapers
- Internet databases

---

## 3. Sampling Techniques

| Technique | Description |
|---|---|
| Simple Random | Every member has equal chance of selection |
| Systematic | Select every kth item from a list |
| Stratified | Divide into groups (strata), sample from each |
| Cluster | Divide into clusters, randomly select whole clusters |
| Convenience | Select whoever is easily available |

---

## 4. Types of Classes in Frequency Distribution

### Inclusive Classes (used for discrete data):
```
0 – 9
10 – 19
20 – 29
```
The upper limit of one class does NOT equal the lower limit of the next.

### Exclusive Classes (used for continuous data):
```
0 – 10
10 – 20
20 – 30
```
The upper limit of one class equals the lower limit of the next.

---

## 5. Constructing a Frequency Distribution Table

### Step 1: Find the Range
```
Range = Maximum value - Minimum value
```

### Step 2: Determine Number of Classes (Sturges Rule)
```
k = 1 + 3.322 log N
```
Where N = total number of observations. Round k to the nearest whole number.

### Step 3: Calculate Class Width
```
h = Range / k
```
Round up to a convenient number.

### Step 4: Set Up Classes
Start from a value at or below the minimum. List all classes, then tally and count frequencies.

---

## 6. Worked Example — Frequency Distribution

**Data:** 200 observations, minimum = 10, maximum = 98

**Step 1:** Range = 98 - 10 = 88

**Step 2:** k = 1 + 3.322 log(200) = 1 + 3.322 × 2.301 = 1 + 7.644 = 8.644 ≈ **9 classes**

**Step 3:** h = 88/9 = 9.78 ≈ **10** (rounded up)

**Frequency Distribution Table:**

| Class   | Frequency | Midpoint |
|---------|-----------|----------|
| 10–20   | 38        | 15       |
| 20–30   | 69        | 25       |
| 30–40   | 41        | 35       |
| 40–50   | 25        | 45       |
| 50–60   | 9         | 55       |
| 60–70   | 5         | 65       |
| 70–80   | 5         | 75       |
| 80–90   | 5         | 85       |
| 90–100  | 3         | 95       |
| **Total** | **200** |          |

---

## 7. Cumulative Frequency Table

| Class  | Freq | Less Than CF | More Than CF |
|--------|------|-------------|--------------|
| 10–20  | 38   | 38          | 200          |
| 20–30  | 69   | 107         | 162          |
| 30–40  | 41   | 148         | 93           |
| 40–50  | 25   | 173         | 52           |
| 50–60  | 9    | 182         | 27           |
| 60–70  | 5    | 187         | 18           |
| 70–80  | 5    | 192         | 13           |
| 80–90  | 5    | 197         | 8            |
| 90–100 | 3    | 200         | 3            |

---

## 8. Graphical Representation

### Histogram
- Bar chart where bars touch (no gaps)
- X-axis: class boundaries
- Y-axis: frequency
- Area of each bar = frequency

### Frequency Polygon
- Connect midpoints of the tops of histogram bars with straight lines
- Extend to the midpoints of the empty classes on each end (so the polygon closes at the x-axis)

### Ogive (Cumulative Frequency Curve)

**Less Than Ogive:**
- Plot (upper class boundary, less than CF)
- Curve rises from left to right

**More Than Ogive:**
- Plot (lower class boundary, more than CF)
- Curve falls from left to right

**Reading Quartiles from Ogive:**

Using the less than ogive with N = 200:
```
Q1: at CF = N/4 = 50   → read x-axis
Q2 (Median): at CF = N/2 = 100  → read x-axis
Q3: at CF = 3N/4 = 150  → read x-axis

IQR = Q3 - Q1
```

From the example above:
- Q1 ≈ 22 (at CF = 50)
- Median ≈ 27 (at CF = 100)
- Q3 ≈ 37 (at CF = 150)
- IQR ≈ 37 - 22 = **15**

---

## 9. Relative Frequency and Percentage Frequency

```
Relative Frequency = f / N
Percentage Frequency = (f / N) × 100
```

---

## 10. Class Mark (Midpoint)

```
Midpoint = (Lower class limit + Upper class limit) / 2
```

---

## 11. Practice Questions

**Q1.** The following are marks scored by 50 students:
42, 55, 68, 31, 74, 49, 63, 57, 38, 72, 45, 61, 53, 29, 66, 48, 70, 36, 58, 44,
52, 67, 39, 75, 47, 60, 34, 71, 56, 43, 65, 50, 37, 73, 46, 59, 33, 69, 54, 41,
64, 48, 76, 35, 62, 51, 40, 68, 44, 57

(a) Using Sturges Rule, determine the number of classes and class width
(b) Construct a frequency distribution table (exclusive classes)
(c) Draw a less than and more than ogive
(d) Estimate Q1, Median, Q3 and IQR from the ogive

**Q2.** Distinguish between:
(a) Discrete and continuous data — give 3 examples of each
(b) Inclusive and exclusive class intervals
(c) Less than and more than ogive

**Q3.** From the frequency distribution in Q1:
(a) Construct a relative frequency table
(b) Draw a histogram and frequency polygon
(c) What percentage of students scored between 50 and 70?

---

## 12. Key Points to Remember

1. Sturges Rule gives the **number of classes**, not the class width
2. Class width is always **rounded up**, never down
3. For exclusive classes, the upper boundary of one class = lower boundary of the next
4. The two ogives intersect at the **median**
5. Histogram bars **touch** — no gaps (unlike bar charts)
6. Frequency polygon must **close** at both ends on the x-axis
