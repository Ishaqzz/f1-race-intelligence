# F1 Race Intelligence

Data science and AI training project analysing 75+ years of Formula 1 data with
statistics, probability, linear algebra, and machine learning to understand
what decides a race win.

## Project structure

```text
data/
├── raw/        # Original, unmodified datasets
└── processed/  # Cleaned datasets ready for analysis
notebooks/      # Exploratory analysis and experiments
src/            # Reusable data-processing and modelling code
app/            # Streamlit application
```

## Setup

Create and activate a virtual environment, then install the project
dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Place source datasets in `data/raw/`, use the notebooks for exploration, and
put reusable analysis code in `src/`.
