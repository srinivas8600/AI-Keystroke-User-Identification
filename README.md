# AI-Driven User Identification Using Keystroke Dynamics

This project focuses on authenticating users based on their typing behavior (keystroke dynamics). It leverages both traditional machine learning and deep learning models to recognize unique typing patterns and classify users accurately.

---

## 🎯 Objective

To compare the performance of different ML and DL models in identifying users using keystroke dynamics, and to validate the results statistically using SPSS.

---

## 🧠 Models Compared

1. **SVM vs. Random Forest** (Traditional ML)
2. **LSTM vs. Random Forest** (Deep Learning vs ML)
3. **SVM vs. LSTM** (Feature Engineering vs Sequence Learning)
4. **LSTM vs. GRU** (Best Deep Learning model)

Each comparison includes:
- Model training
- Evaluation (Accuracy, Precision, Recall, F1-score)
- Confusion matrix
- Statistical analysis (T-Test using SPSS)

---

## 📁 Project Structure

AI-Keystroke-User-Identification/
│
├── Dataset/ # Keystroke CSV data
│ └── keystroke_data.csv
│
├── Models/ # Jupyter notebooks for each model
│ ├── svm_model.ipynb
│ ├── random_forest_model.ipynb
│ ├── lstm_model.ipynb
│ ├── gru_model.ipynb
│
├── Results/ # Confusion matrices, charts, evaluation reports
│ ├── confusion_matrix_svm.png
│ ├── evaluation_comparison.csv
│
├── SPSS/ # SPSS files and statistical analysis results
│ ├── t_test_output.pdf
│
├── Report/ # Final paper and poster
│ ├── IEEE_Paper.pdf
│ └── Tech_Star_Poster.pdf
│
├── requirements.txt # List of required Python packages
├── .gitignore # Files/folders excluded from Git tracking
└── README.md # Project overview

2.Install dependencies
pip install -r requirements.txt

3.Run the Jupyter notebooks
Navigate to the Models/ folder and open notebooks one by one.

📊 Results Summary
Model Comparison	Accuracy (%)	Precision	Recall	F1-Score
SVM vs. Random Forest	✅ ~90.3	0.89	0.90	0.89
LSTM vs. Random Forest	✅ ~89.8	0.90	0.90	0.90
SVM vs. LSTM	✅ Similar	-	-	-
LSTM vs. GRU	✅ GRU ~90.4	0.91	0.91	0.91

✅ Statistical validation using SPSS (T-Test) confirms performance differences.


Author & Guide
Author: Srinivas Annavarapu (Register No: 192211019)

Guide: Dr. V. Jaganathan

Institution: Saveetha School of Engineering

Presented at: Tech Star Summit 2025
