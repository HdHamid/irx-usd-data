# irx-usd-data
Historical price data of Tehran Stock Exchange symbols converted to USD using updated exchange rates.

# TSE to USD Data 📈💵

Historical price data of Tehran Stock Exchange (TSE) symbols, converted to USD using daily exchange rates.

داده‌های تاریخی نمادهای بورس تهران، تسعیرشده به دلار با نرخ ارز به‌روز (آزاد). این پروژه برای تحلیلگران، پژوهشگران و توسعه‌دهندگانی طراحی شده که نیاز به داده‌های دلاری از بازار سرمایه ایران دارند.

---

## 📦 Features

- Daily adjusted prices of TSE symbols (OHLC + volume)
- Converted to USD using up-to-date exchange rates
- Ready for analysis in Python, R, Excel, or any data science tool
- Open-source, regularly updated

---

## 📊 Structure

Each symbol CSV contains:

| NmdID       | NmdNam | Endt     | PrsnDte   | ClosePrc | UsdPrice | AvgUsdPrice | MinNormalPrice | MaxNormalPrice |
|-------------|--------|----------|-----------|----------|----------|-------------|----------------|----------------|
| 3           |	kemase |2017-06-18|	1396/03/28|	281.00	 |0.00749333|0.01018808633|0.00091139447486|0.01946477820017|
---

## 🔁 Update Schedule

Data is updated **daily or weekly** based on market availability and rate sources.

---

## ⚙️ How It Works

1. Raw TSE data is fetched (from Codal, TSETMC, or manual sources).
2. Exchange rates (free market or NIMA) are retrieved or scraped.
3. Prices are converted: `USD_Price = IRR_Price / FX_Rate`
4. Data is saved in CSV format per symbol.

---

## 💡 Use Cases

- Cross-market comparisons (Iran vs global)
- USD-based technical analysis
- Inflation & currency-adjusted portfolio modeling
- Academic or economic research

---

## 📥 Download & Use

You can download individual CSV files from the `/data/usd/` folder or clone the entire repo:

```bash
git clone https://github.com/your-username/tse-usd-data.git


