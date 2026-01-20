# Trader Rosenfeld - Live Dashboard

**Automated Trading Bot Dashboard** - GitHub Pages Repository

**Latest Update**: 2026-01-18 ✅ V3.0 Operational

This repository hosts the live HTML dashboard for the Trader Rosenfeld MT5 trading bot.

## 📊 View Live Dashboard

**URL**: https://aldorosenfeldjr.github.io/trader-rosenfeld-dashboard/

**Current Version**: V3.0 with Trailing Stop Loss System

## 🔄 Automatic Updates

- **Generated**: Daily at 17:00 Brasília time (20:00 UTC)
- **Uploaded**: Automatically at 17:02 via scheduler
- **Deployment**: GitHub Pages updates within 1-2 minutes
- **Status**: ✅ Active and working (V3 configuration validated)

## 📁 Repository Location

This repository is located within the main bot project:
```
D:\Trader_Rosenfeld\github-pages\
```

## 🛠️ How It Works

### V3 System (Current)
1. Bot V3 generates dashboard at 20:00 UTC: `reports/v3/dashboard/Rosenfeld_dashboard_DD-MM-YYYY.html`
2. Cloud upload scheduler copies to `github-pages/index.html` at 20:02 UTC
3. Git commits and pushes automatically
4. GitHub Pages deploys updated dashboard within 1-2 minutes

### Previous Versions
- **V2**: Generates to `reports/v2/dashboard/`
- **V1**: Generates to `reports/v1/dashboard/`

All versions upload to the same GitHub Pages repository, with V3 being the current production version.

## ⚙️ Manual Update

To manually update the dashboard:

```bash
cd D:\Trader_Rosenfeld
python upload_dashboard_github.py
```

## 📱 Access

The dashboard is optimized for:
- Desktop browsers
- Mobile browsers (fully responsive)
- Tablet browsers
- PDF export via browser print function

**Recommended**: Access via latest V3.0 dashboard for Trailing Stop Loss metrics

## 🔐 Security Note

This is a **public repository** on GitHub. The dashboard shows:
- ✅ Trading performance metrics
- ✅ P&L statistics
- ✅ Trade history
- ❌ Does NOT show broker credentials
- ❌ Does NOT show strategy parameters

---

**Last Updated**: Auto-generated daily by Trader Rosenfeld automated reporting system

**Bot Version**: 1.2.0
