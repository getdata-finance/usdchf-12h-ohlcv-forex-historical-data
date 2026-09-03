# USDCHF 12h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-14_119_rows-blue)](https://getdata.finance/datasets/usdchf) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdchf)

### -> [**Download the full USDCHF dataset on getdata.finance**](https://getdata.finance/datasets/usdchf)

**USDCHF 12h OHLCV forex historical data** — ultra high-quality 12h OHLCV for **US Dollar / Swiss Franc**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **US Dollar / Swiss Franc** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdchf) · **14,119** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `USDCHF_12h.csv` (85 rows, `2026-07-10` -> `2026-09-02`, 5.70 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdchf)** — **14,119** `12h` rows (full `1m`: 9,169,329), **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[USDCHF_12h.csv](https://github.com/getdata-finance/usdchf-12h-ohlcv-forex-historical-data/blob/main/USDCHF_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdchf-12h-ohlcv-forex-historical-data/main/USDCHF_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdchf-12h-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdchf-12h-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdchf-12h-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdchf](https://getdata.finance/datasets/usdchf)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdchf))** |
|---|--:|---|
| Instrument | US Dollar / Swiss Franc · Forex | US Dollar / Swiss Franc · Forex |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 85 | **14,119** |
| Size | 5.70 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Period | `2026-07-10` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `USDCHF_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdchf) |
| Coverage report | — | [USDCHF coverage](https://getdata.finance/coverage/usdchf) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdchf)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/usdchf) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDCHF_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-10T00:00:00+00:00 | 0.80568 | 0.80761 | 0.80304 | 0.80702 | 76033 |
| 2026-07-10T12:00:00+00:00 | 0.80702 | 0.80896 | 0.80593 | 0.8076 | 50741 |
| 2026-07-12T12:00:00+00:00 | 0.8064 | 0.81035 | 0.8064 | 0.81021 | 15707 |
| 2026-07-13T00:00:00+00:00 | 0.81021 | 0.81085 | 0.80745 | 0.8096 | 95902 |
| 2026-07-13T12:00:00+00:00 | 0.8096 | 0.81513 | 0.80932 | 0.81456 | 86800 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-31T00:00:00+00:00 | 0.8086 | 0.80965 | 0.80747 | 0.80849 | 71121 |
| 2026-08-31T12:00:00+00:00 | 0.80849 | 0.80877 | 0.80663 | 0.80859 | 62459 |
| 2026-09-01T00:00:00+00:00 | 0.80859 | 0.81088 | 0.80856 | 0.80992 | 78282 |
| 2026-09-01T12:00:00+00:00 | 0.80992 | 0.81251 | 0.80956 | 0.81251 | 66365 |
| 2026-09-02T00:00:00+00:00 | 0.81251 | 0.8132 | 0.81231 | 0.813 | 5878 |

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

df = pd.read_csv('USDCHF_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDCHF_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USDCHF_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **USDCHF** archive on **[getdata.finance](https://getdata.finance/datasets/usdchf)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **14,119** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full USDCHF dataset on getdata.finance](https://getdata.finance/datasets/usdchf)**

---
*GetData · USDCHF 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdchf)*
