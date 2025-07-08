

# 🧬 Network-Based Gene Discovery and Drug Repurposing for Osteoporosis

This project applies network biology and bioinformatics techniques to identify novel disease genes and repurposable drugs for **osteoporosis**, based on the human protein interactome.

## 📌 Project Overview

We reconstructed the human interactome using BioGRID data and applied multiple network-based algorithms to prioritize genes and map drugs relevant to osteoporosis. The pipeline mirrors real-world translational bioinformatics workflows.

## ⚙️ Methods Used

- **Interactome Reconstruction**: Built from BioGRID interaction data.
- **Gene Prioritization Algorithms**:
  - DIAMOnD
  - DiaBLE
  - ProConsul
- **Performance Evaluation**:
  - Precision, recall, F1 score
- **Biological Validation**:
  - GO and KEGG pathway enrichment (g:Profiler)
- **Drug Repurposing**:
  - DGIdb drug mapping to prioritized genes

## 📊 Technologies

- Python (networkx, pandas, matplotlib, etc.)
- Jupyter Notebook
- BioGRID, DisGeNET, g:Profiler, DGIdb

## 📂 Files

- `BINM_HW.ipynb` — full notebook with all code, results, and visualizations.
- `presentation.pdf` — final slides summarizing the project.

## 👥 Team

This project was developed as part of the *Bioinformatics and Network Medicine* course. Team members:
- Emre Pelzer
- Syed Habibul Bashar

## 🧪 How to Run

1. Open the Jupyter notebook (`BINM_HW.ipynb`).
2. Follow the steps in order — datasets are loaded from CSVs or API calls.
3. To run the Jupyter Notebook, install the required Python packages:

```bash
pip install -r requirements.txt

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
© 2025 — Bioinformatics and Network Medicine Group Project
