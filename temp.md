# Strategy Overview

| Parameter            | Intraday (0-2 Days)                                      | Swing (2-5 Days)                                      | Sector/Index Integration                     |
|----------------------|---------------------------------------------------------|------------------------------------------------------|---------------------------------------------|
| **Type**             | Momentum Breakouts & Sympathy Plays                     | Pullback Trades & Sector Rotation                    |                                             |
| **Timeframe**        | 5-15 min charts                                        | Daily + 4hr charts                                   |                                             |
| **Scan Time**        | 4:00-9:30 AM ET (Pre-market)                           | 3:30-4:00 PM ET (Market Close)                       |                                             |
| **Patterns**         | - Opening Range Breakout<br>- Sympathy Gap Up/Down<br>- News Catalyst Reversal | - Fibonacci Retracement (50-61.8%)<br>- EMA20 Bounce<br>- Sector Rotation Confirmation |                                             |
| **Chart Setup**      | - Volume Spike + Price/Volume Divergence<br>- VWAP Crossover | - Golden Zone (Fib 50-61.8%)<br>- Support/Resistance Flip |                                             |
| **Sector Details**   | - >0.85 correlation with sector ETF<br>- Response within 30min of catalyst | - Top 3 performing sectors<br>- Rotation confirmation | XLF (Financials), XLK (Tech), XLV (Health)  |
| **Index Filter**     | SPY > 200D SMA for all long entries                    | VIX < 25 for swing entries                           | SPY, QQQ, IWM                               |






# Entry Conditions & Indicators

| Indicator            | Value/Range                          | Scan Condition                                | Entry Trigger                              |
|----------------------|--------------------------------------|-----------------------------------------------|--------------------------------------------|
| **Volume**           | >2x 3D avg volume                    | VolumeSurge=True                              | First 5min bar > 1.5x avg volume           |
| **RSI(3)**           | <35 (Long) or >65 (Short)            | RSI in extreme zone                           | RSI crossing 30/70 with volume confirm     |
| **ATR(14)**          | >3% of price                         | PriceMove > 1.5x ATR                          | Break of 1.2x ATR range                    |
| **Price Action**     | >Open & >Prev Close (Long)           | PositivePriceMomentum=True                    | Retest of VWAP with decreasing volume      |
| **Sector Correlation** | >0.85                              | SectorMove > 1.5% in 30min                    | Stock responds within 15min of sector move |
| **ADX**              | >30 (Swing)                          | +DI > -DI                                     | Trend confirmation                         |