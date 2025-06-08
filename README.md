# Excel Trading Analysis – FinTrack Solutions

📊 This project presents a structured analysis of stock trading operations for FinTrack Solutions, using Excel. The goal was to turn a raw spreadsheet into a dynamic tool for performance tracking and strategic insight.

## 🎯 Objective

Transform a static Excel sheet into a structured and visual dashboard that helps understand:

- Trading profits over time
- Trade duration distributions
- Exchange-level insights
- Risk and taxation patterns

## 📁 Dataset

The dataset contains trading transactions carried out by Bob since January 1st, 2021.  
[📥 Download Source Dataset](https://proai-datasets.s3.eu-west-3.amazonaws.com/tradesonexchanges.xlsx)

### Key columns:
- **TradeID**: unique ID of each trade  
- **Stock Exchange**: where the trade occurred  
- **Region**: geographic region of the exchange  
- **Date Added / Sold**: when the stock was bought and sold  
- **Quantity**  
- **Buy Price / Sell Price**

---

## 📊 Sheets & Analyses

### 1. **My Trades**
- Cleaned and styled table of trades
- Custom formatting for readability

### 2. **Stock Exchanges**
- Pivot table summarizing trades per market & region
- Conditional column to flag trades > 67 units (for tax considerations)

### 3. **Profit Insights**
- Duration of trade in days  
- Calculated profit (quantity × price difference)  
- Histogram of trade durations  
- Notes on distribution pattern

### 4. **Number of Trades Exchanged**
- Contingency table: trade frequency by region  
- Two probability scenarios:
  - UK trade with quantity = 1  
  - Asian trade with quantity ≤ 8

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Pivot Tables, Conditional Formatting
- Custom styles, formulas
- Visualizations (histograms, tables)

---

## 🔗 Author

👩 Giusi Russo – Data Analyst in training  
🎓 Project created during the Data Analytics Master – ProfessionAI  
