# AAPL 5m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-243_930_rows-blue)](https://getdata.finance/datasets/aapl) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aapl)

### -> [**Download the full AAPL dataset on getdata.finance**](https://getdata.finance/datasets/aapl)

**AAPL 5m OHLCV stocks historical data** — ultra high-quality 5m OHLCV for **Apple**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 5m OHLCV** for **Apple** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`5m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aapl) · **243,930** `5m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `5m` sample updated in sync

> **Sample on GitHub** · `AAPL_5m.csv` (9,906 rows, `2026-03-12` -> `2026-09-11`, 923.93 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/aapl)** — **243,930** `5m` rows (full `1m`: 636,557), **11 timeframes**, `2011-05-09` -> `2026-09-11`.

## Download sample

**[AAPL_5m.csv](https://github.com/getdata-finance/aapl-5m-ohlcv-stocks-historical-data/blob/main/AAPL_5m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aapl-5m-ohlcv-stocks-historical-data/main/AAPL_5m.csv)) · [GitHub Releases](https://github.com/getdata-finance/aapl-5m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aapl-5m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/aapl-5m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aapl](https://getdata.finance/datasets/aapl)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aapl))** |
|---|--:|---|
| Instrument | Apple · US stocks | Apple · US stocks |
| Timeframes | `5m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 5m rows | 9,906 | **243,930** |
| Size | 923.93 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Period | `2026-03-12` -> `2026-09-11` | `2011-05-09` -> `2026-09-11` |
| File | `AAPL_5m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aapl) |
| Coverage report | — | [AAPL coverage](https://getdata.finance/coverage/aapl) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`5m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aapl)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `5m` sample · [getdata.finance](https://getdata.finance/datasets/aapl) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `5m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AAPL_5m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T13:30:00+00:00 | 260.51 | 260.51 | 257.04 | 257.76 | 1063 |
| 2026-03-12T13:35:00+00:00 | 257.76 | 257.95 | 257.44 | 257.48 | 1087 |
| 2026-03-12T13:40:00+00:00 | 257.48 | 257.55 | 256.4 | 256.53 | 1380 |
| 2026-03-12T13:45:00+00:00 | 256.53 | 256.58 | 255.89 | 256.33 | 1446 |
| 2026-03-12T13:50:00+00:00 | 256.33 | 256.61 | 255.39 | 255.46 | 1658 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T19:35:00+00:00 | 332.81 | 332.88 | 332.4 | 332.47 | 544 |
| 2026-09-11T19:40:00+00:00 | 332.47 | 332.6 | 332.34 | 332.46 | 550 |
| 2026-09-11T19:45:00+00:00 | 332.46 | 332.66 | 332.29 | 332.59 | 432 |
| 2026-09-11T19:50:00+00:00 | 332.59 | 332.59 | 332.12 | 332.26 | 912 |
| 2026-09-11T19:55:00+00:00 | 332.26 | 332.77 | 331.89 | 332.23 | 1240 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AAPL_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AAPL_5m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AAPL_5m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='5min')
print(pf.stats())
```

## Download full data

The complete **AAPL** archive on **[getdata.finance](https://getdata.finance/datasets/aapl)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **243,930** rows at `5m`, plus all other timeframes in the same ZIP.

**[-> Get the full AAPL dataset on getdata.finance](https://getdata.finance/datasets/aapl)**

---
*GetData · AAPL 5m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aapl)*
