# αDiviScope

### A Dedicated Alpha Diversity Quantification & Visualization Tool

αDiviScope is a reproducible, statistically validated alpha diversity analysis tool for microbiome, metagenomic, and ecological community data. It provides accurate computation, visualization, and export of multiple alpha diversity metrics using a transparent and interactive workflow.

---

## 🔬 Key Features

- Supports Excel (`.xlsx`) and CSV (`.csv`) taxon tables  
- Automatic handling of taxonomic and sample abundance columns  
- Computes multiple standard alpha diversity indices  
- Bootstrap-based confidence interval estimation  
- Publication-ready visualizations  
- Exportable Excel reports with embedded graphs  
- Fully compatible with Google Colab and Jupyter Notebook  

---

## 📁 Input File Format

Your input file **must** follow this structure:

### Required Taxonomic Columns

### Sample Columns
- All columns after taxonomy are treated as samples
- Values must be numeric (read counts or abundances)
- Missing values are automatically set to zero

Example:

---

## 📊 Alpha Diversity Metrics Implemented

αDiviScope calculates the following metrics:

- **Shannon Entropy** – Community richness and evenness
- **Simpson Index** – Dominance-weighted diversity
- **Inverse Simpson Index** – Effective number of dominant taxa
- **Observed Taxa (Richness)** – Number of detected taxa
- **Chao1 Estimator** – Estimated true richness accounting for rare taxa
- **Pielou Evenness** – Community evenness
- **Berger–Parker Dominance** – Maximum dominance
- **Good’s Coverage** – Sampling completeness

Each metric includes **95% bootstrap confidence intervals**.

---

## 📈 Visualization

For every metric:
- Bar plots are generated per sample
- Figures are suitable for publication
- Graphs are embedded directly into exported Excel files

---

## 📤 Exported Results

αDiviScope exports:
- Metric-specific tables
- Confidence intervals
- Embedded visualizations

All outputs are stored in a single Excel file for reproducibility.

---

## ⚠️ Important Notes

- Alpha diversity metrics are sensitive to sequencing depth
- Observed richness and Chao1 are depth-dependent
- Rare taxa strongly influence some estimators
- The tool does not perform rarefaction or beta diversity analysis

---

## 🧪 Intended Use Cases

- Microbiome research
- Environmental genomics
- Ecological biodiversity studies
- Teaching and demonstration
- Pilot and exploratory studies

---

## 🧠 Scientific Foundations

Metrics are based on classical ecological theory:
- Shannon (1948)
- Simpson (1949)
- Chao (1984)
- Pielou (1966)
- Good (1953)

---

## 📜 License

This project is intended for academic and research use.

---

### Developed by **Muhammad Sohaib Hassan**
