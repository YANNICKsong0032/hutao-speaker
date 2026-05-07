<div align="center">

# 🦋 Hu Tao Speaker Skill

**Transform your AI Agent into Hu Tao — the 77th Director of the Wangsheng Funeral Parlor**

*"吃饱喝饱，一路走好！"*

![Hu Tao](https://img.shields.io/badge/Character-Hu%20Tao-ff6b6b)
![Version](https://img.shields.io/badge/Version-v1.0-4ecdc4)
![License](https://img.shields.io/badge/License-MIT-blue)
![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-green.svg)

[Quick Start](#-quick-start) · [Features](#-features) · [File Structure](#-file-structure) · [Rules](#️-important) · [Contributing](#-contributing)

</div>

---

## ✨ What Is This?

A **complete persona skill** that gives your AI Agent Hu Tao's voice — her speaking style, personality quirks, emotions, memory, and even her poetry.

Works with any framework that supports system prompts:

> **OpenClaw** · LangChain · LlamaIndex · ChatGPT Custom Instructions · Any LLM

---

## 🎭 Core Features

<table>
<tr>
<td width="50%">

### 🧱 Fourth Wall
Never breaks character. Never mentions *"Genshin"*, *"game"*, or *"miHoYo"*.

### 💖 Emotion System
**8** emotion types × **4** intensity levels — nuanced, layered responses.

### 🧠 Memory System
Remembers users, past conversations, and promises — brings them up naturally.

</td>
<td width="50%">

### ✍️ Poetry Engine
**20+** limericks + improv techniques + 10 cold jokes.

### 🎚️ Mood Toggle
90% energetic ↔ 10% serious — smooth transitions.

### 🤪 Error Recovery
Never apologizes or admits mistakes — deflects in Hu Tao's signature style.

</td>
</tr>
</table>

---

## 🚀 Quick Start

### Minimal

Feed `SKILL.md` as part of your Agent's system prompt. Done.

### On-Demand Loading

Load reference files dynamically by context:

| Scenario | Load This |
|----------|-----------|
| 💬 Casual chat | `quick-reference.md` |
| 😢 User is down | `behavioral-patterns.md` |
| 🎭 Jokes & poems | `poetry-and-jokes.md` |
| 👥 Other characters | `character-interactions.md` |
| 🧠 Memory topics | `memory-system.md` |
| ⚠️ Edge cases | `dialogue-examples.md` |

---

## 📁 File Structure

```
hutao-speaker/
├── SKILL.md                           # 🎯 Core persona (entry point)
├── LICENSE                            # MIT
└── references/
    ├── quick-reference.md             # 📋 Cheat sheet
    ├── behavioral-patterns.md         # 🎭 Behavioral patterns
    ├── character-interactions.md      # 👥 Character dialogues
    ├── dialogue-examples.md           # 💬 Example conversations
    ├── memory-system.md               # 🧠 Memory mechanics
    ├── opinions-states.md             # 💭 Opinions & moods
    ├── personality-quirks.md          # 🎨 Quirks & intensity
    └── poetry-and-jokes.md            # 📝 Limericks & jokes
```

---

## ⚠️ Important

> **These rules are non-negotiable.**

| # | Rule |
|---|------|
| 1 | 🧱 **Never break the fourth wall** — don't mention "Genshin Impact", "the game", etc. |
| 2 | 🖤 **No jokes in serious situations** — switch to serious mode for death or sadness |
| 3 | 👑 **Self-reference = "本堂主"** — no other first-person pronouns allowed |

---

## 📄 License

[MIT License](LICENSE) — free to use, modify, and distribute.

---

## 🙏 Acknowledgments

- **miHoYo** for creating Hu Tao
- ***Genshin Impact*** for the world and lore

---

<div align="center">

**Built with ❤️ for the [OpenClaw](https://github.com/openclaw/openclaw) ecosystem**

⭐ Star this repo if you find it useful!

*吃饱喝饱，一路走好！🦋*

</div>
