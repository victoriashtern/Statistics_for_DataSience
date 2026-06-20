# Statistics_for_DataSience
Describes main statistic concepts


# Data Types

## Data Types Overview

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



# Key Terms for Rectangular Data

| Term | Definition | Synonyms |
|---|---|---|
| **Data frame** | Rectangular data (like a spreadsheet) is the basic data structure for statistical and machine learning models. | — |
| **Feature** | A column within a table is commonly referred to as a feature. | attribute, input, predictor, variable |
| **Outcome** | The variable being predicted in a study or machine learning problem, often a yes/no result. | dependent variable, response, target, output |
| **Records** | A row within a table is commonly referred to as a record. | case, example, instance, observation, pattern, sample |



# Key Statistical Terms (Measures of Center & Robustness)

| Term | Definition | Synonym | Example |
|---|---|---|---|
| **Mean** | The sum of all values divided by the number of values. | average | (2 + 4 + 6 + 8) / 4 = 5 |
| **Weighted mean** | The sum of all values multiplied by their weights divided by the sum of the weights. | weighted average | (80×2 + 90×3) / (2 + 3) = 86 |
| **Median** | The value such that half of the data lies above and half below. | 50th percentile | 2, 4, 6, 8, 10 → median = 6 |
| **Percentile** | The value such that P percent of the data lies below it. | quantile | 90th percentile of test scores = 88 |
| **Weighted median** | The value such that half of the total weight lies above and half below the sorted data. | — | Values: (10, 20, 30) with weights (1, 2, 3) → weighted median = 20 |
| **Trimmed mean** | The mean after removing a fixed number of extreme values from both ends. | truncated mean | Data: 1, 2, 3, 4, 100 → trimmed mean (remove 1 & 100) = 3 |
| **Robust** | Not sensitive to extreme values. | resistant | Median income remains stable even if one billionaire is added |
| **Outlier** | A data value that is very different from most of the data. | extreme value | Salaries: 40k, 42k, 45k, 1M → 1M is an outlier |


