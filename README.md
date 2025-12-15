# SHL-Research-Intern-Hiring-Assessment

# SHL Grammar Scoring Engine – Research Intern Assessment

## Overview
This notebook presents my solution for the SHL Grammar Scoring challenge, where the goal is to predict a continuous grammar score (0–5) from spoken audio samples.

## Methodology
- Audio preprocessing and validation
- Hybrid feature extraction:
  - Deep acoustic embeddings using Whisper encoder
  - Handcrafted acoustic features (MFCC, ZCR, RMS)
  - Audio duration
- Regression model:
  - XGBoost Regressor
- Evaluation:
  - RMSE and Pearson Correlation on validation set

## Notes
- Feature extraction using Whisper is computationally intensive and was executed on Google Colab.
- The submitted `submission.csv` was generated using this pipeline.

## Folder Stucture
```
├── grammar_scoring.ipynb
└──  README.md
```

