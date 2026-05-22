# 📊 Dual-Domain Analytics Capstone Project

A full-stack data analytics dashboard combining **E-commerce Sales Analysis** and **COVID-19 Health Data** visualization.

## 🛠️ Tech Stack
| Layer | Technologies |
|-------|-------------|
| Backend | Python, Flask |
| Data | Pandas, NumPy |
| Charts | Matplotlib, Seaborn |
| Frontend | HTML5, CSS3, JavaScript |

## 📁 Project Structure
```
capstone/
├── app.py              ← Flask backend (data + chart generation)
├── requirements.txt    ← Python dependencies
├── templates/
│   └── index.html      ← Dashboard UI (HTML/CSS/JS)
└── README.md
```

## 🚀 How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Run the app
```bash
python app.py
```

### 3. Open in browser
```
http://localhost:5000
```

## 📈 E-Commerce Module
- **KPIs**: Total Sales, Profit, Avg Rating, Return Rate, Orders, Avg Discount
- **Charts**:
  - Horizontal bar — Sales by Category
  - Line chart — Monthly Sales & Profit Trend
  - Seaborn heatmap — Region × Category Sales
  - Histogram + KDE — Customer Rating Distribution
  - Scatter plot — Discount vs Profit (colored by Sales)
  - Pie chart — Category Sales Share

## 🦠 COVID-19 Module
- **KPIs**: Total Cases, Deaths, Recovered, Avg Vaccination %, Countries, CFR
- **Charts**:
  - Multi-line trend — Monthly Cases by Country
  - Horizontal bar — Vaccination Rate (%)
  - Seaborn heatmap — Monthly Deaths by Country
  - Bar chart — Case Fatality Rate (%)
  - Bar chart — Recovery Rate by Country

## 💡 Key Concepts Demonstrated
- Synthetic data generation with NumPy & Pandas
- Matplotlib dark-theme customization
- Seaborn statistical visualizations (histplot, heatmap)
- Base64 chart encoding for Flask → JS delivery
- REST API endpoints (`/api/ecommerce`, `/api/covid`)
- Lazy-loading tabs in vanilla JavaScript
- Responsive CSS Grid dashboard layout
