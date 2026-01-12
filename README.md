# Trader Rosenfeld - Live Dashboard

**Automated Trading Bot Dashboard** - GitHub Pages Repository

This repository hosts the live HTML dashboard for the Trader Rosenfeld MT5 trading bot.

## 📊 View Live Dashboard

**URL**: https://aldorosenfeldjr.github.io/trader-rosenfeld-dashboard/

## 🔄 Automatic Updates

- **Generated**: Daily at 17:00 Brasília time (20:00 UTC)
- **Uploaded**: Automatically at 17:02 via scheduler
- **Deployment**: GitHub Pages updates within 1-2 minutes

## 📁 Repository Location

This repository is located within the main bot project:
```
D:\Trader_Rosenfeld\github-pages\
```

## 🛠️ How It Works

1. Bot generates dashboard at 17:00: `reports/dashboard/Rosenfeld_dashboard_DD-MM-YYYY.html`
2. Scheduler copies to `github-pages/index.html` at 17:02
3. Git commits and pushes automatically
4. GitHub Pages deploys updated dashboard

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
