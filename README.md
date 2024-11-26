# Statistical Hypothesis Testing Project

This repository demonstrates the application of various **statistical hypothesis tests** using Python. The goal is to provide a practical understanding of different tests used in data analysis, and how to apply them using libraries such as **SciPy** and **NumPy**.

The tests covered include:

- **T-Test** (One-Sample, Two-Sample)
- **ANOVA**
- **Chi-Square Test**
- **Pearson's Correlation Coefficient**
- **Mann-Whitney U Test**

## Overview of Tests Covered

### 1. **T-Test (One - Sample and Two - Sample)**
- **Purpose**: Compare the sample mean to the population mean (one-sample t-test) or compare the means of two independent groups (two-sample t-test).
- **Example**: Testing whether the average mass of a group of objects differs from 10g, or comparing the mass of objects in two different conditions (upwind vs downwind).
- **Key Concepts**: T-Statistic, P-Value.

### 2. **ANOVA (Analysis of Variance)**
- **Purpose**: Compare the means of three or more groups.
- **Example**: Testing if there is a significant difference in the mean marks between three different sections.
- **Key Concepts**: F-Statistic, P-Value.

### 3. **Chi-Square Test**
- **Purpose**: Test the independence of two categorical variables.
- **Example**: Testing if gender is associated with product preference.
- **Key Concepts**: Chi-Square Statistic, P-Value, Contingency Table.

### 4. **Pearson's Correlation Coefficient**
- **Purpose**: Test the strength and direction of the linear relationship between two continuous variables.
- **Example**: Testing the correlation between exam scores in two subjects.
- **Key Concepts**: Correlation Coefficient, P-Value.

### 5. **Mann-Whitney U Test**
- **Purpose**: Compare the medians of two independent groups when the data is not normally distributed.
- **Example**: Comparing the test scores of students from two different schools.
- **Key Concepts**: U-Statistic, P-Value.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/HunarAgrawal/Common_Statistical_Tests.git
   cd Common_Statistical_Tests

2. **Install required libraries**:
   ```bash
   pip install scipy numpy

---

## Usage

1. **Run the script**:
    ```bash
    python analysis.py

2. **View the Results**:
- The T-statistics, p-values, and conclusion statements for each test will be printed in the console.

---

## File Descriptions

- analysis.py: Main script containing all the statistical hypothesis tests.
- data/: (Optional) Folder to store any input datasets (if applicable).

---

## Dependencies

- Python 3.7 or higher
- Libraries: scipy, numpy

---
## Contributing

Contributions are welcome! If you have suggestions, improvements, or bugs to fix, feel free to fork the repository, make changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more information.

---

## Author

Hunar Agrawal

---

## Acknowledgements

- SciPy Documentation
- Python Libraries: SciPy, NumPy
