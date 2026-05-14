# Sentinel — Network Intrusion Detection System

A machine learning system that classifies network traffic as **Normal** or **Malicious** using Random Forest and XGBoost.

## Project Structure

```
sentinel/
├── data/
│   ├── raw/          
│   └── processed/    
├── notebooks/        
├── src/              
├── models/           
├── app/              
└── reports/          
```

## Setup

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Dataset
NSL-KDD — download from Kaggle and place CSV files in `data/raw/`.
