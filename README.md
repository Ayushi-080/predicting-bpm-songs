# 🎵 Predicting BPM of Songs | Kaggle Playground S5E9

## 📖 Project Overview

This project is my take on the **Kaggle Playground Series – Season 5, Episode 9**, where the challenge was to **predict the Beats Per Minute (BPM)** of songs based on their audio features.
I approached it as a complete **end-to-end machine learning pipeline**, transforming raw tabular data into meaningful predictions — almost like turning data into music.  
From **EDA and feature engineering** to **model tuning and evaluation**, every step was a performed carefully.

---

## 🚀 Step-by-Step Journey

### 1️⃣ Exploring the Data
I began by diving into the dataset — understanding distributions, correlations, and hidden rhythms behind the numbers.  
📊 Used **Pandas**, **NumPy**, and **Seaborn** to visualize trends and spot patterns in acoustic features.

### 2️⃣ Feature Engineering
To prepare the data for modeling:
- Encoded categorical variables like song type and genre 🎼  
- Normalized and scaled numerical columns  
- Experimented with removing outliers that created “noise” in the data  

### 3️⃣ Model Building & Tuning
I tested and compared multiple models:
- **Linear Regression** – as a baseline  
- **Random Forest Regressor** – for non-linear feature handling  
- **XGBoost** & **CatBoost** – for optimized gradient boosting performance  

🧩 Finally, **CatBoost** gave the best results, handling categorical variables elegantly and producing smooth predictions.

### 4️⃣ Evaluation
Evaluated models using **Root Mean Squared Error (RMSE)** to measure prediction accuracy.  
Visualized residuals to ensure the model didn’t “overfit” to any specific tempo range.

🎯 **Result:** Achieved a strong performance with low RMSE, showing the model learned real BPM patterns effectively.

---

## 📈 Insights & Learnings

🔹 **Feature Importance:**  
Energy, loudness, and tempo emerged as key predictors of BPM — proving how acoustic intensity relates directly to rhythm.

🔹 **Takeaways:**  
- Learned how even synthetic tabular datasets can represent real-world musical patterns.  
- Strengthened intuition around model interpretability & cross-validation.  
- Improved hands-on experience with hyperparameter tuning & performance benchmarking.

---

## 🧠 Skills Demonstrated

| Area | What I Did |
|------|-------------|
| **Data Exploration & Cleaning** | Explored data patterns using Pandas & Seaborn |
| **Feature Engineering** | Encoded categorical features, scaled and normalized data |
| **Model Development** | Implemented and tuned Linear, RF, XGBoost & CatBoost models |
| **Evaluation** | Compared models via RMSE, analyzed residuals |
| **Visualization** | Created correlation maps & feature importance plots |
| **End-to-End ML Pipeline** | Built complete workflow from raw data → prediction → submission |

---

## ⚙️ Tech Stack

**Languages & Tools:** Python 🐍, Jupyter Notebook 📓  
**Libraries:** Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · XGBoost · CatBoost  
**Environment:** Kaggle Notebooks / Local Jupyter  

---

## 💡 Reflections

Working on this project felt like balancing **data and rhythm** —  
each feature had its own beat, and tuning the model was like composing harmony between **noise and signal**.  

It wasn’t just about predicting numbers — it was about learning to **listen to the data**.  
This challenge helped me strengthen my analytical thinking and storytelling with data, both essential for real-world ML roles.

---

## 👩‍💻 Author

**Ayushi Mittal**  
🎓 M.Tech in Computer Science (Artificial Intelligence)  
👩‍🏫 Data Scientist | Data Analyst | 🧠 Machine Learning & Data Science Enthusiast  

🌐 [GitHub Profile](https://github.com/Ayushi-080)  
📊 [Kaggle Profile](https://www.kaggle.com/pihu09876)  
💌 Open to collaborations and data-driven opportunities  

---

⭐ *If you enjoyed this project or found it insightful, feel free to star the repo and connect!*
