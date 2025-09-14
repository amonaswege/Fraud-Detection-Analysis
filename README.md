# Forensic Fraud Detection 

This project demonstrates basic forensic data analytics for fraud detection using a transactions dataset.
Files:
- fraud_data.csv (dataset)
- fraud_detection_notebook.ipynb (step-by-step notebook)

How to run:
1. Clone repo.
2. Place `fraud_data.csv` in the repo root or `data/` folder.
3. Install dependencies: `pip install pandas scikit-learn matplotlib`.
4. Open `fraud_detection_notebook.ipynb` in Jupyter and run cells.

Notes on data issues: the original `is_fraud` column had malformed strings in some rows; the notebook shows the cleaning step (extract leading 0/1 and drop malformed rows).


