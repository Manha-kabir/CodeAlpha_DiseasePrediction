# Disease Prediction from Medical Data

**Objective:** Predict the possibility of diseases (Diabetes / Heart Disease / Breast Cancer) using structured patient data.

---

## 📋 Overview
This project demonstrates a beginner-friendly machine learning pipeline:
- Load and clean data
- Split into train/test sets
- Train baseline model (Logistic Regression)
- Try advanced models (Random Forest, XGBoost)
- Evaluate using accuracy, confusion matrix, and ROC AUC
- Save trained model for later use

---

## 📁 Project Structure
```
CodeAlpha_DiseasePrediction/
├─ data/            # datasets (CSV files go here)
├─ notebooks/       # Jupyter notebooks (.ipynb)
├─ models/          # saved trained models
├─ src/             # optional Python scripts
├─ requirements.txt # list of dependencies
└─ README.md        # this file
```

---

## 🧠 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Manha-kabir/CodeAlpha_DiseasePrediction.git
   cd CodeAlpha_DiseasePrediction
   ```

2. **Create a virtual environment & activate it:**
   ```bash
   python -m venv venv
   venv\Scripts\activate     # for Windows
   # or
   source venv/bin/activate  # for macOS/Linux
   ```

3. **Install required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Download a dataset (e.g., Pima Diabetes from UCI/Kaggle)**  
   Save it as `data/diabetes.csv`

5. **Run Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open `notebooks/disease_prediction.ipynb` and run the cells.

---

## 📊 Models Used
- Logistic Regression (baseline)
- Random Forest
- XGBoost

Each model’s accuracy and ROC AUC are compared to pick the best performer.

---

## 💾 Output
- Trained model saved in `/models/random_forest_model.joblib`
- Evaluation metrics printed and visualized in notebook
- ROC curve plotted for model performance

---

## ⚠️ Notes
- Use **public datasets only** (no private patient data)
- Replace placeholder dataset paths as needed
- Works with Python 3.8 or higher

---

## 🤝 Acknowledgments
This project was completed as part of my **CodeAlpha Internship**.  
Dataset sources: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) and [Kaggle](https://www.kaggle.com/).

---

## 📜 License
MIT License — you’re free to use and modify this code.

### Note:
XGBoost was not included in the final results due to installation issues on my local environment.
The project still demonstrates multiple classification models (Logistic Regression and Random Forest) as required.