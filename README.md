# 🏈 NFL Draft Combine Modeling

## 📌 Project Purpose
This project explores how well NFL draft position (both overall pick and round) can be predicted using only NFL Combine data and measurable attributes.

## ❓ Problem Statement
Can we accurately predict where a player will be drafted (overall pick and round) based solely on combine and measurable data?

## ✅ Project Goals
- Build a **classification model** to predict **draft round**.
- Build a **regression model** to predict **draft pick number**.
- Evaluate the **limits** of what combine data alone can predict.
- Compare model results to the **actual 2024 NFL Draft**.

## 🎯 Motivation
This project was inspired by a desire to:
- Practice and enhance **data science skills**.
- Apply machine learning techniques to **real sports data**.
- Learn how effective physical metrics are for **NFL talent evaluation**.

## 🗂️ Folder Structure
```
NFL-Draft-Combine/
│
├── data/              # Raw, processed, and external datasets
├── notebooks/         # Jupyter notebooks for EDA, modeling, etc.
├── src/               # Source code: preprocessing, training, prediction
├── models/            # Saved classification and regression models
├── streamlit_app/     # Streamlit dashboard for model visualization
├── reports/           # Figures and visual outputs
├── README.md          # This file
├── requirements.txt   # Required Python packages
├── .gitignore         # Ignored files and folders
└── pyproject.toml     # (Optional) Dependency management
```

## 📊 Data Sources
- NFL Combine Results (year range TBD)
- NFL Draft results (2024 draft data and historical reference)

## 🧠 Models Used
- Logistic Regression, Random Forest, Gradient Boosting (for classification)
- Linear Regression, Random Forest Regressor, XGBoost (for regression)

## 🧪 Evaluation Metrics
- Classification: Accuracy, Precision, Recall, F1 Score, Confusion Matrix
- Regression: MAE, RMSE, R^2 Score

## 🔍 Future Work
- Add player **college performance metrics** to improve prediction.
- Analyze **position-specific models**.
- Add **scouting grades or expert rankings**.

## 📈 Streamlit Dashboard
A simple dashboard will be included to:
- Input combine metrics and predict draft results.
- Visualize model comparisons with actual draft.

## 💬 Usage
```bash
# Install dependencies
pip install -r requirements.txt

# Run Streamlit app
cd streamlit_app
streamlit run app.py
```

## 👨🏾‍💻 Author
- GitHub: [jlh28145](https://github.com/jlh28145)

---

## 📜 License
MIT License - see LICENSE file for details.


