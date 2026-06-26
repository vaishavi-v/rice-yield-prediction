# rice-yield-prediction
Global rice yield analysis and prediction with Sri Lanka focus using Random Forest (R² = 0.94)
# 🌾 Global Rice Yield Analysis & Prediction
> Predicting rice crop yield using weather and agricultural data  
> with a special focus on Sri Lanka 🇱🇰

---

## 📌 Project Overview
This project analyzes global rice yield data across 70+ countries 
from 1990–2013 and builds a machine learning model to predict crop 
yield based on rainfall, temperature, and pesticide usage.

The project highlights Sri Lanka's rice production trends and 
demonstrates how weather conditions impact yield — with actionable 
insights for farmers and policymakers.

---

## 🔍 Key Findings
- Sri Lanka's rice yield shows a clear **upward trend** from 1990 to 2013
- **Optimal conditions** for maximum yield: ~1800mm rainfall, ~27°C temperature
- Both drought AND excessive rainfall **negatively impact** yield
- Random Forest outperformed Linear Regression significantly (R² 0.18 → 0.94)

---

## 🤖 Model Results

| Model | R² Score | MAE | RMSE |
|---|---|---|---|
| Linear Regression | 0.1849 | 13,316 hg/ha | 17,581 hg/ha |
| Random Forest | **0.9414** | 2,684 hg/ha | 4,714 hg/ha |

---

## 🔮 Sample Predictions (Sri Lanka)

| Scenario | Rainfall | Temp | Predicted Yield |
|---|---|---|---|
| Drought Year | 800mm | 30°C | 4.05 tonnes/ha |
| Normal Year | 1800mm | 27°C | **5.32 tonnes/ha** |
| Heavy Rainfall | 2800mm | 25°C | 3.67 tonnes/ha |
| Ideal Conditions | 2000mm | 26°C | 3.79 tonnes/ha |

---

## 🛠️ Tech Stack
- **Python 3**
- **Pandas** — data cleaning & analysis
- **Matplotlib & Seaborn** — visualizations
- **Scikit-learn** — machine learning models
- **Google Colab** — development environment

---

## 📊 Dataset
- **Source:** [Crop Yield Prediction Dataset — Kaggle](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset)
- **Size:** 28,242 rows across 70+ countries
- **Features:** Rainfall, temperature, pesticides, crop type, year
- **Target:** Crop yield (hg/ha)

---

## 🚀 How to Run
1. Open [Google Colab](https://colab.research.google.com)
2. Upload `yield_df.csv` to Colab files
3. Open `student_performance_analysis.ipynb`
4. Run all cells top to bottom

---

## 💡 Real World Impact
This model can help:
- 🧑‍🌾 **Farmers** plan planting seasons based on weather forecasts
- 🏛️ **Governments** anticipate food supply and prepare imports
- 🏦 **Agricultural banks** assess loan risk based on predicted harvest

---

## 👩‍💻 Author
**Vaishavi**  
BSc (Hons) Information Technology — Data Science  
SLIIT, Sri Lanka  
LinkedIn:www.linkedin.com/in/vaishaviindreshan
GitHub:https://github.com/vaishavi-v
