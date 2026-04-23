[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=00C2FF&center=true&vCenter=true&width=700&lines=NTUT+Statistics(II)+Practice;Project+Cycle+2;SadOrHopeless+%26+BMI+Analysis;One-Sample+Inference+%26+Chi-Square+Test)](https://git.io/typing-svg)

<h1 align="center">📊 Project Cycle 2 - One-Sample Inference</h1>

<p align="center">
  <b>NTUT Industrial Engineering & Management</b><br>
  Statistical Analysis Project
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue">
  <img src="https://img.shields.io/badge/Statistics-Inference-orange">
  <img src="https://img.shields.io/badge/Status-Completed-green">
</p>

---

## 👥 Group Information
- **Group Number:** 5
- **Members:**
  - 王靖慈 112A50033 (Github ID: t112a50033, Emma2242)
  - 許皓崴 112370236 (Github ID: tymfmjs6qr-bot)
  - 黃靖容 113370211 (Github ID: annie12261-pixel)

---

## 📁 Dataset
- **Dataset:** YRBS_2007.csv  

---

## 🔍 Variables

| Type | Variable | Description |
|------|--------|------------|
| Behavior | SadOrHopeless | Feeling sad or hopeless |
| Continuous | BMIPCT | BMI percentile |

---

## 🎯 Benchmark Values

| Analysis | Benchmark |
|--------|----------|
| Proportion | p₀ = 0.30 |
| Mean | μ₀ = 65 |

---

## ❓ Research Questions

1. Is the proportion of students who feel sad or hopeless different from 0.30?  
2. Is the mean BMI percentile different from 65?  
3. Do students with higher BMI percentile tend to report feeling sad or hopeless more often?  

---

## 🔄 Project Workflow

![Workflow](https://img.shields.io/badge/Flow-Data→EDA→Inference→Conclusion-blue)

---

## 🧪 Methods

### One-Sample Inference
- Sample proportion (p̂)
- Confidence interval
- One-sample z-test  

### Mean Analysis
- Sample mean (x̄)
- Confidence interval
- One-sample t-test  

### Additional Analysis
- BMI grouping (Low / Medium / High)
- Chi-square test of independence  

---

## 📊 Key Results

### Proportion (SadOrHopeless)
- p̂ ≈ **0.30**  
- 95% CI: **(0.2923, 0.3076)**  
- p-value ≈ **0.9926**  

👉 No significant difference  

---

### Mean (BMIPCT)
- x̄ ≈ **64.82**  
- 95% CI: **(64.35, 65.29)**  
- p-value ≈ **0.4564**  

👉 No significant difference  

---

### Chi-square Test
- p-value ≈ **0.0615**

👉 No significant association  

---

## 🧾 Conclusion

The proportion of students feeling sad or hopeless is very close to 0.30, and no significant difference is found.

The mean BMI percentile is also close to 65, with no significant difference.

Although EDA suggests a slight trend, statistical tests do not confirm a strong relationship.

---

## 🗂️ Project Structure

    project-cycle-2/
    ├── data/
    │   ├── raw/
    |   |   └── YRBS_2007.csv
    │   └── processed/
    |       ├── bmi_cleaned.csv
    |       ├── joint_cleaned.csv
    |       └── sad_cleaned.csv
    ├── notebooks/
    │   ├── 01_data_check.ipynb
    │   ├── 02_EDA.ipynb
    │   └── 03_inference.ipynb
    ├── outputs/
    │   ├── figures/
    |   |   ├── bmi_boxplot.png
    |   |   ├── bmi_group_bar.png
    |   |   ├── bmi_histogram.png
    |   |   └── sad_bar_chart.png
    │   ├── summary/
    |   |   └── final_summary.txt
    │   └── tables/
    |       └── bmi_group_summary.cvs
    ├── report/
    |   └── one_page_summary.pdf
    ├── references/
    │   ├── variable_definitions.md
    │   ├── recoding_rules.md
    |   └── benchmark_values.md
    └── README.md

---

## 📌 Notes
- Workflow: Question → Data → EDA → Inference → Conclusion  
- Data is kept reproducible and structured  