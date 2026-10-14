# Adverse-Drug-Reaction-ADR-Data-analysis-by-Excel
Excel-based Adverse Drug Reaction (ADR) Data Analysis project using a synthetic healthcare dataset of 80 patients and 10 drugs. Analysed ADR rates, reaction severity, causality, age groups, and risk factors using Excel formulas, PivotTables, conditional formatting, and charts to identify patterns and visualize pharmacovigilance data.

## 📌 Project Overview

This project focuses on **Adverse Drug Reaction (ADR) Data Analysis using Microsoft Excel** to explore patient information, medication usage, adverse reactions, severity levels, and potential risk factors.

The project demonstrates how Excel can be used for healthcare data cleaning, analysis, visualization, and pharmacovigilance reporting.

The analysis uses a synthetic dataset created for learning purposes. It does not contain real patient data.

## 🎯 Objectives

- Analyse patient symptoms and medication usage.
- Identify possible adverse drug reactions associated with medications.
- Calculate and compare ADR rates across different drugs.
- Assess the severity of reported adverse reactions.
- Explore potential risk factors, including age, gender, and concomitant drug use.
- Perform a simplified causality assessment using a Naranjo-style scoring approach.
- Create charts and visual summaries to communicate findings.

## 📊 Project Highlights

| Metric | Result |
|---|---:|
| Total Patients | 80 |
| Drugs Analysed | 10 |
| Reported ADR Cases | 26 |
| Overall ADR Rate | 32.5% |

## 🛠️ Tools and Techniques

**Tool:** Microsoft Excel

**Techniques used:**
- Data cleaning and structuring
- Excel filters and helper columns
- Excel formulas: `COUNTIFS`, `AVERAGEIFS`, `INDEX-MATCH`, `RANK`, and `IF`
- PivotTables and PivotCharts
- Conditional formatting and colour scales
- Drug-wise ADR rate calculation
- Severity and causality assessment
- Data visualization using charts and graphs

## 🔄 Project Workflow

### 1. Dataset Preparation

Prepared the patient and medication dataset containing information required for ADR analysis.

### 2. Data Cleaning and Structuring

Organized the dataset using Excel filters and helper columns to support accurate calculations and analysis.

### 3. Drug-wise ADR Analysis

Calculated ADR rates for the selected medications and categorized the results into high-, medium-, and low-risk groups based on the project's defined thresholds.

### 4. Drug–Reaction Matrix

Created a drug-versus-reaction matrix using PivotTables and conditional formatting to identify patterns between medications and reported reactions.

### 5. Risk Factor Analysis

Explored potential associations between ADRs and patient characteristics, including:
- Age group
- Gender
- Concomitant medication use

### 6. Causality Assessment and Visualization

Applied a simplified Naranjo-style scoring approach to classify suspected ADR cases and created charts to present the findings.

## 📈 Key Results

### 1. ADR Rate by Drug

The analysis identified the following medications with the highest observed ADR rates:

| Medication | ADR Rate | Project Risk Category |
|---|---:|---|
| Enalapril | 62.5% | High |
| Diclofenac | 50% | High |
| Atorvastatin | 50% | High |
| Warfarin | 50% | High |
| Amoxicillin | 25% | Medium |
| Metformin | 25% | Medium |
| Amlodipine | 25% | Medium |
| Ciprofloxacin | 25% | Medium |
| Omeprazole | 12.5% | Low |
| Paracetamol | 0% | Low |

*Risk categories are based on the thresholds defined for this project and should not be interpreted as established clinical risk classifications.*

### 2. Severity of Adverse Drug Reactions

| Severity | Cases | Percentage |
|---|---:|---:|
| Mild | 17 | 65% |
| Moderate | 7 | 27% |
| Severe | 2 | 8% |
| **Total** | **26** | **100%** |

Most recorded ADR cases were classified as mild, while two cases were classified as severe in the synthetic dataset.

The severe reactions recorded were:
- Diclofenac — gastrointestinal bleeding
- Metformin — lactic acidosis

### 3. Causality Assessment

The simplified Naranjo-style assessment produced the following results:

| Causality Category | Cases | Percentage |
|---|---:|---:|
| Probable | 17 | 65% |
| Possible | 9 | 35% |
| Unlikely | 0 | 0% |
| **Total** | **26** | **100%** |

The assessment classified most reported ADR cases as probable within the project's simplified scoring framework.

### 4. ADR Rate by Age Group

| Age Group | Patients | ADR Rate |
|---|---:|---:|
| Under 18 | 3 | 100% |
| 18–39 | 30 | 33% |
| 40–59 | 24 | 21% |
| 60+ | 23 | 35% |

The under-18 group had an observed ADR rate of 100%, based on only three patients. Therefore, this result should be interpreted cautiously.

### 5. Other Key Findings

- The most frequently recorded reactions were bruising associated with Warfarin and dry cough associated with Enalapril, with four cases each.
- Approximately 65% of the recorded ADR cases were classified as mild.
- The observed ADR rate was 37.1% among patients taking concomitant drugs, compared with 28.9% among those without concomitant drug use.
- The concomitant medication comparison is exploratory and does not establish a causal relationship.

## 📊 Visualizations

The project includes Excel charts and visual summaries covering:

- Drug-wise ADR rates and risk categories
- Severity distribution of ADR cases
- Causality assessment results
- ADR rates across age groups
- Drug–reaction patterns using a colour-coded matrix

These visualizations help communicate patterns in the dataset and support exploratory healthcare data analysis.

## 💡 Skills Demonstrated

- Healthcare Data Analysis
- Pharmacovigilance Fundamentals
- Data Cleaning and Preparation
- Microsoft Excel
- Excel Formulas and Functions
- PivotTables and PivotCharts
- Conditional Formatting
- Data Visualization
- Exploratory Data Analysis
- Interpretation of Healthcare Data

## ⚠️ Important Disclaimer

This project uses a **synthetic dataset created for educational purposes**. The results are illustrative and are not derived from real patients or validated clinical research.

The ADR rates and risk categories are specific to this dataset. They should not be used to make clinical decisions, determine the safety of medications, or establish causal relationships.

The simplified Naranjo-style assessment is intended for learning purposes and is not a substitute for a validated clinical causality assessment.

## 👩‍💻 Author

**Shanmugapriya A**

Aspiring Healthcare Data Analyst | Biotechnology Graduate | Interested in Clinical Research and Pharmacovigilance

## 🏷️ Tags

`Pharmacovigilance` `Adverse Drug Reactions` `Healthcare Analytics` `Microsoft Excel` `Data Analysis` `Data Visualization` `Biotechnology` `Clinical Research`
