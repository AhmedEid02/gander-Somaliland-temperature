# AI-Assisted Climate Visualization with gander  
### Gu-Season Temperature Anomalies in Somaliland

![Gu-Season Temperature Anomalies in Somaliland](figures/v3_final.png)

---

## 📘 Project Overview

This project demonstrates how **AI integrated directly into the RStudio workflow (via gander)** can enhance climate data visualization by improving visual clarity, interpretability, and design decisions.

Using **Gu-season temperature anomalies in Somaliland (2000–2022)** as a case study, the project shows how a basic, human-generated plot can be iteratively refined into a **policy-ready and publication-quality visualization** through AI-assisted feedback — while keeping scientific judgment fully human-driven.

Rather than focusing on automated analysis, the project highlights how AI can support **design thinking and visualization literacy** inside the IDE.

---

## 📊 Data

- **Variable:** Seasonal mean temperature (Gu season)  
- **Spatial unit:** Somaliland (Admin-0)  
- **Period:** 2000–2022  
- **Baseline for anomaly calculation:** 2000–2010  

Temperature anomalies represent deviations from the baseline mean and are used here to support **visual communication of climate variability**, rather than formal climate trend attribution.

---

## 🛠️ Workflow

1. Data exploration and seasonal filtering  
2. Temperature anomaly calculation relative to a defined baseline  
3. Baseline visualization (human-only)  
4. AI-assisted refinement using **gander** inside RStudio  
5. Final publication-ready visualization  

Each stage is saved and documented to clearly show how visualization quality evolves through AI-assisted iteration.

---

## 🤖 How gander was used

The **gander** package was used as an AI assistant embedded directly within the RStudio environment to support visualization design and code refinement.

Specifically, gander was used to:
- Improve visual hierarchy and readability  
- Suggest perceptually meaningful encodings for temperature anomalies  
- Refine titles, labels, and legend placement  
- Clean and refactor ggplot2 code  

All AI suggestions were reviewed critically and selectively adopted. Final decisions regarding baseline selection, anomaly framing, and interpretation remained fully human-driven. This workflow illustrates how AI can **augment analytical reasoning and design thinking**, rather than replace scientific expertise.

---

## 📈 Results

The final visualization clearly distinguishes warming and cooling anomalies relative to the baseline, with recent years predominantly showing positive (warming) anomalies during the Gu season.

A before-and-after comparison highlights how AI-assisted refinement improves clarity, interpretability, and communication without altering the underlying data.

![Before vs After](figures/before_after_gander.png)

---

## 📂 Repository Structure

- `data/` – raw and processed temperature data  
- `scripts/main_analysis.R` – complete analysis and visualization workflow  
- `figures/` – baseline, refined, and final visualization outputs  
- `README.md` – project documentation  
---

## ⚠️ Disclaimer

This project focuses on **visualization methodology and AI-assisted workflows**. It does not aim to produce official climate trend estimates, attribution analyses, or operational climate services.

---

**Author:** Ahmed Hussein Ismail  
**Role:** Agro-Meteorologist & Climate Data Analyst.
