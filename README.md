# USDJPY 16h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-10_846_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full USDJPY dataset on ork.ad**](https://ork.ad/)

**USDJPY 16h OHLCV Forex historical data** — ultra high-quality 16h OHLCV for **US Dollar / Japanese Yen**. 24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 16h OHLCV** for **US Dollar / Japanese Yen** (Forex)
- **24/5 FX liquidity with Asian, European and US sessions — not limited to US market hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`16h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **10,846** `16h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `16h` sample updated in sync

> **Sample on GitHub** · `USDJPY_16h.csv` (330 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **10,846** `16h` rows (~0.62 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2001-11-28` → `2026-07-03`.

## Download sample

**[USDJPY_16h.csv](https://github.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/blob/main/USDJPY_16h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/main/USDJPY_16h.csv)) · [GitHub Releases](https://github.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdjpy-16h-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdjpy-16h-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `16h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 16h rows | 330 | **10,846** |
| Size | 0.02 MB | ~0.62 MB |
| Period | `2025-10-03` → `2026-07-03` | `2001-11-28` → `2026-07-03` |
| File | `USDJPY_16h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`16h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `16h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `16h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_16h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T16:00:00Z | 147.52 | 147.56 | 147.3977383 | 147.474746 | 26561.0 |
| 2025-10-05T16:00:00Z | 149.4509436 | 150.4520437 | 149.0 | 150.384 | 238983.0 |
| 2025-10-06T08:00:00Z | 150.384 | 150.633 | 149.766 | 150.505049 | 223356.0 |
| 2025-10-07T00:00:00Z | 150.505049 | 151.43 | 150.263 | 151.341 | 198453.0 |
| 2025-10-07T16:00:00Z | 151.341 | 152.8022787 | 151.27 | 152.76 | 201206.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-30T16:00:00Z | 162.66 | 162.853 | 162.505 | 162.682 | 78127.0 |
| 2026-07-01T08:00:00Z | 162.682 | 162.78 | 162.312 | 162.579 | 103586.0 |
| 2026-07-02T00:00:00Z | 162.579 | 162.6 | 160.643 | 161.001 | 294118.0 |
| 2026-07-02T16:00:00Z | 161.001 | 161.54 | 160.502 | 161.049 | 140308.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDJPY_16h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDJPY_16h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('USDJPY_16h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='16h')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **10,846** rows at `16h`, plus all other timeframes in the same ZIP.

**[→ Get the full USDJPY dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDJPY 16h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*