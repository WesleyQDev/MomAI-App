<div align="center">

<img src="https://momaiassistente.studio/icon.png" width="200" alt="MomAI" />

# MomAI

**Sua assistente proativa que respeita sua privacidade**

[![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Baixar-0078D4?style=for-the-badge&logo=microsoft)](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=pt-BR&gl=BR)
[![Site](https://img.shields.io/badge/Site-momaiassistente.studio-8B5CF6?style=for-the-badge&logo=google-chrome)](https://momaiassistente.studio/)
[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg?style=flat-square)](LICENSE)

</div>

## Sobre

O grande objetivo da MomAI é ser uma assistente **proativa**: analisar dados de entrada, entender o contexto e realizar tarefas de forma autonoma, seguindo os habitos e preferencias do usuario. Tudo localmente, sem comprometer sua privacidade.

**O que ja esta implementado hoje:**

- **Sistema de extensoes.** Adicione novas capacidades pela loja integrada. Extensoes sao pacotes auto-contidos com UI React e manifesto proprio.
- **3 tipos de sintese de voz.** Edge TTS (nuvem), Kokoro ONNX (local, streaming) e say.js (fallback local). Escolha entre qualidade e privacidade.
- **3 modos de operacao.** Execute conforme seu hardware: modo leve para maquinas modestas, modo balanceado e modo maximo para GPUs dedicadas.
- **Sistema de notas Markdown completo.** Crie, edite e gerencie notas por texto ou voz. A MomAI organiza tudo de forma inteligente.
- **Memoria inteligente.** A MomAI se lembra de informacoes entre sessoes, construindo um contexto persistente sobre voce.
- **Busca na web e no YouTube.** Pesquise informacoes atualizadas da internet e encontre videos sem abrir o navegador.
- **Comandos de voz.** Ative com a palavra de chamada ("Sistema") e use a assistente sem usar as maos.
- **Privacidade total.** Nenhum dado sensivel e enviado para servidores proprios. Sem cadastro, sem login, sem coleta.

## Extensoes Oficiais

| Extensao | Descricao | Repositorio |
|----------|-----------|-------------|
| WhatsApp Web | Integracao com WhatsApp: monitorar conversas, receber notificacoes e responder mensagens | [WesleyQDev/momai-whatsapp-extension](https://github.com/WesleyQDev/momai-whatsapp-extension) |
| MomAIOpen | Abra programas, arquivos e pastas com comandos em linguagem natural | [WesleyQDev/momai-open](https://github.com/WesleyQDev/momai-open) |

## Stack

| Camada | Tecnologia |
|--------|------------|
| Desktop | Electron, React, TypeScript, TailwindCSS |
| Build | electron-vite, pnpm, Turborepo |
| Orquestracao de IA | Node.js, LangGraph, LangChain |
| Busca Semantica | LanceDB |
| Backend de Voz | Python 3.12+, FastAPI, faster-whisper, Kokoro ONNX |
| TTS | edge-tts-universal, Kokoro ONNX, say.js |
| Testes | Vitest (desktop), pytest (core) |

## Assista

<div align="center">

[![MomAI - Assistente Local](https://img.youtube.com/vi/fzyV0VCn_ZM/0.jpg)](https://youtu.be/fzyV0VCn_ZM)

</div>

## Disponibilidade

**Windows.** Microsoft Store, Winget (`winget install MomAI`) ou executavel direto pelo site e nas Releases.

**Linux.** Disponivel pelo site oficial e nas Releases.

As versoes sao desenvolvidas primeiro para Windows. Se encontrar problemas, reports nas Issues sao sempre bem-vindos.

## Licenca

O aplicativo MomAI (codigo compilado) e distribuido sob licenca proprietaria.
Uso pessoal gratuito. Veja o arquivo [LICENSE](LICENSE) para os termos completos.

As extensoes oficiais (WhatsApp Web, MomAIOpen) sao open source e possuem
suas proprias licencas nos repositorios indicados na tabela de extensoes.

Copyright (c) 2026 WesleyQDev. Todos os direitos reservados.

---

<div align="center">

<small><em>MomAI nao coleta dados pessoais para servidores proprios. Processamento e armazenamento sao locais. Saiba mais na <a href="https://momaiassistente.studio/politicas-privacidade-momai.html">politica de privacidade</a>.</em></small>

</div>

## Links

- [Microsoft Store](https://apps.microsoft.com/detail/9nm4jg67cgcd?hl=pt-BR&gl=BR)
- [Site oficial](https://momaiassistente.studio/)
- [Releases](https://github.com/WesleyQDev/MomAI-App/releases)
