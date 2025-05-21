# ✈️ Airline Booking Prediction using Machine Learning

This project is a predictive modeling solution aimed at helping airlines better anticipate customer booking behavior. With access to 50,000 customer records, I built a machine learning pipeline that determines the likelihood of a customer completing a booking based on various behavioral and transactional features.

---

## 💡 Project Objective

Customers are more empowered than ever with real-time access to information. By the time they arrive at an airport, most booking decisions are already made. This project helps airlines shift from being reactive to proactive—using data-driven insights to target potential customers **before** they finalize their travel plans.

---

## 🚀 Project Workflow

1. **Data Exploration & Cleaning**  
   - Checked missing values, data types, and descriptive statistics.
   - Created new features from existing ones (e.g., origin and destination airports from the route).
   - Detected and visualized outliers using box plots.

2. **Feature Engineering**  
   - Encoded categorical variables using one-hot encoding.
   - Removed redundant or less informative features.

3. **Model Training & Evaluation**  
   - Used **Random Forest Classifier** for prediction.
   - Evaluated performance with accuracy, AUC, confusion matrix, and classification report.
   - Applied **cross-validation** for reliability.

4. **Feature Importance Analysis**  
   - Visualized the top features influencing booking decisions.

---

## 📊 Dataset Overview

- **Rows**: 50,000
- **Target**: `booking_complete` (1 = booked, 0 = not booked)
- **Features**:  
  - Sales channel, trip type, flight day/hour  
  - Booking origin, flight route  
  - Extra services requested (meals, baggage, seat)  
  - Lead time, length of stay, number of passengers

---

## 🔍 Key Results

- **Training Accuracy**: 99.98% (as expected, high due to overfitting)
- **Test Accuracy**: 85.57%
- **Top Influential Features**:
  - Purchase lead time
  - Flight hour
  - Length of stay
  - Request for extra baggage or meals
  - Number of passengers

---

## 📈 Evaluation Metrics

- **Precision** for bookings: 55%
- **Recall** for bookings: 14% (indicates opportunity for further optimization)
- **AUC Score**: 0.56
- **Cross-Validated Accuracy**: 84.92%

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

