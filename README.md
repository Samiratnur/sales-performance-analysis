readme = """# Sales Performance Analysis
**Intern:** Samir Mahamad Atnur  
**Intern ID:** 2614  
**Company:** Vaidsys Technologies  
**Internship Duration:** 8 Aug 2025 – 7 Sep 2025

## Project Summary
Analysis of Superstore sales data to identify KPIs, best-selling products, peak months, and region/segment performance. Implemented using Python (pandas, matplotlib, seaborn).

## Deliverables
- Sales_Analysis.pdf — Final report with EDA, visualizations and recommendations.
- Sales_Analysis.ipynb — Jupyter Notebook (code + outputs).
- Superstore.csv — Dataset used for analysis.
- outputs/ — KPIs (kpis.csv) and saved figures (png).

## How to run
1. Open `Sales_Analysis.ipynb` in Jupyter Notebook.
2. Run all cells (Cell → Run All).
3. Outputs (figures and kpis.csv) will be saved in `outputs/` folder if the save-code is executed.

## Tools & Environment
- Python (tested with 3.13)
- pandas, matplotlib, seaborn
- Jupyter Notebook (Anaconda / Miniconda)

## Notes
- CSV encoding handled using `encoding='latin1'`.
- Date columns parsed with `pd.to_datetime(..., dayfirst=True)`.

## Contact
Samir Mahamad Atnur  
Email: <your_email_here>  
Phone: <your_phone_here>
"""
with open("README.md","w",encoding="utf-8") as f:
    f.write(readme)
print("README.md created at:", __import__("os").path.abspath("README.md"))
