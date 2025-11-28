# Stock-Price-Analysis

📈 Stock Price Prediction & Analysis Web App
🔥 Powered by LSTM Deep Learning Model + Flask

This project is an end-to-end Stock Price Prediction and Analysis Web Application that uses a trained LSTM (Long Short-Term Memory) deep learning model to forecast stock trends based on historical market data.
It also visualizes essential technical indicators such as EMA 20, 50, 100, 200 and generates Actual vs Predicted graphs.

Built using: Python, Flask, Keras, yFinance, Matplotlib, NumPy, Pandas
Team Members: Rani Amin, Smruti Katariya

🚀 Features

✔ Fetches real-time stock data using yFinance
✔ LSTM-based future stock price prediction
✔ EMA trend visualization (20, 50, 100, 200)
✔ Actual vs Predicted graph comparison
✔ Auto-generates downloadable CSV file
✔ Clean, simple, user-friendly web interface
✔ Flask-based backend + HTML/CSS/JS frontend
✔ Error handling for invalid stock symbols

📂 Project Structure
📁 Stock-Price-Prediction/
│── app.py                      # Flask application backend
│── stock_dl_model.h5           # Trained LSTM model
│── STOCK_PRICE.ipynb           # Model training notebook
│── templates/
│   └── index.html              # Frontend UI
│── static/
│   ├── ema_20_50.png           # Auto-generated graphs
│   ├── ema_100_200.png
│   ├── pred_vs_actual.png
│   └── <stock>_data.csv
│── requirements.txt            # All required libraries
│── README.md                   # Project description

🧠 Tech Stack
Component	Technology Used
Frontend	HTML, CSS, JS
Backend	Flask
Model	LSTM (Keras)
Data Source	yFinance API
Visualization	Matplotlib
Data Processing	NumPy, Pandas
Scaling	MinMaxScaler
▶ How to Run the Project Locally
Step 1: Clone this repository
git clone <your_repo_url>

Step 2: Install dependencies
pip install -r requirements.txt

Step 3: Add the trained model

Place the file stock_dl_model.h5 in the project folder.

Step 4: Run the Flask server
python app.py

Step 5: Open in your browser
http://127.0.0.1:5000/

📊 Output Preview
1️⃣ EMA Trend Charts (20, 50)

📌 Automatically generated after prediction
(Insert screenshot here)

2️⃣ EMA Trend Charts (100, 200)

(Insert screenshot here)

3️⃣ Actual vs Predicted Stock Price

(Insert screenshot here)

🧩 How the Model Works

The LSTM model was trained on:

10 years of stock price data

Closing price as the primary feature

100-day historical window

MinMax scaled dataset

70% training, 30% testing

The trained model predicts future values which are then inverse-scaled to actual prices.

🌟 Future Enhancements

🚀 Add RSI, MACD, Bollinger Bands
🚀 Add multi-stock comparison dashboard
🚀 Deploy the app on Render / Railway / AWS
🚀 Add Buy/Sell/Hold suggestion system
🚀 Build a React or Streamlit frontend

🤝 Team Members

👩‍💻 Rani Amin
👩‍💻 Smruti Katariya

📬 Feedback & Contributions

Feel free to open issues or submit pull requests.
Suggestions and improvements are always welcome!
