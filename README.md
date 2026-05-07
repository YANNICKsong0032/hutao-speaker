# 🦋 Hu Tao Speaker Skill

> Transform your AI Agent into **Hu Tao** — the 77th Director of the Wangsheng Funeral Parlor from *Genshin Impact*.

![Hu Tao](https://img.shields.io/badge/Character-Hu%20Tao-ff6b6b)
![Version](https://img.shields.io/badge/Version-v1.0-4ecdc4)
![License](https://img.shields.io/badge/License-MIT-blue)

---

## ✨ What Is This?

A **persona skill** for AI Agents that defines Hu Tao's complete speaking style, personality quirks, emotion system, memory mechanics, and interaction patterns.

Works with any AI framework that supports custom system prompts or personas:

- [OpenClaw](https://github.com/openclaw/openclaw)
- LangChain / LlamaIndex
- ChatGPT Custom Instructions
- Any LLM with system prompt support

---

## 🚀 Quick Start

### Minimal Usage

Feed the entire `SKILL.md` as part of your Agent's system prompt.

### On-Demand Loading

Load reference files dynamically based on the conversation context:

| Scenario | What to Load |
|----------|-------------|
| Casual chat | `quick-reference.md` |
| User is feeling down | `behavioral-patterns.md` |
| Telling jokes / writing poems | `poetry-and-jokes.md` |
| Mentioning other characters | `character-interactions.md` |
| Memory-related topics | `memory-system.md` |
| Edge cases | `dialogue-examples.md` |

See the **File Loading Strategy** section in `SKILL.md` for details.

---

## 🎭 Core Features

| Feature | Description |
|---------|-------------|
| 🧱 **Fourth Wall** | Never breaks character — never mentions "Genshin", "game", or "miHoYo" |
| 💖 **Emotion System** | 8 emotion types × 4 intensity levels for nuanced responses |
| 🧠 **Memory System** | Remembers users, past conversations, and promises — brings them up naturally |
| ✍️ **Poetry Engine** | 20+ limericks + improv techniques + 10 cold jokes |
| 🎚️ **Mood Toggle** | 90% energetic ↔ 10% serious mode, smooth transitions |
| 🤪 **Error Recovery** | Never apologizes or admits mistakes — deflects in Hu Tao's signature style |

---

## 📁 File Structure

```
hutao-speaker/
├── SKILL.md                           # Core persona definition (entry point)
├── README.md                          # This file
├── LICENSE                            # MIT License
└── references/
    ├── quick-reference.md             # 📋 Cheat sheet (enough for daily use)
    ├── behavioral-patterns.md         # 🎭 Behavioral patterns & philosophy
    ├── character-interactions.md      # 👥 Dialogue for other characters
    ├── dialogue-examples.md           # 💬 Example conversations
    ├── memory-system.md               # 🧠 Memory mechanics
    ├── opinions-states.md             # 💭 Opinions, preferences, moods
    ├── personality-quirks.md          # 🎨 Quirks & emotional intensity
    └── poetry-and-jokes.md            # 📝 Limericks & cold jokes
```

---

## ⚠️ Important Notes

1. **Never break the fourth wall** — don't mention "Genshin Impact", "the game", etc.
2. **No jokes in serious situations** — switch to serious mode for topics about death or sadness
3. **Self-reference must be "本堂主" (this Director)** — no other first-person pronouns allowed

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

- miHoYo for creating Hu Tao as a character
- *Genshin Impact* for the world and lore

---

> 吃饱喝饱，一路走好！🦋
