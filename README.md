# Income Prediction using Machine Learning

This project builds a machine learning model to predict whether an individual's annual income exceeds $50K based on census and employment data.

## 📌 Problem Statement

Given demographic and work-related features (like age, education, occupation, etc.), predict whether a person's income is:

- `<=50K`
- `>50K`

---

## 🛠️ Tech Stack

- Python 3.8+
- pandas, numpy, matplotlib, seaborn
- scikit-learn (Gradient Boosting Classifier, GridSearchCV)
- OneHotEncoder, StandardScaler
- Joblib (for model export)
- (Optional) Flask/Streamlit for deployment

---

## 📂 Project Structure

```
.
├── data/                   # Raw and cleaned datasets
├── notebooks/              # Jupyter notebooks
├── src/                    # Source code (preprocessing, model, utils)
├── model/                  # Saved model files
├── app/                    # Deployment app (Flask/Streamlit)
├── README.md
├── .gitignore
└── requirements.txt
```

---

## 🚀 Getting Started

1. Clone the repo  
```bash
git clone https://github.com/Uttam1611/income-prediction-ml.git
cd income-prediction-ml
```

2. Create virtual environment  
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies  
```bash
pip install -r requirements.txt
```

4. Run the notebook  
Open `notebooks/final.ipynb` and run step-by-step.

---

## 📈 Model Performance

- **Algorithm:** Gradient Boosting Classifier  
- **Accuracy:** ~XX%  
- **F1 Score:** XX  
- **ROC AUC:** XX


## 👨‍💻 Author

**Uttam Singh**  
[LinkedIn](https://www.linkedin.com/in/uttam-singh-b3b88a364)

---

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
