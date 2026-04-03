# ICA Project — Independent Component Analysis

## Submitted Files

This repository contains the following submitted files:

- `ICA_Project.ipynb` — main experimental notebook (all code and experiments)
- `ICA_report.pdf` — final written report

---

## Project Description

The work is organized into two main parts:

### Part 1 — Synthetic ICA Benchmark
- Comparison of several ICA algorithms on synthetic mixtures with known ground truth  
- Includes:
  - mathematical background  
  - experimental protocol  
  - low-dimensional analysis (d = 4 to 9)  
  - scalability study (d = 10 to 100)  
  - sensitivity analysis (learning rate, initialization)

### Part 2 — ICA with Missing Data
- Extension of ICA methods to datasets with missing values  
- Includes:
  - preprocessing strategies for missing data  
  - modified ICA solvers  
  - synthetic experiments under missing data  
  - sensitivity to missing rate  
  - transfer to real **EEG data**

### Conclusion
- Summary of findings  
- Discussion of limitations and practical insights  

---

## How to Run the Code

All experiments are contained in the notebook:

`ICA_Project.ipynb`

### Steps:

1. Open the notebook using:
   - Jupyter Notebook / JupyterLab  
   - VS Code  
   - or Google Colab  

2. Run all cells from top to bottom

---

## Dependencies

All required Python packages are already imported inside the notebook.

You do **not** need a separate installation script.  
Just run the notebook and install missing packages if prompted.

---

## Data

### Synthetic Data
- Automatically generated in the notebook  
- No download required  

### EEG Data 
- You need to **%pip install mne**  

---

## Reproducibility

- All experiments can be reproduced by running the notebook sequentially  
- Random seeds are fixed when necessary  
- Figures and results are generated automatically  

---

## Notes

- The notebook is self-contained and structured as an experimental report  
- It includes:
  - implementation  
  - experiments  
  - visualizations  
  - intermediate explanations  

---
