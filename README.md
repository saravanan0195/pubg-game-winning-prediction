# PUBG Game Winning Prediction 🎯🏆

A machine learning project that predicts the winning percentage of players in **PUBG (PlayerUnknown's Battlegrounds)** based on in-game stats. Built using Python and trained on a real dataset from Kaggle, this project aims to demonstrate the power of data analysis and predictive modeling in competitive gaming environments.

## 🔍 Problem Statement

The objective is to predict a player's final winning percentage in a match using various gameplay statistics such as kills, distance traveled, items looted, etc. The model helps identify key factors contributing to performance and makes accurate predictions of match outcomes.

---

## 📂 Dataset

- **Source**: [Kaggle PUBG Finish Placement Prediction](https://www.kaggle.com/competitions/pubg-finish-placement-prediction)
- **Size**: 4+ million players’ match stats.
- **Format**: CSV
- **Features**: Includes stats like `kills`, `walkDistance`, `weaponsAcquired`, `matchDuration`, and many more.

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (Data Visualization)
- Scikit-learn (ML Models)
- Jupyter Notebook

---

## 🧠 Machine Learning Models

The following ML algorithms were explored:
- Linear Regression ✅
- Decision Tree Regressor
- Random Forest Regressor ✅
- Gradient Boosting Regressor

The **Random Forest Regressor** gave the best results in terms of accuracy and performance.

---

## 📊 Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **R² Score**
- **Root Mean Squared Error (RMSE)**

---

## 📈 Results

- **Best Model**: Random Forest Regressor
- **MAE**: ~0.02 (very close to true values)
- **Insights**:
  - `walkDistance`, `kills`, and `boosts` were among the most influential features.
  - Features like `matchType` also had a minor impact.

---

## 📁 Project Structure

```bash
pubg-game-winning-prediction/
│
├── dataset/
│   └── train_V2.csv
│
├── PUBG Winning Prediction.ipynb  # Jupyter notebook with full analysis
├── requirements.txt               # Dependencies
└── README.md                      # Project documentation
