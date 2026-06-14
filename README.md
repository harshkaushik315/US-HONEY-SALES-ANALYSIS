# 🍯 US Honey Sales Analytics (1995–2021)

An exploratory data analysis (EDA) project on US honey production, pricing, and sales trends across 44 states from 1995 to 2021.

---

## 📊 Project Overview

This project analyzes a dataset of US honey production statistics to uncover trends in colony numbers, yield, pricing, and state-level production performance over nearly three decades.

---

## 📁 Dataset

- **File:** `US_honey_dataset.csv`
- **Records:** 1,115 rows × 8 columns
- **Time Period:** 1995 – 2021
- **States Covered:** 44 US states

### Columns

| Column | Description |
|--------|-------------|
| `state` | US state name |
| `colonies_number` | Number of bee colonies |
| `yield_per_colony` | Honey yield per colony (lbs) |
| `production` | Total honey production (lbs) |
| `stocks` | Honey stocks held (lbs) |
| `average_price` | Average price per lb ($) |
| `value_of_production` | Total value of production ($) |
| `year` | Year of record |

---

## 📌 Key Findings

- **North Dakota** is the highest honey-producing state, followed by California and South Dakota
- **Hawaii** has the highest yield per colony (~104 lbs), while Maine has the lowest (~33 lbs)
- **2014** was the most profitable year for US honey production
- States with **high production tend to have lower prices** — a classic supply-side effect (correlation: −0.19)
- **Hawaii's production declined sharply after 2010**, dropping from ~1.3M lbs to under 100K lbs by 2017
- **Virginia** commands the highest average honey price in the 21st century despite low production volume
- **North Dakota consistently outperforms California** in yield per colony, though both show a declining trend in recent years

---

## 📈 Visualizations

The project includes 9 analytical plots:

1. Colonies vs Production (scatter)
2. Production vs Average Price (scatter)
3. Average Honey Production by State (bar)
4. Yield per Colony by State (bar)
5. Total Value of Production by Year (bar)
6. Honey Stocks by State in 2020 (bar)
7. Average Price by State — 21st Century (bar)
8. Hawaii Production Trend Over Time (line)
9. Yield per Colony: North Dakota vs California (line)

---

## 🛠️ Tools & Libraries

- **Python 3**
- **Pandas** — data manipulation
- **Matplotlib** — plotting
- **Seaborn** — statistical visualizations

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/harshkaushik315/us-honey-sales-analysis.git
   cd us-honey-sales-analysis
   ```

2. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. Open the notebook:
   ```bash
   jupyter notebook honey_analysis.ipynb
   ```

---

## 📂 Project Structure

```
us-honey-sales-analysis/
│
├── US_honey_dataset.csv       # Raw dataset
├── honey_analysis.ipynb       # Main analysis notebook
├── honey_dashboard.png        # Final visualization output
└── README.md                  # Project documentation
```

---

## 🙋 Author
HARSH KAUSHIK
LinkedIn:[www.linkedin.com/in/harshkaushik315]
GITHUB:[https://github.com/harshkaushik315]


Made with 🍯 and Python.
