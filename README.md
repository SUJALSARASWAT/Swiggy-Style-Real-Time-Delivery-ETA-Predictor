# 🚚 Swiggy-Style Real-Time Delivery ETA Predictor

**A machine learning-powered application that predicts food delivery times in Delhi using order details, restaurant info, and live weather & traffic data.**  
Built to simulate the type of ETA prediction systems used by companies like Swiggy.

---

## 📌 Features
- **ML Model**: Random Forest Regression trained on synthetic but realistic order datasets.
- **Live APIs**:  
  - [OpenWeatherMap API](https://openweathermap.org/api) for current temperature & weather conditions.  
  - [TomTom Routing API](https://developer.tomtom.com/) for real-time traffic delay data.
- **Metrics**: RMSE ~2.97 mins | MAE ~2.25 mins
- **Deployment**: Interactive [Gradio](https://gradio.app/) web app with public share link for demos.

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn, Requests, Gradio)
- **APIs**: OpenWeatherMap, TomTom Routing
- **Deployment**: Gradio in Google Colab

---

## 🚀 How to Run Locally
1. **Clone this repo**:
   ```bash
   git clone https://github.com/YOUR_USERNAME/eta-predictor.git
   cd eta-predictor
