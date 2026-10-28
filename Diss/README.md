# Workforce Pressure Analytics for Market Entry in Children's Social Care

Analysis code and data for the MSc Business Analytics dissertation *Workforce Pressure Analytics for Market Entry in Children's Social Care: A Greater Manchester Case Study for Bikal Technologies* (UCL School of Management, 2025–26).

## Contents

| File | Description |
| --- | --- |
| `RO3_DialogXR_Analysis.ipynb` | The full analysis (Sections 1–14): data preparation and audit trail, exploratory analysis, Model 1 (H1), Model 2 (H2), inference model (H3), robustness checks, application to Greater Manchester, feasibility calculations and verification of standard errors. |
| `RO3_2023-2024_Outturn.csv` | MHCLG local authority revenue outturn (RO3), 2023–24. Open Government Licence v3.0. |
| `csww_indicators_2017_to_2025.csv` | DfE children's social work workforce indicators, 2017–2025. Open Government Licence v3.0. |
| `requirements.txt` | Python packages used. |

## How to reproduce the results

1. Install Python 3.10 or later and the packages listed in `requirements.txt`:
   ```
   pip install -r requirements.txt
   ```
2. Keep the two CSV files in the same folder as the notebook.
3. Open the notebook (`jupyter notebook RO3_DialogXR_Analysis.ipynb`) and run all cells in order (*Kernel → Restart & Run All*).

Section numbers in the dissertation (for example, "Appendix A, Section 7.1") refer to the numbered sections of this notebook.

## Data sources

- Ministry of Housing, Communities and Local Government: *Local authority revenue expenditure and financing, 2023–24 final outturn (RO3)*.
- Department for Education: *Children's social work workforce*, reporting years 2017–2025.

Both datasets are published under the Open Government Licence v3.0.

## Note

Bikal Technologies' internal documents are confidential and are not included in this repository.
