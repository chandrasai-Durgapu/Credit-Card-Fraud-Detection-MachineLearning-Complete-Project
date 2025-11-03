# Credit-Card-Fraud-Detection-MachineLearning-Complete-Project
Credit Card Fraud Detection Machine Learning Complete Project and it implements MLOPS, DVC, MLflow Dagshub and concepts included like Data Ingestion and Data Validation and Data Transformation and Model Training and Model Building etc


## Clone the repository
```bash
git clone https://github.com/chandrasai-Durgapu/Credit-Card-Fraud-Detection-MachineLearning-Complete-Project.git
```
```bash
cd Credit-Card-Fraud-Detection-MachineLearning-Complete-Project
```

## Create Virtual Environment
```bash
python -m venv credit-card-ml-01
```

## Activate Virtual Enviroment
```bash
.\credit-card-ml-01\Scripts\activate
```

## Install Dependencies
```bash
pip install -r requirements.txt
```

## Experiment Tracking using mlflow
```bash
https://dagshub.com/chandrasekharcse522/Credit-Card-Fraud-Detection-MachineLearning-Complete-Project.mlflow/#/experiments/0?searchFilter=&orderByKey=attributes.start_time&orderByAsc=false&startTime=ALL&lifecycleFilter=Active&modelVersionFilter=All+Runs&datasetsFilter=W10%3D
```

---
## Note

Option 1: Use Git Large File Storage (Git LFS)

Install Git LFS:
```bash
git lfs install
```

Track the large file:
```bash
git lfs track "creditcard.csv"
```

Commit the .gitattributes change:
```bash

git add .gitattributes
git add creditcard.csv
git add README.md  # and any other changes
```

Re-add the CSV file and push:
```bash
git commit -m "Add creditcard.csv via Git LFS and update README"
git push origin main
```
```bash
git config --global http.postBuffer 524288000
```
---