# Advanced Data Science Project: End-to-End Housing Market Modeling

This project demonstrates a production-grade, end-to-end data science workflow that goes far beyond basic analysis. It includes:

- **Data acquisition and profiling** (schema, missingness, leakage checks)
- **Exploratory data analysis (EDA)** with statistical summaries and distribution diagnostics
- **Feature engineering** (robust scaling, categorical synthesis, outlier flags)
- **Model benchmarking** across multiple algorithms
- **Hyperparameter optimization** using randomized search
- **Model evaluation** with cross-validation and holdout metrics
- **Explainability** with permutation importance and partial dependence plots
- **Reporting artifacts** saved as Markdown and figures

## Quickstart

```bash
python -m src.pipeline
```

Outputs are written to the `reports/` directory:

- `report.md`: Detailed EDA + modeling summary
- `feature_importance.png`: Permutation importance plot
- `partial_dependence.png`: Partial dependence plots

## Dependencies

Install with:

```bash
pip install -r requirements.txt
```

## Project Structure

```
.
├── README.md
├── requirements.txt
├── reports/
└── src/
    ├── pipeline.py
    ├── profiling.py
    ├── modeling.py
    └── reporting.py
```
