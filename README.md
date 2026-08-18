<div align="center">

<img src="https://momaiassistente.studio/icon.png" width="200" alt="MomAI" />

# MomAI

**Your proactive AI assistant that respects your privacy**

[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Download-0078D4?style=for-the-badge&logo=microsoft)](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=en-US&gl=US)
[![Site](https://img.shields.io/badge/Site-momaiassistente.studio-8B5CF6?style=for-the-badge&logo=google-chrome)](https://momaiassistente.studio/)

</div>

## About

MomAI's long-term goal is to be a **proactive** assistant: analyze incoming data, understand context, and perform tasks autonomously based on your habits and preferences. Everything runs locally, without compromising your privacy.

**What is already implemented today:**

- **Extension system.** Add new capabilities through the built-in store. Extensions are self-contained packages with React UI and their own manifest.
- **3 voice synthesis options.** Edge TTS (cloud), Kokoro ONNX (local, streaming) and say.js (local fallback). Choose between quality and privacy.
- **3 operation modes.** Run according to your hardware: light mode for modest machines, balanced mode, and maximum mode for dedicated GPUs.
- **Complete Markdown notes system.** Create, edit and manage notes by text or voice. MomAI organizes everything intelligently.
- **Smart memory.** MomAI remembers information across sessions, building a persistent context about you.
- **Web and YouTube search.** Search the web for up-to-date information and find videos without opening a browser.
- **Voice commands.** Activate with the wake word ("Sistema") and use the assistant hands-free.
- **Total privacy.** No sensitive data is sent to our own servers. No sign-up, no login, no tracking.

## Official Extensions

| Extension | Description | Repository |
|-----------|-------------|------------|
| WhatsApp Web | WhatsApp integration: monitor conversations, receive notifications, and reply to messages | [WesleyQDev/momai-whatsapp-extension](https://github.com/WesleyQDev/momai-whatsapp-extension) |
| MomAIOpen | Open programs, files and folders using natural language commands | [WesleyQDev/momai-open](https://github.com/WesleyQDev/momai-open) |
| MomAI Vision | Computer vision: camera snapshots, object detection and monitoring alerts, fully local | [WesleyQDev/momai-vision](https://github.com/WesleyQDev/momai-vision) |
| MomAI Smart Home | Control Home Assistant devices, including lights, TVs, climate, sensors and more | [WesleyQDev/MomAISmartHome](https://github.com/WesleyQDev/MomAISmartHome) |

## Stack

| Layer | Technology |
|-------|------------|
| Desktop | Electron, React, TypeScript, TailwindCSS |
| Build | electron-vite, pnpm, Turborepo |
| AI Orchestration | Node.js, LangGraph, LangChain |
| Semantic Search | LanceDB |
| Voice Backend | Python 3.12+, FastAPI, faster-whisper, Kokoro ONNX |
| TTS | edge-tts-universal, Kokoro ONNX, say.js |
| Testing | Vitest (desktop), pytest (core) |

## Watch

<div align="center">

[![MomAI](https://img.youtube.com/vi/fzyV0VCn_ZM/0.jpg)](https://youtu.be/fzyV0VCn_ZM)

</div>

## Availability

**Windows.** Microsoft Store, Winget (`winget install MomAI`) or direct download from the website and Releases.

**Linux.** Available from the official website and Releases.

Versions are developed for Windows first. If you find issues, bug reports are always welcome.

---

<div align="center">

<small><em>MomAI does not collect personal data to its own servers. Processing and storage are local.</em></small>

</div>

## Links

- [Microsoft Store](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=en-US&gl=US)
- [Official Website](https://momaiassistente.studio/)
- [Releases](https://github.com/WesleyQDev/MomAI-App/releases)
