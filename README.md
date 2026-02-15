# U.S.-Library-Visitation-Pay-Equity

**Project:** Modeling Visitation and Pay Equity in U.S. Public Libraries

**Purpose:** Repository for a class project exploring the relation of Wi-Fi, programs, and open hours to visits by locale as well as investigating staff pay equity to IRS ZIP code income data.

**Contents:**
- **Data:**
  - `Data/PLS_FY22_AE_pud22i` — 2022 Public Libraries Survey (n ≈ 9K libraries)
  - `Data/22zpallagi` — Placeholder for IRS ZIP Code Income Data. Download here: https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics-2022-zip-code-data-soi

- **Notebooks:**
	- `Notebooks/amoskal_finalproject.ipynb` — Full project notebook.

- **Environment:** `requirements.txt` is included for reproducibility.

**My Role:**
- **Topic modeling:**
  - Prepared the 2022 Public Libraries Survey (n ≈ 9K libraries) with outlier handling, locale features, and average salary-per-FTE
measures.
  - Fit regression models (with diagnostics) to relate Wi-Fi, programs, and open hours to visits by locale and joined IRS ZIP code
income data to assess staff pay equity.

**Notes & Assumptions**
- The notebooks expect the datasets at `Data/`.

**Attribution & License**

- License: see `LICENSE` in repo root.
