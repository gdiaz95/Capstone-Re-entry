# Capstone Re-entry

## 📂 Project Structure

```text
Capstone-Re-entry/
├── Data/                     # Raw and processed data (ignored, only .gitkeep tracked)
│   ├── raw/                  # Immutable original datasets
│   ├── interim/              # Intermediate cleaned/transformed
│   └── processed/            # Final features for modeling
│
├── Papers/                   # References, notes, related research
│
├── notebooks/                # Jupyter notebooks (exploration, EDA)
│   └── 01_data_exploration.ipynb (example)
│
├── src/                      # Source code (main package)
│   └── capstone/             # Python package (importable: `capstone.*`)
│       ├── data/             # Data loading, preprocessing
│       ├── features/         # Feature engineering
│       ├── models/           # Training & evaluation
│       ├── utils/            # Helper functions
│       └── visualization/    # Plotting, metrics
│
├── tests/                    # Unit and integration tests
│
├── configs/                  # Config files for experiments
│
├── scripts/                  # Command-line entry points (training, evaluation, etc.)
│
├── models/                   # Saved models / checkpoints (ignored, only .gitkeep tracked)
│
├── reports/                  # Results, figures, experiment outputs (ignored, only .gitkeep tracked)
│   └── figures/
│
├── pyproject.toml            # Poetry config (dependencies, package info)
├── poetry.lock
├── README.md                 # Project overview (this file)
├── .gitignore                # Ignore data dumps, models, venvs, etc.
└── .env                      # Environment variables (ignored)

