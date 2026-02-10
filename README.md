# Trader Rosenfeld - Live Dashboard

**Automated Trading Bot Dashboard** - GitHub Pages Repository

**Latest Update**: 2026-02-10
**Version**: 6.1.2 (6 Bot Versions: V1-V6)

This repository hosts the live HTML dashboard for the Trader Rosenfeld MT5 trading bot.

## View Live Dashboard

**URL**: https://aldorosenfeldjr.github.io/trader-rosenfeld-dashboard/

**Password Protected**: Yes (contact owner for access)

## Bot Versions

| Version | Signal Logic | Entry Timing | Exit Strategy |
|---------|--------------|--------------|---------------|
| V1 | EMA200 + RSI% | Half-candle | Fixed TP/SL |
| V2 | ATR% + Direction | Half-candle | Fixed TP/SL |
| V3 | ATR% + Direction | Half-candle | Trailing SL |
| V4 | EMA200 + RSI% | Half-candle | Trailing SL |
| V5 | ATR% + Direction | Every 30min | Fixed TP/SL |
| V6 | ATR% + Direction | Every 30min | Dynamic Trailing |

## Automatic Updates

- **Generated**: Daily at 17:00 Brasilia (20:00 UTC)
- **Uploaded**: Automatically at 17:02 via scheduler
- **Deployment**: GitHub Pages updates within 1-2 minutes
- **Status**: Active

## Repository Location

This repository is located within the main bot project:
```
D:\Trader_Rosenfeld\github-pages\
```

## How It Works

1. Combined dashboard generated with all V1-V6 trade data
2. Cloud upload scheduler copies to `github-pages/index.html`
3. Git commits and pushes automatically
4. GitHub Pages deploys updated dashboard

## Manual Update

```bash
cd D:\Trader_Rosenfeld
python upload_dashboard_github.py
```

## Dashboard Features

- Version toggle (V1-V6) with instant filtering
- Equity curve chart
- Performance by pair analysis
- Trade history with export
- Mobile responsive design
- PDF export via browser print

## Security Note

This is a **public repository**. The dashboard shows:
- Trading performance metrics
- P&L statistics
- Trade history

Does NOT expose:
- Broker credentials
- Strategy parameters
- Account numbers

---

**Auto-generated daily by Trader Rosenfeld automated reporting system**
