# Stock_Analysis
# Stock Performance Dashboard – README

## 📌 Problem Statement
The Stock Performance Dashboard provides a comprehensive visualization and analysis of the Nifty 50 stocks’ performance over the past year. It utilizes daily stock data (open, close, high, low, and volume) to generate insights and highlight key metrics.

The goal is to clean, transform, and visualize stock data, offering investors, analysts, and enthusiasts an interactive dashboard via Streamlit and Power BI for informed decision-making.

---

## 💼 Business Use Cases

1. **Stock Performance Ranking**  
   Identify the top 10 best-performing (green) and top 10 worst-performing (red) stocks over the past year.

2. **Market Overview**  
   Provide a summary of market trends including average performance and green/red stock ratio.

3. **Investment Insights**  
   Detect stocks with consistent growth or steep declines for informed portfolio decisions.

4. **Decision Support**  
   Offer insights on average prices, volatility, and behavioral trends for retail and institutional investors.

---

## 🔍 Approach

### 1. Data Extraction & Transformation
- Source Format: YAML files organized by months and dates.
- Objective: Convert the YAML data into CSV format for analysis.
- Result: 50 CSV files, each representing a specific stock/symbol.

---

## 📊 Data Analysis & Visualization Features

### 1. Volatility Analysis
- **Objective**: Identify price fluctuations using standard deviation of daily returns.
- **Metric**: `Volatility = std(dev) of daily returns`
- **Visualization**: Bar chart showing top 10 most volatile stocks.

### 2. Cumulative Return Over Time
- **Objective**: Visualize overall stock performance from start to end of the year.
- **Metric**: Cumulative Return = running total of daily percentage changes.
- **Visualization**: Line chart for top 5 stocks with the highest cumulative returns.

### 3. Sector-wise Performance
- **Objective**: Analyze average performance across different sectors.
- **Metric**: Average yearly return per sector.
- **Visualization**: Bar chart showing sector-wise average returns.

### 4. Stock Price Correlation
- **Objective**: Identify relationships between stock movements.
- **Metric**: Pearson correlation coefficient of closing prices.
- **Visualization**: Heatmap of stock-to-stock correlation matrix.

### 5. Monthly Top 5 Gainers and Losers
- **Objective**: Provide monthly breakdown of top performers and underperformers.
- **Metric**: Monthly return percentage.
- **Visualization**: 12 sets of bar charts (per month) showing top 5 gainers and losers.

---

## 🧰 Tools & Technologies
- **Python (Pandas, Matplotlib, Seaborn)** – for data processing and visualizations
- **Streamlit** – for building an interactive web dashboard
- **Power BI** – for business-friendly dashboarding and drill-down analysis
- **SQL / MySQL** – for structured data querying and backend storage
- **YAML/CSV** – for input and processed data formats

---

## 📁 Directory Structure (Recommended)

