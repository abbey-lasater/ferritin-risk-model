# ferritin-risk-model
Exploring demographic and lifestyle factors that influence ferritin levels in women using NHANES data. This project uses statistical analysis and machine learning to identify key predictors of iron deficiency.

This project explores the demographic and lifestyle factors that influence ferritin levels in women using publicly available data from NHANES (National Health and Nutrition Examination Survey). Ferritin is a key marker of iron storage in the body, and iron deficiency is one of the most common nutritional issues among women of reproductive age.

The goal is to identify patterns in the data that predict ferritin deficiency and to build a machine learning model that can help assess risk based on various demographic variables.

## Project Objectives

- Understand the distribution of ferritin levels across different demographic groups.
- Identify key risk factors associated with low ferritin.
- Use statistical and machine learning methods to predict ferritin deficiency.
- Provide clear visualizations and model interpretability.

## Dataset

**Source:** [CDC NHANES](https://wwwn.cdc.gov/nchs/nhanes/)  
**Date:** September 2024

The following NHANES files are used in this project:

- Demographics (DEMO)
https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/DEMO_L.htm
- Laboratory data (LBXFER)
https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/FERTIN_L.htm
- Body Measurement Data (BMX)
https://wwwn.cdc.gov/Nchs/Data/Nhanes/Public/2021/DataFiles/BMX_L.htm

All files are merged using the respondent identifier `SEQN`.

## Column Definitions
BMXWT : weight (kg)
RIAGENDR : gender
RIDAGEYR : age (years)
RIDAGEMN : age (months)
RIDRETH1 : race-ethnicity cat
RIDRETH3: race-ethnicity cat
RIDEXMON : month survery was perf
RIDEXAGM : age in mo. at time of exam
BMXWT : weight (kg)
BMXHT: standing height (cm)
BMXBMI : body mass index (kg/m)
BMXWAIST: waist_circum
LBXFER: ferritin level (ng/ml)

1 male; 2 female


## Methodology

1. Data cleaning and merging multiple NHANES datasets
2. Exploratory data analysis (EDA) and visualization
3. Feature engineering and transformation
4. Modeling with logistic regression and tree-based classifiers
5. Model evaluation using AUC, accuracy, and precision-recall
6. Feature importance interpretation 

## Key Findings 
