# STAT556-Homework-3
A Repository for STA556 Homework 3 for Samuel Anoff Addo

# STA 556 — Homework 3: Reproducibility & Matrix Computation

This repository contains a reproducible Quarto report that uses NumPy
matrix operations to fit and diagnose a linear model on the housing
dataset.

## Project Structure

```text
README.md                         project description and how to run
requirements.txt                  packages needed to run the project
data/raw/                         original data, never edited - housing.csv
reports/
        homework3.qmd             report source
        homework3.html            rendered report
_quarto.yml

```

## Dataset
- **Source:** Instructor's (Dr. Ben Lucas) Dataset
- **File:** `data/housing.csv`
- **Response:** `price_thousands`
- **Predictors:** `size_sqft`, `bedrooms`, `age_years`
- **Size:** 130 observations and 5 variables


## How to run

1. **Install Quarto** (Linux or GitHub Codespaces). Run the following in
   your terminal:
   ```bash
   wget https://github.com/quarto-dev/quarto-cli/releases/download/v1.10.19/quarto-1.10.19-linux-amd64.deb
   sudo apt-get install -y ./quarto-1.10.19-linux-amd64.deb
   ```
   Then check the installation:
   ```bash
   quarto --version
   ```
2. **Install the Python packages in requirements**

3. **Render the report** from the repository root:
   ```bash
   quarto render reports/homework3.qmd
   ```
4. **View it** by opening `reports/homework3.html` in a browser, or with:
   ```bash
   quarto preview reports/homework3.qmd
   ```
   If the preview opens in the browser but the page doesn't load or shows
   an error, add `/reports/homework3.html` to the end of the URL in the
   address bar.