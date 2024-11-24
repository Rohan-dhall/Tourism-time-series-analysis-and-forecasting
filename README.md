# Tourism Dataset Analysis

This repository contains an analysis of a tourism dataset comprising 5,989 records across 8 key columns. The dataset captures details about tourism locations, visitor statistics, ratings, and revenue, with records spanning from 2018 to 2023.

---

## Dataset Overview

### Columns Description:
1. **Location**: Unique identifier/name of the tourism location.
2. **Country**: The country where the location is situated (7 unique countries).
3. **Category**: Type of tourism (6 unique categories: Cultural, Historical, Adventure, Nature, Shopping, Recreational).
4. **Visitors**: Number of visitors to the location (range: 1,108 - 999,982, average: ~501,016).
5. **Rating**: Average rating of the location (scale: 1.0 - 5.0, average: ~3.01).
6. **Revenue**: Revenue generated in an unspecified currency (range: 1,025.81 - 999,999.49, average: ~499,479.37).
7. **Accommodation_Available**: Indicates whether accommodations are available ("Yes" or "No").
8. **Date**: Date of record in YYYY-MM-DD format (2,066 unique dates, spanning 2018-2023).

---

## Initial Observations

- **Visitors**: Broad range of visitor counts with a slight concentration around 500,000. Some locations exhibit exceptionally high visitor counts, resulting in a long tail.
- **Rating**: Average rating of 3.01 with a standard deviation of 1.16, indicating a wide spread. Few locations achieve a perfect rating of 5.0.
- **Revenue**: Wide range of revenue values with peaks near the median (~500,000). Some locations generate extremely high revenue, while others are significantly lower.
- **Categorical Data**:
  - **Accommodation_Available**: 3,013 records have accommodations ("Yes"), while 2,976 do not ("No").
  - **Country**: Egypt has the most records (912), followed by others.
  - **Category**: Adventure is the most frequent category (1,037 records).
- **Date**: Data spans over 5 years, with the highest frequency on October 7, 2023 (11 records).

---

## Key Findings from Visualizations

### 1. Distribution of Numerical Variables
- **Visitors**: A relatively uniform distribution with a slight concentration around the median (~500,000 visitors). The presence of high outliers results in a long tail.
- **Rating**: Near-normal distribution centered around 3.0 with a slight left skew.
- **Revenue**: Significant variation with peaks near the median (~500,000). Presence of both low-revenue entries and high-revenue outliers.

### 2. Revenue by Category
- **Cultural and Historical Categories**: Higher median revenue, suggesting greater popularity or revenue potential.
- **Adventure and Nature Categories**: Broader revenue distribution, with notable high-revenue outliers.
- **Shopping and Recreational Categories**: Lower median revenue but more consistent results.

### 3. Visitors by Country
- **India and China**: Locations in these countries attract significantly more visitors on average.
- **Australia and Egypt**: Lower variability in visitor numbers, indicating stable tourism patterns.

---

## Usage

### For Analysts:
This dataset is ideal for exploring trends in tourism, revenue generation, and visitor behaviors across different locations and categories. It can also be used to identify patterns in tourist accommodations and ratings.

### For Developers:
The dataset can serve as a benchmark for machine learning models focusing on predictive analytics, such as:
- Predicting revenue based on visitor counts and ratings.
- Analyzing the impact of accommodation availability on tourism revenue.

---

## Future Work
- Detailed country-wise analysis to identify seasonal trends.
- Regression models to predict revenue based on other variables.
- Clustering analysis to group similar locations based on visitor patterns and revenue.

---

## License
This repository is licensed under the MIT License. See the `LICENSE` file for more information.

---

## Acknowledgments
Thanks to all contributors and stakeholders who helped gather, clean, and analyze the data.

---

## Contact
For questions or suggestions, please open an issue or contact [Your Name/Organization] via [your-email@example.com].
