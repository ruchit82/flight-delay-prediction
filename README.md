
# ✈️ Flight Delay Prediction using Machine Learning

This project predicts whether a flight will be delayed by 15 minutes or more using historical flight data from the US Department of Transportation. The goal is to help airlines and airport authorities improve decision-making and passenger satisfaction through proactive delay management.

---

## 📌 Project Objective

To build a classification model that accurately predicts flight delays using pre-departure data such as airline, scheduled departure time, origin/destination airport, and day of the week. The project also explores key delay trends and insights via data visualizations.

---

## 🛠️ Tools & Technologies

- **Languages**: Python
- **Libraries**: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
- **Notebook**: Jupyter Notebook
- **(Optional)**: Power BI / Streamlit (for dashboard integration)

---

## 📁 Project Structure


---

## 🧠 Problem Definition

Delays are a common and costly issue in the airline industry. Being able to predict delays ahead of time allows for:
- Better operational planning
- Improved customer communication
- Efficient resource allocation at airports

This model helps identify patterns and predict the likelihood of a delay ≥ 15 minutes.

---

## 📊 Exploratory Data Analysis

Some of the EDA insights include:
- Delay distributions by **airline**, **airport**, and **day of week**
- Common causes of delays (weather, carrier, NAS, etc.)
- Class imbalance in delay vs. on-time flights

> 📸 *See `images/` folder for sample visualizations.*

---

## 🤖 Machine Learning Model

- **Model Used**: Logistic Regression, Random Forest Classifier
- **Target Variable**: Binary delay (1 = Delayed ≥15 mins, 0 = On time)
- **Features**:
  - Airline carrier
  - Scheduled departure time
  - Day of the week
  - Origin and destination airports
- **Evaluation Metrics**:
  - Accuracy
  - Precision / Recall
  - Confusion Matrix
  - ROC-AUC

---

## 📈 Business Impact

This model can be used to:
- Alert gate/ground staff about expected delays
- Re-route staff/resources in high-risk delay periods
- Inform customers ahead of time and reduce dissatisfaction
- Build a foundation for real-time predictive dashboards

---

## 📚 Dataset

- Source: [Kaggle – US DOT Flight Delay Dataset](https://www.kaggle.com/datasets/usdot/flight-delays)
- Size: 5.8M+ records
- Fields include: Flight Date, Carrier, Origin, Destination, Delay Reasons, Weather, Departure Times

---

## 📌 Future Improvements

- Integrate live weather data using APIs (OpenWeather)
- Build real-time delay prediction app with Streamlit
- Optimize model with advanced classifiers (e.g., XGBoost, LightGBM)
- Add airport traffic, holidays, and seasonality data

---

## 🙋‍♂️ Author

**Ruchit Sanap**  
🎓 Bachelor's in Data Science & Business Analytics  
💼 Aspiring Data Analyst 
📫 ruchitsanap00@gmail.com 
🔗 [LinkedIn Profile]

---

## ✅ License

This project is open source and available under the [MIT License](LICENSE).
