# AQI-Predictor




🌫 AQI Prediction Web App

AQI Prediction is a multi-page web application built using Streamlit to display air quality information for locations like Karyavattom, Kollam, and Eloor. The app features an aesthetic sky-themed UI, clean navigation, and custom-styled buttons for a smooth user experience.


---

✅ Features

🌤 Sky-Themed Background for a peaceful, relevant UI

🖱 Styled Buttons with hover effect and shadow

📍 Multi-Page Navigation using st.switch_page()

🗂 Separate Pages for Karyavattom, Kollam, and Eloor

📈 Extendable Design for adding AQI prediction models or live APIs

🔧 Clean Code organized by components for easy updates



---

⚙ How It Works

1. The app starts at aqi_prediction_home.py, displaying the title and location buttons.


2. Users select a location (e.g., Kollam), triggering st.switch_page() to navigate to the respective page (aqi_prediction_kollam.py).


3. Each location page displays a custom message (can later include AQI graphs, data, etc.).


4. Background styling and buttons are customized using embedded CSS.


5. The project is structured to allow easy integration of ML models, APIs, or data visualizations.




---

📁 Project Structure

AQI-Prediction/
├── aqi_prediction_home.py
├── pages/
│   ├── aqi_prediction_kollam.py
│   ├── aqi_prediction_eloor.py
│   └── aqi_prediction_kryvttm.py
├── requirements.txt
└── README.md


---

🚀 How to Run

1. Clone the repo



git clone https://github.com/your-username/AQI-Prediction.git
cd AQI-Prediction

2. Install dependencies



pip install -r requirements.txt

3. Run the app



streamlit run aqi_prediction_home.py



💡 Future Scope

Add live AQI API integration (e.g., OpenWeather, WAQI)

Predict AQI trends using ML models like LSTM or Prophet

Visualize historical AQI with charts and interactive plots

Create user dashboards for tracking air quality over time



👩‍💻 Developed by: Jephy Joseph







