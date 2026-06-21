
## Data Types
---

| Type | Description | Example Variables | Example Dataset Values |
|------|-------------|------------------|------------------------|
| Categorical | Non-numeric data grouped into categories | Gender, department | Male / Female |
| Nominal | Categories with no inherent order | Blood type, nationality | A, B, O, AB |
| Ordinal | Categories with meaningful order | Satisfaction level, class rank | Poor, Fair, Good |
| Binary | Only two possible categories | Pass/fail, yes/no | Yes/No, 1/0 |
| Numerical | Numeric data representing counts or measurements | Height, income | 150, 200 |
| Discrete | Countable numeric values | Number of students | 0, 1, 2 |
| Continuous | Measurable values within a range | Weight, speed | 52.4, 61.8 |
| Interval | Equal intervals but no true zero | Temperature (°C), IQ | 10°C, 20°C |
| Ratio | Equal intervals with a true zero | Height, salary | 150 cm, $5000 |
| Cross-sectional | Data collected at one point in time | Population survey | Income data in 2026 |
| Time-series | Data collected over time | Monthly sales | Jan: 500, Feb: 620 |
| Panel (Longitudinal) | Repeated observations over time for same subjects | Patient tracking | BP across 5 years |


## 📚 Foundations: Central Tendency & Robustness
---

| Term | Definition | Synonym | Example |
|---|---|---|---|
| **Count** | The number of observations or data points in a dataset. | sample size (n) | Data: 2, 4, 6, 8 → count = 4 |
| **Interquartile Range (IQR)** | The difference between the 75th percentile (Q3) and 25th percentile (Q1). | middle spread | Q1 = 2, Q3 = 10 → IQR = 8 |
| **Mean** | The sum of all values divided by the number of values. | average | (2 + 4 + 6 + 8) / 4 = 5 |
| **Median** | The value such that half of the data lies above and half below. | 50th percentile | 2, 4, 6, 8, 10 → median = 6 |
| **Mode** | The value that appears most frequently in a dataset. | most frequent value | 2, 2, 3, 4, 4, 4 → mode = 4 |
| **Outlier** | A data value far away from most other values. | extreme value | 40k, 42k, 45k, 1M → 1M is an outlier |
| **Percentile** | The value such that P percent of the data lies below it. | quantile | 90th percentile of test scores = 88 |
| **Robust** | Not sensitive to extreme values. | resistant | Median income stays stable even with an extreme salary |
| **Trimmed Mean** | Mean after removing extreme values from both ends. | truncated mean | Remove 1 and 100 → mean of remaining data |
| **Weighted Mean** | Mean where values have different importance (weights). | weighted average | (80×2 + 90×3) / (2 + 3) = 86 |
| **Weighted Median** | Value where half of total weight lies above and below. | — | Values (10,20,30), weights (1,2,3) → 20 |

---

## 1. Central Tendency (Center)

- **Mean** = average = Σx / n → sensitive to outliers  
- **Weighted Mean** = Σwx / Σw  
- **Median** = middle value → robust to outliers  
- **Mode** = most frequent value  


## 2. Position (Location)

- **Percentile (Pth)** = P% of data lies below this value  
- **Quartiles** = Q1 (25%), Q2 (50%), Q3 (75%)  
- **Deciles** = data split into 10 equal parts  

## 3. Spread (Dispersion)

- **Range** = max − min → very sensitive to outliers  
- **Variance** = average squared deviation from mean  
- **Standard Deviation** = √variance  
- **IQR (Interquartile Range)** = Q3 − Q1 → robust measure  

## 4. Robust Statistics (Outlier-Resistant)

- **Median** = most robust measure of center  
- **Trimmed Mean** = mean after removing extreme values  
- **Winsorized Mean** = mean after capping extremes  
- **Weighted Median** = median with importance weights  

## 5. Shape of Distribution

- **Skewness** = asymmetry of distribution (left/right tail)  
- **Kurtosis** = tail heaviness / peakedness  

## 6. High-Yield Relationships

- Mean > Median → Right-skewed distribution  
- Mean < Median → Left-skewed distribution  
- Mean ≈ Median → Symmetric distribution  

## 7. Robustness Rule (VERY IMPORTANT)

- **Sensitive:** Mean, Range, Variance  
- **Robust:** Median, IQR, Trimmed Mean  

## 8. Quick Memory Map

- **Center** → Mean, Median, Mode  
- **Position** → Percentiles, Quartiles  
- **Spread** → Variance, Standard Deviation, IQR  
- **Robust** → Median, IQR, Trimmed Mean  
- **Shape** → Skewness, Kurtosis  

---
## 📌  Summary

- **Center:** Mean, Median, Mode  
- **Spread:** IQR, Count  
- **Robust measures:** Median, IQR, Trimmed Mean  
- **Outliers:** Extreme values that distort mean-based statistics  
- Mean is **sensitive** to outliers  
- Median and IQR are **robust**  
- Weighted measures handle **importance differences**  








