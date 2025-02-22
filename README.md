# Credit-Card-Fraud-Detection-System
Overview
This project implements a Credit Card Fraud Detection System using Logistic Regression. It aims to classify transactions as fraudulent or legitimate based on historical transaction data.

Dataset
The model is trained on a dataset containing transaction details, including:

Time
Amount
Transaction type
Cardholder information
Fraud labels (0 = Legitimate, 1 = Fraudulent)
Features
✅ Logistic Regression Model for binary classification
✅ Data Preprocessing (handling missing values, scaling, encoding)
✅ Feature Engineering (selecting important fraud indicators)
✅ Model Evaluation (accuracy, precision, recall, F1-score, AUC-ROC)
✅ Visualization (fraud distribution, correlation heatmaps)

Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Scikit-learn (Logistic Regression, Metrics, Train-Test Split)
Jupyter Notebook (for model training & evaluation)
Installation
Clone this repository:
bash
Copy
Edit
git clone https://github.com/your-repo/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
Copy
Edit
jupyter notebook
Model Performance
The model is evaluated using:

Accuracy: Measures overall correctness
Precision: Identifies fraud detection reliability
Recall: Detects fraudulent transactions correctly
F1-Score: Balances precision and recall
AUC-ROC: Measures classification effectiveness
Results
The trained Logistic Regression model achieves high accuracy with a good balance between precision and recall, effectively detecting fraudulent transactions.

Contributions
Feel free to contribute! Open an issue or submit a pull request.

License
MIT License

