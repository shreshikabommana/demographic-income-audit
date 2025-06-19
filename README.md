# Analyzing Demographic Imbalance in Public Income Data

This project takes a closer look at the UCI Adult Income dataset to understand how fairly different demographic groups are represented. The dataset is commonly used for building machine learning models that predict whether a person earns more than $50K per year. Our analysis explores demographic imbalances and offers suggestions for improving fairness and transparency.

## Project Overview

We used a fairness evaluation framework (SystemCard+) to assess representation across factors like gender, race, education, and income. The goal was to identify any built-in bias and raise awareness about potential risks when using this dataset in decision-making systems.

## Files Included

- `code.ipynb` – Jupyter Notebook with data cleaning, visualizations, and fairness evaluation  
- `adult_income.csv` – Original dataset used in the analysis  
- `Analyzing Demographic Imbalance in Public Income Data (5-2025).pdf` – Final report with key findings and recommendations  

## Key Takeaways

- The dataset scored **-18 out of 55** on a fairness checklist  
- Disparities were found in gender balance, racial representation, and income groupings  
- No built-in bias mitigation techniques or transparency documentation were found  
- Recommendations include reweighting, resampling, and more transparency in dataset design

## Tools & Skills Used
- Python
- Fairness auditing and reporting  
- Data ethics and responsible AI practices  
- Communication through visual and written storytelling
