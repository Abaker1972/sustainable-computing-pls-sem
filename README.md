# Sustainable Computing Adoption using PLS-SEM

## Overview
This repository contains the dataset and analysis for the study:

**"Organizational Drivers of Sustainable Computing Adoption and Future Sustainability Intentions"**

The study investigates how **awareness, organizational drivers, and perceived barriers** influence **sustainable computing practices** and **future sustainability intentions** using **Partial Least Squares Structural Equation Modeling (PLS-SEM)**.

---

## Dataset

- **Sample size:** N = 300  
- **Sampling method:** Non-probability purposive sampling  
- **Data collection:** Online survey (Google Forms)  
- **Scale:** 5-point Likert scale (1 = strongly disagree, 5 = strongly agree)  

### Sector Distribution
- Government: 100 (33.3%)  
- Private: 73 (24.3%)  
- Education: 127 (42.3%)  

---

## Variables

The dataset includes the following constructs:

| Construct | Code | Items |
|----------|------|------|
| Awareness | AW | AW1–AW5 |
| Drivers | DR | DR1–DR5 |
| Barriers | BR | BR1–BR5 |
| Sustainable Computing Practices | PR | PR1–PR5 |
| Future Sustainability Intentions | FI | FI1–FI5 |

---

## Methodology

- **Analysis technique:** PLS-SEM (SmartPLS)  
- **Bootstrapping:** 5,000 resamples  
- **Approach:** Two-stage analysis  
  - Measurement model assessment  
  - Structural model assessment  

### Measurement Criteria
- Cronbach’s Alpha > 0.70  
- Composite Reliability (CR) > 0.70  
- Average Variance Extracted (AVE) > 0.50  
- HTMT < 0.85  

---

## Key Results

- Drivers → Practices (**β = 0.41, p < 0.001**)  
- Awareness → Practices (**β = 0.32, p < 0.001**)  
- Barriers → Practices (**β = −0.28, p < 0.01**)  
- Practices → Future Intentions (**β = 0.44, p < 0.001**)  

### Model Explanation
- R² (Practices) = 0.57  
- R² (Future Intentions) = 0.63  

---

## Repository Structure

---

## Reproducibility

The dataset and analysis outputs are provided to support reproducibility and transparency of the study findings.  
PLS-SEM analysis was conducted using **SmartPLS**.

---

## Data Availability

The dataset used in this study is publicly available in this repository.  
The data are synthetic and generated for research and reproducibility purposes.

---

## License

This project is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

---

## Author

**Ahmed Abaker**  
Corresponding Author  

---

## Citation

If you use this dataset, please cite:

> Abaker, A. (2025). Sustainable Computing Adoption Dataset (PLS-SEM). GitHub Repository.
