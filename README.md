# Insurance Management System (Python)

## Overview
A Python-based insurance administration system that models customers, risk profiles, insurance products, policy rules, premium calculations, and claims processing.

## Key features
- Domain modelling using **dataclasses**
- Strong rule enforcement using **Pydantic validation**
- Multiple insurance lines (e.g., motor, home, life, business)
- Policy constraints and validation examples (valid + invalid scenarios)
- Premium calculation logic including fees and VAT
- Claims workflow and payout logic

## Project structure
- `/notebooks/`
  - `Insurance_Systems.ipynb` – system classes and core logic
  - `Insurance_Validation_Examples.ipynb` – validation and example runs
- `/docs/`
  - `Insurance_Report.md` / `Insurance_Report.pdf` – write-up and results

## How to run
1. Open the notebooks in Jupyter / VS Code / Google Colab.
2. Run `Insurance_Systems.ipynb` first (core system).
3. Run `Insurance_Validation_Examples.ipynb` to see validation scenarios and outputs.
