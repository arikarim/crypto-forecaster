# Crypto Direction Forecaster

Live crypto forecaster (BTC, ETH, SOL, BNB, XRP, gold via PAXG).

- Live prices over WebSocket (Binance → Bybit → OKX → Coinbase fallback)
- Timeframes: 5m, 15m, 1h, 4h, 1d
- Models: gradient-boosted trees, logistic regression, k-NN pattern matching, technical rules — scored with a walk-forward backtest and weighted into an ensemble
- GARCH(1,1) volatility → expected range

Open `index.html` in a browser, or host the folder on any static host. Not financial advice.
