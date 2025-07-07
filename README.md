🏏 IPL Match Outcome Prediction

🔍 **Objective:** Predict the winner of an IPL match using machine learning models based on historical match data.



## 📁 Dataset

- 📌 Source: Uploaded manually (CSV format)
- 💡 Features include:
  - Teams
  - Venue
  - Toss decision
  - Match winner
  - Win by runs/wickets
  - Player of the match

 🧼 Data Cleaning

- ✅ Removed duplicates and null values
- 🧠 Label encoded categorical variables
- 🧹 Removed outliers in `win_by_runs` and `win_by_wickets` using IQR method


 📊 Exploratory Data Analysis (EDA)

- 📌 Toss decision influences match results
- 📈 Certain teams have higher winning probabilities at specific venues
- 🔍 Correlation heatmap shows features affecting outcomes



 🤖 Modeling Process

- ✅ Trained multiple models:
  - Logistic Regression
  - SVM (RBF, Linear)
  - KNN
  - Decision Tree
  - Random Forest
  - XGBoost
- 🔍 Used **GridSearchCV** for hyperparameter tuning




## 🛠️ Final Model

- 📁 Saved as: 
- 🧪 Training Accuracy: 93%
- 🧪 Testing Accuracy: 92%
- 📉 Overfitting reduced via hyperparameter tuning

---

 📈 Improvements & Challenges

 ✅ Suggestions:
- Add player-level features (form, recent performance)
- Include pitch and weather data

### ⚠️ Challenges:
- Imbalanced data (some teams win more often)
- Outliers affecting model performance

---

