# GER30 4h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-22_334_rows-blue)](https://getdata.finance/datasets/ger30) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/ger30)

### -> [**Download the full GER30 dataset on getdata.finance**](https://getdata.finance/datasets/ger30)

**GER30 4h OHLCV index historical data** — ultra high-quality 4h OHLCV for **DAX 40 (GER30)**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 4h OHLCV** for **DAX 40 (GER30)** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/ger30) · **22,334** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `GER30_4h.csv` (646 rows, `2026-03-26` -> `2026-09-25`, 60.10 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/ger30)** — **22,334** `4h` rows (full `1m`: 2,329,742), **11 timeframes**, `2008-09-10` -> `2026-09-25`.

## Download sample

**[GER30_4h.csv](https://github.com/getdata-finance/ger30-4h-ohlcv-index-historical-data/blob/main/GER30_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/ger30-4h-ohlcv-index-historical-data/main/GER30_4h.csv)) · [GitHub Releases](https://github.com/getdata-finance/ger30-4h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/ger30-4h-ohlcv-index-historical-data/](https://getdata-finance.github.io/ger30-4h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/ger30](https://getdata.finance/datasets/ger30)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/ger30))** |
|---|--:|---|
| Instrument | DAX 40 (GER30) · Index | DAX 40 (GER30) · Index |
| Timeframes | `4h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 4h rows | 646 | **22,334** |
| Size | 60.10 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Period | `2026-03-26` -> `2026-09-25` | `2008-09-10` -> `2026-09-25` |
| File | `GER30_4h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/ger30) |
| Coverage report | — | [GER30 coverage](https://getdata.finance/coverage/ger30) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`4h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/ger30)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `4h` sample · [getdata.finance](https://getdata.finance/datasets/ger30) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`GER30_4h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T04:00:00+00:00 | 22822.74 | 22839.49 | 22686.75 | 22720 | 19663 |
| 2026-03-26T08:00:00+00:00 | 22720 | 22783.34 | 22569.86 | 22579.34 | 81789 |
| 2026-03-26T12:00:00+00:00 | 22579.34 | 22825.35 | 22552.84 | 22659.35 | 89939 |
| 2026-03-26T16:00:00+00:00 | 22659.35 | 22703.85 | 22515.49 | 22522.01 | 37718 |
| 2026-03-26T20:00:00+00:00 | 22522.01 | 22888.75 | 22509.5 | 22625.74 | 7427 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T00:00:00+00:00 | 25410.83 | 25440.25 | 25364.99 | 25426.75 | 16452 |
| 2026-09-25T04:00:00+00:00 | 25426.75 | 25506.25 | 25406.24 | 25429.58 | 40487 |
| 2026-09-25T08:00:00+00:00 | 25429.58 | 25554.58 | 25402.6 | 25466.59 | 61264 |
| 2026-09-25T12:00:00+00:00 | 25466.59 | 25510.58 | 25369.58 | 25491.59 | 74549 |
| 2026-09-25T16:00:00+00:00 | 25491.59 | 25597.25 | 25486.23 | 25574.48 | 35541 |

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

df = pd.read_csv('GER30_4h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('GER30_4h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('GER30_4h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **GER30** archive on **[getdata.finance](https://getdata.finance/datasets/ger30)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **22,334** rows at `4h`, plus all other timeframes in the same ZIP.

**[-> Get the full GER30 dataset on getdata.finance](https://getdata.finance/datasets/ger30)**

---
*GetData · GER30 4h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/ger30)*
