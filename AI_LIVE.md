# Live free APIs (auto-integrated by field)

Xroga detects your product field (crypto, weather, AI chat, …) and wires **free live endpoints** so the preview works with real data.

| Field | Free endpoint | API key? |
|-------|---------------|----------|
| Crypto prices | [CoinGecko](https://www.coingecko.com/en/api) `simple/price` | No |
| Chat / text | [Pollinations](https://pollinations.ai) | No |
| Images | `image.pollinations.ai` | No |
| Weather | [Open-Meteo](https://open-meteo.com) | No |
| FX rates | Frankfurter | No |
| Web search | DuckDuckGo (+ Xroga SearXNG on xroga.com) | No |
| Voice | Browser Web Speech API | No |

Use `window.XrogaLiveAi.cryptoPrices()`, `.chat()`, `.weather()`, `.search()`.

## Bring your own key (encrypted)

1. Open **Xroga → Integrations → AI**
2. Paste Groq / Gemini / OpenRouter / DeepSeek key
3. **AES-encrypted** in your account — never committed to GitHub
4. Preview on xroga.com can use `/api/integrations/live-ai/chat` with your vault key
