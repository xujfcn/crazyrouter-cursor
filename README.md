# 🖥️ Use Cursor IDE with Crazyrouter

> **Save 45% on AI coding costs** — Use Cursor with Claude, GPT, Gemini through Crazyrouter.

[Crazyrouter](https://crazyrouter.com?ref=github) is an AI API gateway — one key, 300+ models, 45% cheaper.

## 💰 Price Comparison

| Model | Official (In/Out per 1M tokens) | Crazyrouter | Savings |
|-------|--------------------------------|-------------|---------|
| Claude Opus 4 | $15 / $75 | $8.25 / $41.25 | **45%** |
| GPT-4o | $2.50 / $10 | $1.38 / $5.50 | **45%** |
| Claude Sonnet 4 | $3 / $15 | $1.65 / $8.25 | **45%** |
| Gemini 2.5 Pro | $1.25 / $10 | $0.69 / $5.50 | **45%** |

## ⚡ Setup (2 Minutes)

### 1. Get API Key
Sign up at [crazyrouter.com](https://crazyrouter.com?ref=github)

### 2. Configure Cursor
1. Open Cursor → **Settings** → **Models**
2. Set **API Base URL**: `https://crazyrouter.com/v1`
3. Set **API Key**: `sk-your-crazyrouter-key`
4. Add models you want to use

### 3. Start coding!

## 📋 Settings JSON

Edit Cursor settings directly:

```json
{
  "openai.apiBaseUrl": "https://crazyrouter.com/v1",
  "openai.apiKey": "sk-your-crazyrouter-key"
}
```

## 🎯 Recommended Model Setup

| Cursor Feature | Model | Why |
|---------------|-------|-----|
| Tab Completion | `gpt-4o-mini` | Fast and cheap ($0.08/$0.33) |
| Cmd+K Edit | `claude-sonnet-4-20250514` | Best code quality |
| Chat | `claude-sonnet-4-20250514` | Good balance |
| Composer | `claude-opus-4-20250514` | Complex multi-file tasks |

This setup optimizes for both quality and cost.

## 💡 Cursor Pro vs Crazyrouter

| | Cursor Pro ($20/mo) | Crazyrouter (pay-per-use) |
|--|---------------------|--------------------------|
| Monthly cost | $20 fixed | ~$30-50 (heavy use) |
| Usage limits | Yes (500 fast requests) | No limits |
| Model choice | Limited | 300+ models |
| Claude Opus | Limited | Unlimited |
| Overage | Slow mode | Just pay for what you use |

If you frequently hit Cursor Pro limits, Crazyrouter is more cost-effective.

## ❓ FAQ

**Q: Does Cursor work with Crazyrouter?**
A: Yes, fully compatible. All features work — Tab, Chat, Composer, Cmd+K.

**Q: Can I use Claude in Cursor?**
A: Yes! Through Crazyrouter you get Claude, GPT, Gemini, and 300+ models.

**Q: Is streaming supported?**
A: Yes, streaming works perfectly for real-time code generation.

**Q: Can I keep Cursor Pro and also use Crazyrouter?**
A: Yes, you can configure custom API as a fallback or for specific models.

## 🔗 Links
- 🌐 [Crazyrouter](https://crazyrouter.com?ref=github)
- 🖥️ [Cursor](https://cursor.com)
- 💬 [Telegram Community](https://t.me/crzrouter)
- 🐦 [Twitter @metaviiii](https://twitter.com/metaviiii)

## 📄 License
MIT

