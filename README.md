<div align="center">

<img src="https://momaiassistente.studio/icon.png" width="160" alt="MomAI" />

# MomAI

**Your proactive AI assistant that respects your privacy.**

[![Latest release](https://img.shields.io/github/v/release/WesleyQDev/MomAI-App?style=for-the-badge&label=latest%20release&color=8B5CF6)](https://github.com/WesleyQDev/MomAI-App/releases) [![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-download-0078D4?style=for-the-badge&logo=microsoft)](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=en-US&gl=US) [![Documentation](https://img.shields.io/badge/docs-user%20guide-0EA5E9?style=for-the-badge&logo=readthedocs&logoColor=white)](https://momaiassistente.studio/docs/)

</div>

## What is MomAI?

MomAI is a desktop AI assistant for Windows and Linux. It chats by text or voice, remembers what matters, works with your notes and documents, and can act on your computer through extensions, always with your permission.

It is **local-first**: you can run the AI on your own machine, without an account or API key. If you prefer, connect your own cloud provider and choose a different model for each task. The long-term goal is a proactive assistant that understands context and helps before you ask; the list below covers what is available today.

This repository is the public home for MomAI releases, the extension catalog, and extension documentation. The application source code is not distributed here.

## Download

- **Windows 10/11 (x64):** [Microsoft Store](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=en-US&gl=US) (recommended) or the [direct installer](https://github.com/WesleyQDev/MomAI-App/releases/latest/download/MomAI-Installer.exe).
- **Linux (x64):** latest `.deb` package from [Releases](https://github.com/WesleyQDev/MomAI-App/releases), for Debian/Ubuntu-based distributions.
- **MomAI Server (advanced):** standalone server builds for Windows, Linux/Termux, and Docker are also available on [Releases](https://github.com/WesleyQDev/MomAI-App/releases).

MomAI is free to download. Cloud providers are optional and may charge according to their own pricing. The Microsoft Store is the recommended Windows channel; the direct installer and Linux packages are published here on GitHub.

## Highlights

- **Chat that remembers.** Talk by text or voice, keep long conversations in context, and let MomAI learn useful facts about you. Review, edit, pin, or forget anything in Settings > Memory.
- **Voice, hands-free.** Say "Luna" to wake MomAI, speak naturally, and hear replies as they are generated. Choose local Kokoro voices or the online Edge voice.
- **Local or cloud models.** Run MomAI Lite, Pro, or Ultra on your CPU/GPU, or connect Google Gemini, OpenAI, Groq, DeepSeek, OpenRouter, OpenCode Zen, or OpenCode Go with your own key. You can use a different provider and model for chat, agents, vision, and summaries.
- **Notes and documents.** Keep multiple Markdown vaults, edit with the built-in editor, follow the note graph, and open the same files in Obsidian or any text editor. Attach PDF, Word, spreadsheet, and text files to chat; MomAI indexes larger files locally and answers from the relevant sections. Up to 6 attachments and 25 MB per message.
- **Actions, not just answers.** Extensions add tools, screens, and widgets. Official integrations cover WhatsApp, desktop automation, email, smart home, vision, news, coding, and more.
- **A home screen that works for you.** Build your own layout with widgets for chat, reminders, automations, weather, and daily content. Create routines that run on a schedule or when something happens.
- **Privacy by default.** No account, no analytics, no tracking SDKs. Local models and local voice stay on your computer. When you enable a cloud provider or an online feature, only the data needed for that request leaves the device.
- **Make it yours.** Six UI languages, themes, a desktop pet, global shortcuts, accessibility controls, and a compact overlay for quick access.

## See it in action

[![Watch the MomAI demo](https://i.ytimg.com/vi/fzyV0VCn_ZM/maxresdefault.jpg)](https://youtu.be/fzyV0VCn_ZM)

<sub>Demo in Portuguese.</sub>

## Official extensions

Extensions are optional. Each one declares its permissions in the store, and you can disable or remove it at any time.

| Extension | What it adds |
| --- | --- |
| [MomAI Desktop](https://github.com/WesleyQDev/momai-desktop) | Opens programs and automates on-screen tasks, showing each step. |
| [MomAI WhatsApp](https://github.com/WesleyQDev/momai-whatsapp) | Follows and replies to WhatsApp conversations by voice or text from your PC. |
| [MomAI Smart Home](https://github.com/WesleyQDev/momai-smarthome) | Controls Home Assistant lights, TVs, climate, sensors, and more. |
| [MomAI Vision](https://github.com/WesleyQDev/momai-vision) | Camera snapshots, motion alerts, and local monitoring. |
| [MomAI E-mails](https://github.com/WesleyQDev/momai-emails) | Reads, sends, and organizes email without opening the browser. |
| [MomAI News](https://github.com/WesleyQDev/momai-noticias) | A personalized Discover-style news feed with curated and custom sources. |
| [MomAI Code](https://github.com/WesleyQDev/momai-code) | Secure terminal, file editing, and coding projects with approval rules. |
| [Holy Bible](https://github.com/WesleyQDev/momai-biblia-sagrada) | Bible study in six languages, 640 hymns, search, verse of the day, and favorites. |

Browse the full catalog in the app or on the [extension page](https://momaiassistente.studio/#/extensoes).

## Privacy and permissions

- **No account.** Download and use MomAI without signing up.
- **Local by default.** Local models, notes, memory, and settings stay on your computer.
- **Cloud is optional.** If you configure a provider or use an online feature, only the data needed for that request is sent.
- **You approve sensitive actions.** Extensions declare their permissions, and MomAI asks before running tools that need your consent.
- **No analytics.** MomAI does not include analytics or third-party tracking SDKs.
- **Verify your download.** Releases include `SHA256SUMS.txt`; the Microsoft Store is the recommended Windows channel.

Read the [privacy policy](https://momaiassistente.studio/privacy-policy-momai.html) and the [security notes](https://momaiassistente.studio/#/seguranca).

## Requirements

- **Windows:** Windows 10 or 11, x64.
- **Linux:** x64 distribution with `.deb` support (Debian/Ubuntu-based).
- **Hardware:** there is no single requirement for every model. Local models are downloaded on first use; smaller models run on the CPU, while larger models benefit from a GPU.
- **Internet:** required for downloads, updates, web search, the extension catalog, and cloud providers. Local inference works offline once the models are installed.

## Documentation and support

- [User guide](https://momaiassistente.studio/docs/) — setup, chat, voice, notes, providers, extensions, and settings.
- [Changelog](https://momaiassistente.studio/#/changelog) — what changed in each version.
- [Extension catalog](https://momaiassistente.studio/#/extensoes) — browse official and community extensions.
- [Report an issue](https://github.com/WesleyQDev/MomAI-App/issues) — include your MomAI version, operating system, and steps to reproduce. Never share API keys, passwords, or personal data.
- [Security notes](https://momaiassistente.studio/#/seguranca) — how downloads, providers, and extensions are handled.

### Build an extension

Extensions are self-contained packages with a manifest, optional React UI, tools, and widgets. The public catalog is [`v2/catalog.json`](v2/catalog.json).

- [Extension development guide](https://momaiassistente.studio/docs/dev/overview)
- [Publishing guide](https://momaiassistente.studio/docs/dev/publishing)

## License

MomAI is proprietary software, free to download and use under the terms of the [LICENSE](LICENSE). This repository hosts public releases, the extension catalog, and public extension documentation; it does not contain the application source code.

---

<div align="center">

<sub>MomAI is developed by Wesley Developer Studios. Local-first by design.</sub>

</div>
