# 🏠 House Price Prediction Model

## 📌 About
A machine learning project that predicts house prices based on various property features like area, number of bedrooms, furnishing status, and more. Built and compared **5 regression models** to find the best performer.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost

## 📊 Dataset
- **Source:** Housing.csv
- **Records:** 545 entries
- **Features:** Area, Bedrooms, Bathrooms, Stories, Parking, Mainroad, Guestroom, Basement, Hot Water Heating, Air Conditioning, Preferred Area, Furnishing Status

## 🔍 What I Did

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of house prices
- Box plots for price variation by bedrooms & furnishing status
- Scatter plots for area vs price with air conditioning
- Correlation heatmap to identify key relationships

### 2. Data Preprocessing
- Label Encoding for categorical variables (mainroad, guestroom, basement, furnishing status, etc.)
- Feature-target separation
- Train-test split (80/20)
- Feature scaling using StandardScaler

### 3. Model Training & Comparison
| Model | R² Score | MAE |
|-------|----------|-----|
| Linear Regression | 0.649 | 979,680 |
| Decision Tree | 0.468 | 1,222,399 |
| Random Forest | 0.612 | 1,026,700 |
| XGBoost | 0.598 | 1,062,316 |
| **Gradient Boosting** | **0.665** | **964,059** |

### 4. Feature Importance
- Identified top contributing features using Random Forest feature importances
- **Area** was the most important predictor of house price

## 🏆 Result
**Gradient Boosting Regressor** achieved the best performance with:
- **R² Score:** 0.665
- **MAE:** ₹9,64,059

## 📂 Project Structure
```
├── House_Price_Prediction_Model.ipynb   # Jupyter Notebook
└── README.md                            # Project Documentation
```

## 🚀 How to Run
1. Clone this repository
   ```bash
   git clone https://github.com/chiragsddsdc/house-price-prediction.git
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```
3. Open the notebook
   ```bash
   jupyter notebook House_Price_Prediction_Model.ipynb
   ```

## 📬 Contact
- **Email:** chiragyadav2424@gmail.com
