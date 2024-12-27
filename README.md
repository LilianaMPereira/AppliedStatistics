# Applied Statistics Project

This repository contains a series of projects and tasks demonstrating the application of statistical methods using Python. It includes implementations of hypothesis testing, statistical modeling, and visualization techniques. The repository is divided into two main sections: **Tasks** and **Project**.

---

## **Table of Contents**

1. [Introduction](#introduction)
2. [File Structure](#file-structure)
3. [Tasks.ipynb](#tasksipynb)
   - [Task 1: Permutations and Combinations](#task-1-permutations-and-combinations)
   - [Task 2: Numpy's Normal Distribution](#task-2-numpys-normal-distribution)
   - [Task 3: t-Test Calculation](#task-3-t-test-calculation)
   - [Task 4: ANOVA Simulation](#task-4-anova-simulation)
4. [Project.ipynb](#projectipynb)
   - [PlantGrowth Dataset Analysis](#plantgrowth-dataset-analysis)
5. [Conclusion](#conclusion)
6. [References](#references)

---

## **Introduction**

This repository showcases statistical techniques applied to real-world problems. The **Tasks.ipynb** introduces foundational statistical concepts through engaging examples, while the **Project.ipynb** focuses on an in-depth analysis of the PlantGrowth dataset using hypothesis testing and visualization.

---

## **File Structure**

- **`Tasks.ipynb`**: Contains four distinct tasks demonstrating statistical concepts like permutations, normal distribution, t-tests, and ANOVA simulations.
- **`Project.ipynb`**: A detailed analysis of the PlantGrowth dataset, covering hypothesis testing with t-tests and ANOVA.
- **`README.md`**: Documentation explaining the purpose, structure, and contents of the repository.

---

## **Tasks.ipynb**

### **Task 1: Permutations and Combinations**

#### **Problem Statement**
Inspired by the "Lady Tasting Tea" experiment, this task evaluates the likelihood of success through random guessing in a setup involving 12 cups of tea. The experiment calculates the probabilities of:
- Selecting exactly 6 correct cups.
- Selecting at least 5 correct cups.
- Selecting at least 4 correct cups.

#### **Techniques**
- Mathematical setup using combinations.
- Probability calculations for various scenarios.
- Visualization of results using bar charts.

---

### **Task 2: Numpy's Normal Distribution**

#### **Problem Statement**
This task validates the functionality of `numpy.random.normal()` to generate normally distributed values. Key steps include:
- Generating a large dataset with specified mean and standard deviation.
- Testing the normality using the Shapiro-Wilk test.
- Visualizing the distribution with histograms and probability density functions (PDF).

#### **Techniques**
- Data generation with NumPy.
- Statistical validation using SciPy.
- Visualization with Matplotlib and Seaborn.

---

### **Task 3: t-Test Calculation**

#### **Problem Statement**
This task involves calculating the t-statistic manually and comparing it with `scipy.stats.ttest_rel`. A dataset of resting heart rates before and after a two-week exercise program is analyzed to determine if the program had a significant effect.

#### **Techniques**
- Manual computation of the t-statistic.
- Validation using a built-in paired t-test function.
- Visualization of differences through histograms and paired data charts.

---

### **Task 4: ANOVA Simulation**

#### **Problem Statement**
A simulation to estimate the probability of Type II errors in a one-way ANOVA test. The goal is to:
- Generate samples with specified means and standard deviation.
- Perform 10,000 ANOVA tests to evaluate the robustness of the method.

#### **Techniques**
- Simulation of data using NumPy.
- ANOVA testing with SciPy.
- Visualization of p-values and sample means.

---

## **Project.ipynb**

### **PlantGrowth Dataset Analysis**

#### **Problem Statement**
An in-depth analysis of the PlantGrowth dataset, which contains observations on the dried weights of plants under three different conditions (control, treatment 1, and treatment 2). The project involves:
- Statistical testing to determine significant differences between groups.
- Validation of assumptions for hypothesis testing.
- Visualization of distributions and group comparisons.

#### **Highlights**
1. **Exploratory Data Analysis (EDA)**:
   - Boxplots, histograms, and density plots to explore distributions.
   - Summary statistics for descriptive insights.

2. **Statistical Tests**:
   - **t-Test**: Comparison of treatment groups to determine if the mean weights differ significantly.
   - **ANOVA**: Testing whether at least one group mean differs from the others.

3. **Post-Hoc Analysis**:
   - Tukey's Honestly Significant Difference (HSD) test to identify specific group differences after ANOVA.

4. **Conclusions**:
   - Interpretation of results with respect to experimental conditions and treatment effects.

---

## **Conclusion**

This repository provides a comprehensive guide to applying statistical methods in Python. It includes foundational exercises, simulations, and an in-depth project analysis. Through a combination of mathematical rigor and visualization, it equips users with the tools to perform robust statistical analyses.

---

## References

A list of references used throughout the notebook for further reading and understanding.

---

This README is a part of the "Applied Statistics" project.

## Contact

For any inquiries or collaboration opportunities, please contact g00411560@atu.ie

Thank you :)

