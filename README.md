# Crypto Price Logger

## Overview
**Crypto Price Logger** is a Python-based tool that collects cryptocurrency prices in real-time using Binance WebSocket streams. The coin to track is specified in a `.env` file, and the collected data is saved in a JSON file. This project is designed with modularity and code quality in mind, incorporating tools like **Pylint** for linting.

---

## Features
- Real-time price tracking using Binance WebSocket.
- Configurable coin symbol and output file via `.env`.
- Saves price data with timestamps to a JSON file.
- Includes linting support with **Pylint** for code quality.

---

## Project Structure
crypto-price-logger/ 
├── .env # Environment variables for configuration 
├── .gitignore # Ignored files for Git 
├── README.md # Project documentation 
├── requirements.txt # Python dependencies 
├── src/ │ 
├── main.py # Entry point for the application │ 
├── config.py # Reads configurations from .env 
│ └── logger.py # Implements price logging logic 
├── tests/ 
│ └── test_logger.py # Unit tests for the project 
├── .pylintrc # Configuration file for Pylint


---

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/yourusername/crypto-price-logger.git
cd crypto-price-logger
```
### Set Up the Environment
Create a .env file in the root directory and specify the coin to track and output file:
```bash
COIN_SYMBOL=linkusdt
OUTPUT_FILE=prices.json
```
### Install Dependencies
Use pip to install the required Python packages:
```bash
pip install -r requirements.txt
```

### Run the Application
```bash
python src/main.py
```




