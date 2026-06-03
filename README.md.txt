# Turbo.az Vehicle Market Analytics

This project is an **End-to-End Data Science solution** designed to scrape, clean, analyze, and visualize data from Turbo.az, Azerbaijan's largest automotive marketplace.

## 🚀 Project Goal
The primary objective of this project is to decode the automotive market dynamics by analyzing price trends, identifying correlations between vehicle features (mileage, engine, year), and developing a statistical model to predict market prices for specific car models.

## 🛠 Tech Stack
* **Language:** Python
* **Web Scraping:** BeautifulSoup, Requests
* **Data Manipulation:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Modeling:** Simple Linear Regression (via NumPy Polyfit)

## 📊 Key Pipeline Phases
1. **Data Acquisition:** Automated web scraping to extract vehicle data from Turbo.az.
2. **Data Cleaning & Engineering:** Handling messy raw data using Regex to extract 'Year', 'Engine', and 'Mileage' as structured, numerical features.
3. **Exploratory Data Analysis (EDA):** Performing deep-dive analysis on yearly price trends and brand distribution.
4. **Correlation Analysis:** Utilizing heatmaps to identify the relationships between car features and market price.
5. **Predictive Modeling:** Applying linear regression to build a price valuation engine for Toyota Prius.

## 📈 Key Insights
* **Price Depreciation:** Visualization of how market price decreases as vehicle mileage increases.
* **Trend Analysis:** Clear insights into how production year impacts the valuation of vehicles.
* **Market Valuation:** A functional model that estimates market prices based on mileage, providing a "value-for-money" perspective for buyers.

## 💡 How to Run
1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn beautifulsoup4 requests