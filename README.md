# 🔵 BasePulse

> AI-powered daily digest of Base ecosystem activity

![GitHub Actions](https://github.com/Zganz404/base-pulse/actions/workflows/daily.yml/badge.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Built on Base](https://img.shields.io/badge/Built%20on-Base-0052FF?style=flat&logo=coinbase)

## What is BasePulse?

BasePulse is an open-source bot that automatically generates daily AI-powered reports about the Base L2 ecosystem — DeFi TVL trends, NFT activity, developer metrics, gas analytics, and more.

Every day at 9:15 UTC a new report is committed to this repo. No manual work needed.

## 📊 Latest Reports

Browse the [reports/](./reports/) folder for daily digests.

## 🤖 How it works

GitHub Actions (cron) → Node.js bot → OpenRouter AI → Markdown report → Git commit

1. GitHub Actions triggers daily at 9:15 UTC
2. Bot picks a random Base ecosystem topic
3. AI generates a structured Markdown report
4. Report is committed to reports/ automatically

## 🚀 Stack

- **Runtime:** Node.js
- **AI:** OpenRouter API (free tier, auto model selection)
- **CI/CD:** GitHub Actions
- **Network:** Base L2 (Coinbase)

## 🛠️ Self-host in 5 minutes

Clone the repo, run npm install, add your OpenRouter API key to .env, then run node bot.js

## Environment variables

| Variable | Description |
|----------|-------------|
| OPENAI_API_KEY | Your OpenRouter API key |
| TALENT_WALLET | Your Base wallet address |

## License

MIT © [Zganz404](https://github.com/Zganz404)

<!-- talent.app verification -->
<meta name="talentapp:project_verification" content="a91fdd0e11b6144c52291b122dab6669cfab19e97790808c368c2db25eb4469214c66050be56b4678276c7cc5d77efbf680e2b3473e3cf092a2e4ae6d258a50a">
