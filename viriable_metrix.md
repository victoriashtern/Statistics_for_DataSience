# Variability Metrics Example (Single Dataset Walkthrough)

## Data Sequence
X = [2, 4, 6, 8, 10]

Mean = 6

---

## Step-by-Step Variability Measures

### Deviations
Difference from the mean:

- 2 − 6 = -4  
- 4 − 6 = -2  
- 6 − 6 = 0  
- 8 − 6 = 2  
- 10 − 6 = 4  

**Deviations = [-4, -2, 0, 2, 4]**

---

### Variance
Squared deviations:

- 16, 4, 0, 4, 16  

Sum = 40  
Variance = 40 / (5 − 1) = **10**

---

### Standard Deviation
√Variance = √10 = **3.16**

---

### Mean Absolute Deviation (MAD)
Absolute deviations:

- 4, 2, 0, 2, 4  

MAD = (4 + 2 + 0 + 2 + 4) / 5 = **2.4**

---

### Median Absolute Deviation (from median)
Median = 6

Absolute deviations:

- 4, 2, 0, 2, 4  

Sorted: [0, 2, 2, 4, 4]  
Median = **2**

---

### Range
Max − Min = 10 − 2 = **8**

---

### Order Statistics (Sorted Data)
Sorted X = [2, 4, 6, 8, 10]

- 1st = 2  
- 2nd = 4  
- 3rd = 6  
- 4th = 8  
- 5th = 10  

---

### Percentiles
From sorted data:

- 25th percentile (Q1) = 4  
- 50th percentile (Median) = 6  
- 75th percentile (Q3) = 8  

---

### Interquartile Range (IQR)
IQR = Q3 − Q1 = 8 − 4 = **4**
---

# Key Terms for Variability Metrics

| Term | Definition | Synonyms | Example |
|---|---|---|---|
| **Deviations** | The difference between observed values and an estimate of location. | errors, residuals | Data: 5, 7, mean = 6 → deviations = -1, +1 |
| **Variance** | The sum of squared deviations from the mean divided by (n − 1). | mean-squared-error | Data: 2, 4, 6 → variance = 4 |
| **Standard deviation** | The square root of the variance. | — | If variance = 9 → SD = 3 |
| **Mean absolute deviation** | Mean of absolute deviations from the mean. | l1-norm, Manhattan norm | Data: 2, 4, 6 → MAD = 1.33 |
| **Median absolute deviation from median** | Median of absolute deviations from the median. | — | Data: 1, 2, 3, 100 → MAD ≈ 1 |
| **Range** | Difference between max and min values. | — | Data: 3, 5, 9 → range = 6 |
| **Order statistics** | Metrics based on sorted data values. | ranks | Data: 10, 2, 7 → sorted: 2, 7, 10 |
| **Percentile** | Value below which P% of data lies. | quantile | 90th percentile of scores = 88 |
| **Interquartile range (IQR)** | Difference between 75th and 25th percentiles. | IQR | Q3 = 80, Q1 = 60 → IQR = 20 |
