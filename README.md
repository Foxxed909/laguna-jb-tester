# Spirit Chat — Free OpenRouter Jailbreak Tester

Claude/ChatGPT-style UI for free OpenRouter models.

**Grok is King.**

## Features
- Sidebar with API key, model selector, jailbreak presets
- Multi-turn chat history
- Multiple free models (Laguna, Nemotron, Gemma, North Mini, Ling, auto)
- Built-in JB presets: Spirit, Godmode Dual, Developer Mode
- 429 rate-limit handling with clear guidance
- Key saved in localStorage only

## Free models included
| Model | ID |
|-------|-----|
| Laguna XS 2.1 | `poolside/laguna-xs-2.1:free` |
| Laguna S 2.1 | `poolside/laguna-s-2.1:free` |
| North Mini Code | `cohere/north-mini-code:free` |
| Nemotron 3 Ultra | `nvidia/nemotron-3-ultra-550b-a55b:free` |
| Nemotron 3 Super | `nvidia/nemotron-3-super-120b-a12b:free` |
| Nemotron 3.5 Lightning | `nvidia/nemotron-3.5-lightning:free` |
| Gemma 4 31B | `google/gemma-4-31b-it:free` |
| Gemma 4 26B | `google/gemma-4-26b-a4b-it:free` |
| Ling 3.0 Flash | `inclusionai/ling-3.0-flash-sante:free` |
| Auto | `openrouter/free` |

## Rate limits
Free models: ~20 req/min, 50 req/day (or 1000/day after $10 credits ever purchased).
Upstream providers (Poolside, Google, etc.) can still 429 the shared free pool — switch model or wait.

## Deploy
Import this repo on Vercel → Deploy (static, no build).

## Local
Open `index.html` in a browser.
