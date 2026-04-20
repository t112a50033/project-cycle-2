# Project Cycle 2 - One-Sample Inference

## Group Information
- Group Number: 4
- Members:
  - 王靖慈 112A50033 (Github ID: t112a50033,Emma2242)
  - 許皓崴 112370236 (Github ID: tymfmjs6qr-bot)
  - 黃靖容 113370211 (Github ID: annie12261-pixel)

## Dataset
- Dataset: YRBS_2007.csv

## Variables
- Behavior Variable: SadOrHopeless  
- Continuous Variable: BMIPCT  

## Benchmark Values
- Proportion benchmark: p0 = 0.30  
- Mean benchmark: μ0 = 65  

## Research Questions
1. Is the proportion of students who feel sad or hopeless different from 0.30?  
2. Is the mean BMI percentile different from 65?  
3. Do students with higher BMI percentile tend to report feeling sad or hopeless more often?  

## Methods
- Proportion analysis:
  - Sample proportion
  - Confidence interval
  - One-sample z-test

- Mean analysis:
  - Sample mean
  - Confidence interval
  - One-sample t-test

- Additional analysis:
  - BMI grouping (Low, Medium, High)
  - Chi-square test of independence

## Key Results
- Sample proportion ≈ 0.30  
- 95% CI for proportion: (0.2923, 0.3076)  
- p-value ≈ 0.9926  

- Sample mean ≈ 64.82  
- 95% CI for mean: (64.35, 65.29)  
- p-value ≈ 0.4564  

- Chi-square test:
  - p-value ≈ 0.0615  

## Conclusion
The proportion of students feeling sad or hopeless is very close to the benchmark value of 0.30, and there is no significant difference based on the hypothesis test.

The mean BMI percentile is also close to 65, and the test shows no significant difference.

Although EDA suggests a slight increase in sadness with higher BMI groups, the chi-square test does not show strong statistical evidence of an association.

Overall, the inferential results are consistent with the EDA findings.