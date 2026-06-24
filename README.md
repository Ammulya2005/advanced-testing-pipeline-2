# Advanced Testing Pipeline with Quality Gates

## Objective
Build an automated testing pipeline for an ML API with quality gates using FastAPI, Pytest, and GitHub Actions.

## Features
- Data schema validation
- Null value checks
- Accuracy threshold validation
- Precision threshold validation
- Recall threshold validation
- F1 score validation
- Invalid API input testing
- CI pipeline using GitHub Actions

## Tech Stack
- Python
- FastAPI
- Scikit-learn
- Pandas
- Pytest
- Joblib
- GitHub Actions

## Run locally
1. Create and activate virtual environment
2. Install dependencies:
   pip install -r requirements.txt
3. Train model:
   python train.py
4. Run API:
   uvicorn app.main:app --reload --port 8002
5. Run tests:
   python -m pytest -v