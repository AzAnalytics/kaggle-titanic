# Titanic: Machine Learning from Disaster

First project of my machine learning learning path on Kaggle: a complete, honest ML workflow on a classic dataset, from data exploration to a validated model and a Kaggle submission.

## Goal

**Predict which passengers survived the Titanic shipwreck** from their characteristics (class, sex, age, fare, family on board...).

Beyond the score, the point of this project is the method:
- start from a simple baseline before any model,
- validate with cross-validation, not a single lucky split,
- explain every choice (features, model, metric).

## Data

Source: [Kaggle competition "Titanic: Machine Learning from Disaster"](https://www.kaggle.com/competitions/titanic)

| File | Rows | Content |
|---|---|---|
| `train.csv` | 891 | Passengers with the target `Survived` (0/1) |
| `test.csv` | 418 | Passengers to predict, without the target |

The data is **not included in this repository** (Kaggle competition rules forbid redistribution). To download it, accept the competition rules on Kaggle, then run:

```bash
kaggle competitions download -c titanic -p data
```

and unzip the archive into `data/`.

## Installation

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

Main libraries: pandas, NumPy, scikit-learn, Matplotlib, Jupyter.

## Project structure

```
kaggle-titanic/
├── data/            # Kaggle data (ignored by Git)
├── notebooks/       # analysis and modeling, numbered in order
├── requirements.txt # pinned dependencies
└── README.md
```

## Progress

- [x] Environment and repository setup
- [ ] Exploratory data analysis
- [ ] Baseline model
- [ ] Feature engineering
- [ ] Model comparison with cross-validation
- [ ] Kaggle submission

## Results

*Coming soon.*

## What I learned

*Coming soon.*
