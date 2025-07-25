
# ✈️ Flight Delay Prediction Analysis

This project analyzes airline passenger data to build predictive models for determining whether a flight will be delayed. It explores machine learning techniques and visual analytics to uncover delay trends based on passenger demographics, airline routes, and time factors.

---

## 📁 Dataset

**Source:** Public dataset (uploaded manually)

**Filename:** `Airline_Dataset.csv`

**Key Features:**
- `Passenger ID`, `First Name`, `Last Name`
- `Gender`, `Age`, `Nationality`
- `Airport Name`, `Arrival Airport`
- `Departure Date`, `Flight Status`
- `Country`, `Continent`, `Pilot Name`

---

## 🔍 Project Workflow

1. **Load and clean dataset**
2. **Feature engineering**:
   - Extract day, month, and weekday from `Departure Date`
   - Encode categorical variables
3. **Exploratory Data Analysis (EDA)**:
   - Flight delays by age, continent, airline, and time of year
4. **Modeling**:
   - Logistic Regression
   - XGBoost with hyperparameter tuning
   - Neural Network (Keras)
5. **Class imbalance handled** using:
   - `scale_pos_weight` for XGBoost
   - `class_weight` in Keras
6. **Evaluate model performance**
   - Accuracy, precision, recall, F1-score
   - Confusion matrices and classification reports

---

## 📊 Key Insights

1. **Delays are highly imbalanced** – most flights are on time.
2. **Certain airports and continents** show higher delay patterns.
3. **Neural network outperforms basic models** after class weighting.
4. **Monthly and weekday trends** reveal seasonal effects.

Visualizations include:
- Delay rate by age group and continent
- Delay patterns by weekday and month
- Top arrival airports by delay frequency

---

## 🛠 Tools & Libraries

- Python 3.x
- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for machine learning models
- `xgboost` for boosted trees
- `tensorflow.keras` for neural networks

---

## 🧠 How to Use

1. Clone this repository
2. Ensure `Airline_Dataset.csv` is in the same directory
3. Open `Flight_Delay_Prediction_Analysis.ipynb` in Jupyter Notebook or VSCode
4. Run all cells to:
   - Prepare the data
   - Train models
   - View predictions and visualizations

---

## ✅ Output Preview

> 📈 Includes visual analysis of:
- Delay trends by month, weekday, and age group
- Airline performance
- Confusion matrix comparisons across models

---

## 💡 Author

**Santhakumar Ramesh**  
MPS in Data Science and Applications  
University at Buffalo  
[GitHub](https://github.com/Santhakumarramesh)

---
