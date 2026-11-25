# DSCE Campus Placement Analysis

<p align="center">
  <strong>A data-driven view of placement trends at <a href="https://www.dsce.edu.in/">Dayananda Sagar College of Engineering (DSCE)</a></strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Language-Jupyter%20Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter Notebook">
  <img src="https://img.shields.io/badge/Data-Python%20%7C%20Pandas-3776AB?logo=python&logoColor=white" alt="Python and Pandas">
  <img src="https://img.shields.io/badge/Format-CSV%20%7C%20Excel-217346?logo=microsoftexcel&logoColor=white" alt="CSV and Excel">
  <img src="https://img.shields.io/badge/Data-Placement%20Records-1F6FEB" alt="Placement Records">
</p>

## 📌 Overview

This project analyzes campus placement information published on the official DSCE placement website. Individual academic-year placement tables were collected using Python-based web scraping, cleaned, standardized, and organized for year-wise and company-wise analysis.

The repository contains both yearly records and combined analysis outputs covering the academic years **2022–23 to 2025–26**.

***Please consider giving it a ⭐ on GitHub If you find this repository useful—especially if you are a DSCE student. It helps others discover the project and motivates further improvements.***

## ✨ Key Features

- Collects placement data from the official DSCE placement website
- Organizes records for each academic year
- Converts placement tables into clean CSV datasets
- Consolidates yearly data into a combined pivot-style dataset
- Provides Jupyter Notebook analysis for placement trends
- Includes an interactive HTML summary for quick viewing
- Supports further filtering, visualization, and statistical analysis

## 📊 Data Coverage

| Academic Year | Dataset |
|:---|:---|
| 2022–23 | [`individual_year_analysis/DSCE_2022-23.csv`](https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS/blob/main/individual_year_analysis/DSCE_2022-23.csv) |
| 2023–24 | [`individual_year_analysis/DSCE_2023-24.csv`](https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS/blob/main/individual_year_analysis/DSCE_2023-24.csv) |
| 2024–25 | [`individual_year_analysis/DSCE_2024-25.csv`](https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS/blob/main/individual_year_analysis/DSCE_2024-25.csv) |
| 2025–26 | [`individual_year_analysis/DSCE_2025-26.csv`](https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS/blob/main/individual_year_analysis/DSCE_2025-26.csv) |

## 🗂️ Repository Structure

```text
DSCE_CAMPUS_PLACEMENT_ANALYSIS/
├── all_in_one_pivot_table/
│   ├── DSCE_Placement_Pivot.csv
│   └── DSCE_Placement_Pivot.xlsx
├── collab_code/
│   ├── DSCE_placemet_22_26_summary.ipynb
│   └── DSCE_placemet_all_AC_year_22_26.ipynb
├── individual_year_analysis/
│   ├── DSCE_2022-23.csv
│   ├── DSCE_2023-24.csv
│   ├── DSCE_2024-25.csv
│   └── DSCE_2025-26.csv
├── dsce_placement_22-26_summary.html
└── README.md
```

## 🔬 Analysis Workflow

1. **Scrape** placement tables from the official DSCE placement website.
2. **Extract** relevant academic-year records.
3. **Clean** inconsistent values and standardize the dataset.
4. **Consolidate** yearly information into combined views.
5. **Analyze** company-wise and year-wise placement patterns.
6. **Export** results as CSV, Excel, and interactive HTML summaries.

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- Common data-analysis libraries, including `pandas`, `numpy`, and `matplotlib`

### Run the Analysis

```bash
# Clone the repository
git clone https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS.git

# Enter the project directory
cd DSCE_CAMPUS_PLACEMENT_ANALYSIS

# Install dependencies in your environment
pip install pandas numpy matplotlib jupyter

# Start Jupyter Notebook
jupyter notebook
```

Open a notebook from the `collab_code` directory to explore the analysis.

## 📈 Interactive Summary

The combined placement summary is available as an interactive HTML report:

- [Open `dsce_placement_22-26_summary.html`](https://github.com/vigneshsindhe/DSCE_CAMPUS_PLACEMENT_ANALYSIS/blob/main/dsce_placement_22-26_summary.html)

For the best experience, download the file and open it in a modern web browser.

## 💡 Possible Use Cases

- Compare placement activity across academic years
- Identify organizations recruiting consistently from DSCE
- Analyze company-wise placement distributions
- Build dashboards or additional visualizations
- Use the cleaned datasets for academic or research projects

## 🛠️ Tools and Technologies

- **Python** — data collection and processing
- **Jupyter Notebook** — interactive analysis
- **Pandas** — cleaning and transformation
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **CSV / Excel** — portable data formats
- **HTML** — shareable analysis summary

## 🤝 Contributing

Contributions are welcome. You can improve the documentation, enhance visualizations, add analysis, or help refine the datasets.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a pull request

## ⚠️ Data and Usage Note

Placement records may change or be corrected by the official source after publication. Before making decisions based on the data, verify important figures directly with DSCE or the official placement records.

## 📄 License

No license has been specified for this repository. Please contact the repository owner before using the project or its datasets in a commercial or redistributed context.

## 👤 Author

Created by [Vignesh Sindhe](https://github.com/vigneshsindhe)

---

<p align="center">
  If this project helped you, especially as a DSCE student, consider giving it a ⭐ on GitHub!
</p>
