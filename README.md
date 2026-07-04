# USDJPY 16h OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-293_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

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
- **Free evaluation sample** on GitHub (`16h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **293** `16h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `16h` sample updated in sync

> **Sample on GitHub** · `USDJPY_16h.csv` (327 rows, `2025-10-03` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **293** `16h` rows (~0.02 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-10-31` → `2026-07-02`.

## Download sample

**[USDJPY_16h.csv](https://github.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/blob/main/USDJPY_16h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/main/USDJPY_16h.csv)) · [GitHub Releases](https://github.com/ork-ad/usdjpy-16h-ohlcv-forex-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/usdjpy-16h-ohlcv-forex-historical-data/](https://ork-ad.github.io/usdjpy-16h-ohlcv-forex-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `16h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 16h rows | 327 | **293** |
| Size | 0.02 MB | ~0.02 MB |
| Period | `2025-10-03` → `2026-07-02` | `2025-10-31` → `2026-07-02` |
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
| 2025-10-03T00:00:00Z | 147.1565 | 147.8215 | 147.0589411347056 | 147.3389467347336 | 200707.0 |
| 2025-10-03T16:00:00Z | 147.3389467347336 | 147.5475 | 147.3319465947329 | 147.462949214746 | 36339.0 |
| 2025-10-05T16:00:00Z | 149.4389887349436 | 150.44000875504372 | 149.0 | 150.0340006350031 | 214608.0 |
| 2025-10-06T08:00:00Z | 150.0340006350031 | 150.4805 | 149.7535 | 150.3665 | 232211.0 |
| 2025-10-07T00:00:00Z | 150.3665 | 151.2095 | 150.2515 | 151.1795 | 198962.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-06-30T00:00:00Z | 161.917 | 162.655 | 161.914 | 162.606 | 145413.0 |
| 2026-06-30T16:00:00Z | 162.606 | 162.831 | 162.483 | 162.666 | 77987.0 |
| 2026-07-01T08:00:00Z | 162.666 | 162.758 | 162.289 | 162.543 | 102386.0 |
| 2026-07-02T00:00:00Z | 162.543 | 162.591 | 160.613 | 160.905 | 286511.0 |

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

The complete **USDJPY** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **293** rows at `16h`, plus all other timeframes in the same ZIP.

**[→ Get the full USDJPY dataset on ork.ad](https://ork.ad/)**

---
*GetData · USDJPY 16h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*