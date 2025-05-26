# 📊 S&P 500 Stock Analysis Dashboard  
**Track price trends, volatility, and momentum of S&P 500 companies with Python + Tableau**

---

## 📁 Dataset  
- Source: [Kaggle – S&P 500 Stock Data]([https://www.kaggle.com/](https://www.kaggle.com/datasets/keehyung/mit5742-sp500-stock-value-dataset))  
- Contains historical stock data for 500+ companies including Open, High, Low, Close, Adj Close, and Volume.

---

## 🧪 Project Overview  

This project analyzes historical stock data for S&P 500 companies and presents a dynamic Tableau dashboard that supports cross-company insights. The analysis includes outlier detection, trend indicators, volatility tracking, and performance comparisons.

---

## ⚙️ Key Features & Visual Insights

### 1. 🧼 Outlier Detection  
Cleaned the dataset using **IQR filtering** to remove extreme price values before generating indicators.  

> ![Boxplot](images/boxplot0.png)  
> ![Boxplot After IQR](images/boxplot1.png)  
> *Boxplots showing stock price distributions before and after outlier removal.*

---

### 2. 📈 Moving Averages (MA7, MA30)  
Calculated **7-day** and **30-day** moving averages to smooth price trends and highlight momentum.

> ![Close Price with MA](images/close.png)  
> *Closing price overlaid with MA7 and MA30 for a selected company.*

---

### 3. 💪 Relative Strength Index (RSI)  
Computed **RSI** to capture overbought and oversold conditions across stocks.

> ![RSI Chart](images/rsi.png)  
> *RSI values with horizontal reference lines at 30 and 70.*

---

### 4. 🌪️ 21-Day Rolling Volatility  
Tracked short-term risk by calculating **rolling standard deviation** of closing prices.

> ![Volatility Plot](images/volatility.png)  
> *Rolling volatility over time, used to assess stock stability.*

---

## 📊 Tableau Dashboard  

An interactive Tableau dashboard allows users to:
- Select companies via dropdown filter
- Compare Close price trends, RSI, Volatility, and % Change
- Instantly view:
  - 🟢 Top Gainer  
  - 🔴 Most Volatile  
  - 📈 Highest RSI  

🔗 **[View Dashboard on Tableau Public](your-tableau-link-here)**

---

## 🧰 Technologies Used  
- **Python**: pandas, numpy, matplotlib, seaborn  
- **Jupyter Notebook**: for preprocessing, outlier handling, and indicator calculations  
- **Tableau Public**: for dynamic multi-metric visualization  
- **Data Source**: Kaggle

---

## 🚀 How to Reproduce  
1. Clone this repo  
2. Run `analysis.ipynb` to preprocess and generate indicators  
3. Open `sp500_dashboard.twb` in Tableau Public  
4. Load `sp500.csv` as data source  
5. Interact with filters and metrics in dashboard view

---

## 📎 License  
MIT License

---

## 📬 Contact  
Created by *[Your Name]* — feel free to reach out on [LinkedIn/GitHub link]
