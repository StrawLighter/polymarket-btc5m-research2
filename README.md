<div align="center">

# Polymarket BTC 5m Research

**BTC 5-minute Polymarket research pipeline**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Polymarket](https://img.shields.io/badge/Polymarket-0052FF?logoColor=white)

</div>

---

> **Status:** 🟡 In Progress

## Overview

Research pipeline for analyzing BTC 5-minute prediction markets on Polymarket. Explores signal extraction, edge detection, and execution strategies for short-duration binary outcome markets on Bitcoin price movements.

## Features

- **Market Data Collection** — Historical and real-time Polymarket CLOB data ingestion
- **Signal Analysis** — Technical indicators, order flow, and sentiment signals at 5m resolution
- **Edge Detection** — Statistical analysis of pricing inefficiencies and market maker behavior
- **Backtesting** — Walk-forward simulation with realistic fill assumptions and fee modeling
- **Visualization** — Interactive charts for market microstructure and P&L analysis

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Analysis | Python, Pandas, NumPy |
| Notebooks | Jupyter |
| Data | Polymarket CLOB API |
| Visualization | Plotly, Matplotlib |
| Storage | Parquet / SQLite |

## Getting Started

```bash
git clone https://github.com/StrawLighter/polymarket-btc5m-research2.git
cd polymarket-btc5m-research2
pip install -r requirements.txt
jupyter notebook
```

## License

MIT

---

<div align="center">
  <sub>Built by <a href="https://github.com/StrawLighter">Orchard 7</a></sub>
</div>
