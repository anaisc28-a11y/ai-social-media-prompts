<div align="center">

# 🧠 AI Social Media Prompts

**A battle-tested prompt library for social media managers, personal brands and content teams.**
Strategy · Hooks · Reels scripts · Captions · Community · Paid ads · Reporting

<img src="https://img.shields.io/badge/prompts-36-E01474?style=flat-square" /> <img src="https://img.shields.io/badge/works_with-Claude_·_ChatGPT_·_Gemini-141110?style=flat-square" /> <img src="https://img.shields.io/badge/lang-EN_·_ES-FF5A1F?style=flat-square" /> <img src="https://img.shields.io/badge/license-CC_BY_4.0-1C6B4C?style=flat-square" />

[🇪🇸 Leer en español](#-en-español)

</div>

---

## Why this exists

Most "AI prompts for Instagram" give you generic content that sounds like everyone else. These prompts are built the way I work with real brands (FMCG, fitness creators with 1.6MM+ followers, beauty, food, wellness professionals):

1. **Brand context first.** Every prompt plugs into a reusable [Brand Voice Card](./brand-voice-card.md), so the AI writes *like the brand*, not like a robot.
2. **One goal, one KPI.** Prompts ask for the objective (saves, DMs, clicks, CPA) because content without a KPI can't be improved.
3. **AI drafts, humans decide.** Outputs come as options + reasoning, so you edit with judgement instead of copy-pasting.

## 📚 Library

| # | Category | Prompts | Best for |
|:-:|---|:-:|---|
| 01 | [Strategy & positioning](./prompts/01-strategy.md) | 6 | Audits, content pillars, audience insights, competitor analysis |
| 02 | [Hooks & Reels scripts](./prompts/02-hooks-and-scripts.md) | 7 | Short-form video, storytelling, retention |
| 03 | [Captions & copy](./prompts/03-captions-and-copy.md) | 6 | Carousels, captions, CTAs, repurposing |
| 04 | [Community & DMs](./prompts/04-community.md) | 5 | Replies, crisis, DM-to-sale flows |
| 05 | [Paid social](./prompts/05-paid-social.md) | 6 | Meta & TikTok ad copy, angles, testing plans |
| 06 | [Reporting & insights](./prompts/06-reporting.md) | 6 | Monthly reports, KPI diagnosis, next actions |

## ⚡ Quick start

1. Fill in the [**Brand Voice Card**](./brand-voice-card.md) once per brand (5 minutes).
2. Paste it at the start of a new chat (or save it as a Claude Project / custom GPT instruction).
3. Pick a prompt, replace the `{{variables}}` and run it.
4. Edit the best option. Publish. Measure. Feed the results back with [06-reporting](./prompts/06-reporting.md).

```text
[Brand Voice Card pasted here]

Using the brand above, run prompt 02.1 "Hook generator":
topic = {{why you're not losing fat even if you train}}
format = {{Reel, 30s}}
goal = {{saves}}
```

## 🧩 Prompt anatomy

Every prompt follows the same structure, so you can write your own:

```text
ROLE      → who the AI should act as (senior strategist, copywriter…)
CONTEXT   → brand voice card + the specific situation
TASK      → one clear job
RULES     → constraints (length, tone, what to avoid)
OUTPUT    → exact format (table, numbered list, script with timestamps)
CHECK     → self-review step before answering
```

## 🤝 Contributing

Found a prompt that works great? Open a PR with the prompt, an example output and the result it got (metric + context). Real results > theory.

---

## 🇪🇸 En español

**Librería de prompts probados para social media managers, marcas personales y equipos de contenido.**

Los prompts están en inglés porque así los entienden mejor todos los modelos, pero **todos incluyen la variable `{{language}}`**: pon `español (España)` y la respuesta saldrá en español con el tono de tu marca.

**Cómo usarla:**
1. Rellena la [Brand Voice Card](./brand-voice-card.md) una vez por marca.
2. Pégala al principio del chat (o guárdala como instrucciones de un Proyecto de Claude / GPT).
3. Elige un prompt, cambia las `{{variables}}` y ejecútalo.
4. Edita la mejor opción, publica, mide y vuelve a meter los datos con los prompts de reporting.

> **Mi regla:** la IA se encarga del volumen; tú del criterio, la historia y la estrategia.

---

<sub>Created by <a href="https://github.com/anaiscarapaica">Anais Carapaica</a> · AI-powered Social Media Strategist · Licensed under CC BY 4.0 — use it, adapt it, credit it.</sub>
