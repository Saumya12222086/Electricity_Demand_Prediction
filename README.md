🔌 Electricity Demand Prediction for Delhi

🌟 Overview

Hey there! This project is all about predicting Delhi's electricity demand using a mix of historical consumption data and real-time weather data. We pull past electricity demand from the State Load Dispatch Center (SLDC) website using web scraping and grab weather details via an API. With this data, we train a machine learning model to forecast future electricity needs—helping power planners make smarter decisions. ⚡📊

🚀 Features

Web Scraping: Automatically fetches past electricity demand from SLDC.

Weather API Integration: Gets real-time weather updates to factor in temperature, humidity, etc.

Data Preprocessing: Cleans, merges, and prepares the data for modeling.

Machine Learning Model: Learns from past trends to predict future electricity usage.

Visualization: Shows cool graphs and insights into electricity demand trends.

🛠 Tech Stack

Language: Python 🐍

Libraries & Tools:

pandas, numpy – Data wrangling

scikit-learn – Machine learning magic ✨

matplotlib, seaborn – Pretty charts & graphs 📊

requests – API calls for weather data 🌤

BeautifulSoup – Web scraping for SLDC demand 📡

Flask (if deployed) – Web-based predictions 🖥

📦 Data Collection

Electricity Demand Data:

Scraped from the SLDC website.

Includes past electricity consumption records.

Weather Data:

Fetched via an API (openmeteo).

Covers temperature, humidity, wind speed, and precipitation.

🧠 Model Training

Data is preprocessed to fix missing values and inconsistencies.

We create time-based features to capture demand patterns.

A machine learning model (Random Forest, XGBoost, or LSTM) is trained to predict future electricity demand.

Performance is evaluated using RMSE and R² scores.

🔮 Prediction Flow

Get fresh weather data from the API.

Scrape the latest electricity demand from SLDC.

Merge and preprocess the data.

Use the trained model to forecast electricity demand.

Display results in tables & charts for easy interpretation.

🌍 Deployment 
We first tested the deployment using Gradio for quick and interactive model evaluation.

Later, we deployed it on our own machine for real-time predictions.

🏗 Installation & Usage

Prerequisites

Make sure you have Python 3.8+ and install the required packages:

pip install pandas numpy scikit-learn requests beautifulsoup4 flask matplotlib seaborn

Running the Project

python main.py

API & Web Scraping Setup

Add your weather API key in config.py.

Adjust scraper.py if the SLDC site structure changes.

🚀 Future Enhancements

Improve accuracy using deep learning (LSTMs, Transformers, etc.).

Automate data collection & model retraining.

Build a web dashboard for interactive visualizations.

👨‍💻 Contributors

Saumya Singh – ML Engineer & Developer

📜 License

This project is licensed under the MIT License.

📩 Contact

Got questions or suggestions? Open an issue on GitHub or drop me an email at iamsaumya05@gmail.com. 🚀


the link for the project is this 

https://drive.google.com/drive/folders/1WvFeH-qymalJtxoMadHRcFpS7zITM0Xh
