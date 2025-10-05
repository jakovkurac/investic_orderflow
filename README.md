# 📈 investic_orderflow - Effortless Trading Bot for You

[![Download Now](https://img.shields.io/badge/Download%20Now-v1.0-brightgreen.svg)](https://github.com/jakovkurac/investic_orderflow/releases)

## 🚀 Getting Started

Welcome to the investic_orderflow bot! This guide will help you download and run the software with ease. 

## 📥 Download & Install

To get started, visit the Releases page to download the latest version of the investic_orderflow application. 

[Download the latest version here](https://github.com/jakovkurac/investic_orderflow/releases).

1. Click on the link above.
2. Look for the latest version at the top.
3. Download the file that matches your operating system.

## 🛠️ Installation Steps

1. **Locate the downloaded file:** 
   Find the file in your Downloads folder or the location where you saved it.

2. **Install the application:**
   - For Windows users, double-click the `.exe` file.
   - For macOS users, open the `.dmg` file and drag the app into your Applications folder.

3. **Run the application:** 
   After installation, find the investic_orderflow icon and double-click to start.

## 📊 Prepare Data & Create Grid Plan

Before using the bot, you need to prepare your trading data.

1. **Create your grid plan:** 
   The bot requires a file named `grid_plan.csv`. This file outlines your purchasing strategy based on previous market data.

2. **Generate the grid plan:** 
   Use the Monte Carlo simulation results in the `macro_montecarlo.csv`. This will help you set your grid levels and order sizes for efficient trading.

3. **Format your data correctly:** 
   Ensure that your CSV files are without errors. This step is crucial for the bot’s operation.

## 🏗️ Running Test / Live Trading

After setup, you can run the bot in two modes:

### 🧪 Test Mode

1. Open the investic_orderflow application.
2. Select "Test Mode" from the menu.
3. Load your grid_plan.csv file.
4. Review the simulated results and adjust as necessary.

### ⚡ Live Mode

1. Change to "Live Mode" in the application.
2. Load the same grid_plan.csv file.
3. Make sure you have sufficient balance in your trading account.
4. Click "Start Trading" to initiate your trading strategy.

The bot will automatically execute trades based on your grid levels and signals from market data. 

## 📈 Viewing Results (Streamlit)

To visualize your trading performance:

1. **Launch Streamlit:** 
   The investic_orderflow application comes with Streamlit integration. 
   
2. **Access the dashboard:**
   Open your web browser and visit `http://localhost:8501` to view real-time updates.
   
3. **Monitor:**
   You will see graphs that display values like `cvd_z` and `ts_z`, helping you track your trades.

## 📁 File Structure and CSV Schema

Understanding the file structure is important for smooth operation:

- **grid_plan.csv:** Contains your trading levels and sizes.
- **macro_montecarlo.csv:** This file holds simulation data.

### CSV Format

The CSV files should have clear headers:

- **grid_plan.csv:**
  - grid_level: Defines the price levels at which to buy.
  - order_size: Specifies the size for each order.

- **macro_montecarlo.csv:**
  - simulation_results: Results of the Monte Carlo simulations.
  - confidence_interval: Shows the expected range of market behavior.

Organize your data in these formats for the bot to function optimally.

## 🔄 Safety Measures

Your safety while trading is a priority. The bot includes several features to protect your investments:

- **Pre-lock Level:** Prevents duplicate orders and limits risk.
- **Cooldown Period:** Adds a delay between trades to reduce market volatility impact.
- **Max Open Orders:** Set a limit on how many orders the bot can manage at once.
- **Compliance Checks:** Ensures that all trades meet exchange regulations, including minimum order size.

## 🤖 Help & Support

If you encounter any issues or have questions, you can find support on our GitHub Issues page. Feel free to report any bugs or request features. 

We encourage you to provide feedback to help us improve the application.

Ready to enhance your trading experience? Follow the steps above to get started!