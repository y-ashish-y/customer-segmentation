# Customer Segmentation

Multi-class classification that predicts which of four customer segments (A, B, C, D) a new customer belongs to, so a sales team can target outreach the same way it did in its existing market.

**Dataset:** Customer segmentation data from an Analytics Vidhya hackathon. The task is to score 2,627 new potential customers.

## Contents

| File | Description |
|---|---|
| `Customer_segmentation.ipynb` | Segment prediction, model comparison, evaluation, and feature importance |

## Approach

1. **Predicting segmentation:** data preparation and encoding of customer attributes
2. **Supervised ML:** XGBoost classifier on a train/test split
3. **Model evaluation:** scikit-learn classification report (per-class precision, recall, F1)
4. **Feature importance:** profession, age, and family size are the strongest drivers of segment membership

## Run

Open the notebook in Jupyter or Google Colab. Install the dependencies:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn xgboost
```
