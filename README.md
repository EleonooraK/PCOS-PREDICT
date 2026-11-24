# PCOS-PREDICT

Early clinical screening and risk prediction for Polycystic Ovary Syndrome (PCOS) using clinical, hormonal, physical, and ultrasound features.

## Authors
- **Eleonoora Kõrge** — Team leader, primary model training, recall optimization
- **Tuuli-Mia Haas (Mia)** — Poster design, data visualization, diagram design
- **Ursula Raie** — Data cleaning, cross-validation between datasets, testing

## Motivation and Goal
Early detection of PCOS during initial clinical screening supports timely intervention, yet cases can be missed in routine review. Our goal is to build and evaluate an end-to-end classification workflow that prioritizes high recall (minimizing false negatives) while keeping results transparent and reproducible.

## Repository Structure
- `PCOS_data_without_infertility.csv` — Primary patient dataset (541 rows, clinical/lab/ultrasound features, and `PCOS (Y/N)` target)
- Data preparation & cleaning scripts/notebooks — Fixes data types, `#NAME?` errors, missing values, and train/test splitting
- Modeling & evaluation scripts/notebooks — Baseline model, trained classifiers, cross-validation / cross-dataset tests, and evaluation metrics
- Poster & figures — Visualizations and final project poster for *LTAT.02.002 Introduction to Data Science* (Autumn 2026)

## How to Reproduce the Analysis
1. Clone `https://github.com/EleonooraK/PCOS-PREDICT`.
2. Install Python and required data science packages (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, and any additional model libraries used).
3. Place the dataset in the expected data path and run the data preparation notebook/script first, followed by the modeling and evaluation notebooks/scripts in order.
