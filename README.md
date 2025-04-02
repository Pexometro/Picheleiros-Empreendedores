# Crypto Basket Price Predictor – 1st Place Hackathon Project

This project was developed during a 48-hour Hackathon organized for Uphold, under the theme: "Crypto Basket Price Predictor".
We are proud to announce that our solution won 🥇1st place in this challenge!

## Authors

- Rui Pinto - PG56010 - [RuiPintoUM](https://github.com/RuiPintoUM)
- Pedro Azevedo - PG57897 - [Pexometro](https://github.com/Pexometro)
- Luís Costa - PG55970 - [jluis02](https://github.com/jluis02) 


## Overview 

Crypto Basket Price Predictor is a machine learning-powered application that predicts the next-day closing price of a custom crypto basket. The basket is composed of selected cryptocurrencies (e.g., BTC, ETH, SOL, etc.), weighted by user-defined proportions.

This tool combines technical analysis (like RSI and Moving Averages) with sentiment indicators (like the Fear & Greed Index) to help users better understand crypto market movements and anticipate price fluctuations with greater accuracy.

![image](https://github.com/user-attachments/assets/f04ae55e-c172-4522-90b4-e5a1870b4c34)

![image](https://github.com/user-attachments/assets/2c3e5f0b-4515-4811-a6e8-ac8a9da6d763)

![image](https://github.com/user-attachments/assets/66d16b6b-0f43-4975-a3c7-eff724a68394)

## Why it stands out

- 🥇 **Hackathon Winner** – Built in 48 hours for Uphold, delivering real insights for real users.

- 🧠 Uses **ML models** (AdaBoost & XGBoost) trained on enriched, real-world data.

- 🪙 **Predicts price** of custom crypto baskets, not just individual coins.

- 🔍 Integrates Fear & Greed Index as a sentiment feature.

- 📅 **Tags important events** like election days that may trigger price spikes.

- 📈 **Full visualizations** for real vs predicted prices, RSI, and MA.


## Tech Stack

- **Data prep** - Python, Pandas, NumPy

- **Machine learning** - Scikit-Learn, XGBoost, AdaBoost

- **Visualization** - Matplotlib

- **Prototyping** - Jupyter Notebook

## How It Works

- Download **historical data** for key cryptocurrencies.

- **Combine** them into a weighted **basket price**.

- Calculate indicators like **RSI and MA14**.

- Merge external sentiment data (Fear & Greed Index).

- **Train ML models** to predict next-day closing price.

- **Evaluate performance** with RMSE and MAE.

- **Visualize predictions** and market indicators together.

## How to run  

To run the full project locally (both backend and frontend):

### Backend (API)

Navigate to the backend folder and run :
```
python3 api.py
```

This will start a local server that provides model predictions via a REST API.

### Frontend (Dashboard)

In a separate terminal, navigate to the cryptodashboard folder and run:
```
npm install
```
for the dependencies and then
```
npm run dev
```

to start the server.
This will launch the dashboard in your browser (usually at http://localhost:3000).


# Special Thanks

This project was created with the goal of helping users better navigate and predict crypto market behavior. Huge thanks to the organizers and mentors for their support and feedback during the hackathon!





