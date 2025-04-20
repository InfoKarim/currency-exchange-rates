# 💱 Currency Exchange Rates Dashboard

A simple data science project that fetches and visualizes live exchange rates against the US Dollar 💵 using an external API and Python. It focuses on popular currencies like EGP, SAR, AED, GBP, EUR, and JPY.

---

## 📊 Overview

| Feature      | Description                                          |
|--------------|------------------------------------------------------|
| 🧠 Language   | Python                                               |
| 📦 Libraries | `requests`, `matplotlib`, `pandas`                   |
| 📡 API       | `https://v6.exchangerate-api.com`                    |
| 🌍 Base      | USD (U.S. Dollar)                                    |
| 📈 Output     | CSV + PNG chart with major currency exchange rates  |

---

## 📁 Project Structure

```
currency-exchange-project/
│
├── data/
│   └── exchange_rates.csv        # Cleaned exchange rates data
│
├── output/
│   └── exchange_rates_chart.png  # Bar chart of exchange rates
│
├── exchange_api.py               # Python script to fetch & plot
└── README.md                     # This file
```

---

## 🖼️ Sample Output

### 💹 Exchange Rate Chart (vs USD)
![Exchange Rate Chart](output/exchange_rates_chart.png)

---

## 🧪 How It Works

1. Connects to a free exchange rate API using `requests`
2. Filters major currencies: `EGP`, `SAR`, `AED`, `GBP`, `EUR`, `JPY`
3. Saves results as `.csv`
4. Plots horizontal bar chart using `matplotlib`

---

## 🧬 Future Enhancements

- Add multi-currency comparison over time
- Deploy with Streamlit as a live dashboard
- Connect to historical exchange data

---

## 📬 Contact

**Karim Elsayed**  
📧 info.karimelsayed@gmail.com  
🌐 [Portfolio Website](https://infokarim.github.io)  
🐙 [GitHub Profile](https://github.com/InfoKarim)

---

> Built with Python & ☕ – because data never sleeps.