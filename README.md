# Hair Loss Prediction Project

This project analyzes factors contributing to hair loss and implements machine learning models to predict the likelihood of hair fall.

## Project Structure

```
hair-loss-prediction/
├── data/                   # Raw dataset
│   └── Predict_Hair_Fall.csv
├── notebooks/             # Exploratory notebooks
│   └── HairLoss_Prediction.ipynb
├── scripts/               # Preprocessing & model training code
│   ├── model_training.py
│   └── preprocessing.py
├── README.md
├── requirements.txt       # Python dependencies
└── .gitignore             # Ignore .ipynb_checkpoints, venv, etc.
```

## Setup Instructions
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```

## Run Model Training
```bash
python scripts/model_training.py