# Solar Challenge Week 1 - Data Profiling and EDA

## Project Overview
This project is part of the 10 Academy Solar Challenge Week 1. The goal is to perform data profiling, cleaning, and exploratory data analysis (EDA) on solar datasets from Benin, Sierra Leone, and Togo. The analysis prepares the data for further comparison and region ranking.

---

## Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/uvatarkind/solar-challenge-week1.git
   cd solar-challenge-week1
   ```

2. **Create and activate a Python virtual environment:**

   * On Windows (PowerShell):

     ```powershell
     python -m venv venv
     .\venv\Scripts\Activate.ps1
     ```
   * On Windows (Git Bash):

     ```bash
     python -m venv venv
     source venv/Scripts/activate
     ```
   * On Linux/macOS:

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. **Install required packages:**

   ```bash
   pip install -r requirements.txt
   ```

---

## How to Run the Code / Notebooks

* Open the Jupyter notebooks located in the `notebooks/` folder to view and run the EDA and data cleaning steps.
* Each notebook is named `<country>_eda.ipynb` (e.g., `benin_eda.ipynb`).
* You can launch Jupyter Notebook or Jupyter Lab by running:

  ```bash
  jupyter notebook
  ```

  or

  ```bash
  jupyter lab
  ```

---

## Project Structure

```
├── .github/                 # GitHub workflows for CI
├── notebooks/               # Jupyter notebooks with EDA and data profiling
│   ├── benin_eda.ipynb
│   ├── sierra_leone_eda.ipynb
│   └── togo_eda.ipynb
├── src/                     # (Optional) Source code files
├── data/                    # Raw and cleaned data files (gitignored)
├── requirements.txt         # Python dependencies
├── README.md                # This file
└── .gitignore               # Specifies untracked files/folders (e.g. data/)
```

---

## Contributions Summary

* Created EDA notebooks analyzing solar farm data from three countries.
* Cleaned datasets by detecting and handling missing values and outliers.
* Visualized trends and correlations in the solar radiation and weather data.
* Set up GitHub Actions CI workflow for automated environment setup verification.
* Documented the project setup, folder structure, and analysis process in this README.

---

## Contact

If you have any questions or feedback, feel free to reach out at yubi14465@gmail.com.
