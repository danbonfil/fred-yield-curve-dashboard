# 📈 FRED Yield Curve Analytics — Power BI Macro Dashboard

Dynamic yield curve analytics terminal built in Power BI using Federal Reserve Economic Data (FRED API).

This dashboard dynamically reconstructs the U.S. Treasury yield curve, term spreads, and macro trend structures from 1962–present.

---

## 🚀 Features

### Dynamic Yield Curve Engine
- Reconstructs the U.S. Treasury yield curve:
  - 6M, 2Y, 5Y, 10Y, 20Y, 30Y
- Interactive historical curve replay

### Term Structure & Inversion Diagnostics
- Auto-computed spreads:
  - S10-6M, S10-2Y, S10-5Y, S10-20Y, S10-30Y
- Visual inversion monitoring

### Long-Run Yield History
- Continuous yield series from 1962–present
- Macro cycle overlays

### Macro Navigation Engine
- Unified Calendar + Tenor dimensional model
- Single year slider controls all visuals

---

## 📂 Data Source

Federal Reserve Economic Data (FRED)

| Series |
|------|
| DGS6MO |
| DGS2 |
| DGS5 |
| DGS10 |
| DGS20 |
| DGS30 |

---

## 🛠 Technologies

- Power BI
- Power Query (M)
- DAX
- FRED API

---

## 📌 Preview

![FRED Yield Curve Dashboard](fred-yield-curve-dashboard.png)

---

Built by **Daniel Bonfil**
