# Household Expenditure Analysis

**Author:** Nataraj Narayan  
**Repo:** [Natsman/household-expenditure-analysis](https://github.com/Natsman/household-expenditure-analysis)  

## 📊 Project Overview
This project analyzes how **education, income, and demographic characteristics** affect household monthly expenditure.  
Using a dataset of 50 households, I compare **Multiple Linear Regression** and **Decision Tree Regression** models to understand which approach best explains expenditure patterns.  

The project is part of my MSc coursework in **Applied Economics + AI/ML**, and demonstrates how traditional econometrics and modern machine learning can complement each other.

---

## 🔑 Key Results
- **Income** and **household size** are strong positive predictors of monthly expenditure.  
- **EMI/Rent** significantly increases outflows.  
- **Number of earners** shows a negative relationship with expenditure (possibly due to savings behavior in multi-earner households).  
- **Education** had a weak effect in this small dataset.  
- Cross-validation shows **Linear Regression generalizes better** on this dataset, while Decision Tree captures non-linear splits but risks overfitting.

---

## 📂 Repository Contents
- `2437038_Nataraj.ipynb` — Jupyter Notebook with the full analysis, code, and visuals.  
- `2437038_Nataraj.pdf` — Exported PDF report (ready-to-read version).  
- `2437038_Nataraj.html` — HTML version of the notebook (optional, for GitHub Pages).  
- `requirements.txt` — Python package dependencies.  
- `.gitignore` — Ignoring cache/temporary files.  
- `images/` — Preview images from the analysis (optional).  

---

## ⚙️ How to Run
Clone the repository:
```bash
git clone https://github.com/Natsman/household-expenditure-analysis.git
cd household-expenditure-analysis
