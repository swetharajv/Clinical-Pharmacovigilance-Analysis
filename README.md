# 🏥 Clinical Data Intelligence: Pharmacovigilance & ADR Risk Detection

## 📌 Executive Summary
This project is an end-to-end data pipeline designed to analyze **1,000,000+ synthetic patient records** modeled after the FDA Adverse Event Reporting System (FAERS). The goal of this pipeline is to automate the detection of severe and fatal Adverse Drug Reactions (ADRs) and flag toxic concomitant drug combinations that are often missed during initial clinical prescriptions.

## ⚙️ Methodology & Tech Stack
* **Language:** Python
* **Libraries:** Pandas (Data manipulation), Seaborn & Matplotlib (Data Visualization)
* **Environment:** Google Colab / Jupyter Notebook

## 🚀 Key Deliverables & Clinical Impact
1. **Big Data Ingestion & Filtration (EDA):** Bypassed standard spreadsheet limitations by utilizing Python to ingest and filter a 1-million row clinical dataset, isolating strictly 'severe' and 'fatal' hospitalizations.
2. **Automated Risk Dashboards:** Generated Seaborn heatmaps and bar charts to visually rank the top 10 most dangerous primary drugs (e.g., Amlodipine, Metformin) for hospital stakeholders.
3. **Lethal Concomitant Identification:** Built cross-referencing algorithms to identify lethal secondary interactions (e.g., Amlodipine + Hydrochlorothiazide) causing severe patient outcomes.
4. **Data Cleaning & Anomaly Detection:** Audited messy hospital entry data to successfully flag and remove duplicate-entry prescription errors, ensuring 100% accuracy in the final clinical risk report. 

## 📂 Project Files
* `Pharmacovigilance_Analysis.ipynb`: The core Python code and visualization pipeline.
* `Cleaned_Amlodipine_Risk_Report.csv`: The final, audited data export detailing the highest-risk drug interactions.
