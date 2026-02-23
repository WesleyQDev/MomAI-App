<div align="center">

![MomAI](https://momaiassistente.studio/icon.gif)

[![GitHub](https://img.shields.io/badge/GitHub-WesleyQDev%2FMomAI-181717?style=for-the-badge&logo=github)](https://github.com/WesleyQDev/MomAI)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

## O que é MomAI?

A MomAI é uma assistente de inteligência artificial local. Ela não depende de internet, não exige login e não envia seus dados para nenhum servidor. Tudo roda e fica armazenado na sua própria máquina.

O nome vem da ideia de ser a "mãe" do seu sistema — ela organiza, lembra e ajuda no que for preciso. E é totalmente gratuita.

## O que ela faz hoje?
Você pode criar e gerenciar anotações, agendar lembretes com notificação por voz, e pedir para ela buscar informações na internet. A ativação por voz também já funciona: basta dizer "Luna" e ela começa a ouvir, tudo processado localmente.

Ela também detecta quando você está rodando um jogo ou processo pesado no PC e pausa os processos de IA automaticamente para não comprometer o desempenho.

### Por que usar MomAI?

- **Privacidade** - Seus dados ficam no seu computador.
- **Extensível** - Adicione apenas as funcionalidades (agentes e ferramentas) que você precisa.
- **Código Aberto** - Licença MIT, totalmente gratuito.
- **Multiplataforma** - Windows, Linux e Mac.

Requisitos
O recomendado é 16GB de RAM e uma placa de vídeo com pelo menos 6GB de VRAM. A MomAI roda modelos de linguagem localmente usando o llama.cpp com o modelo Qwen, o que exige um hardware razoável mas garante funcionamento totalmente offline.

Arquitetura
O frontend é feito em Electron com React, e o backend em Python com FastAPI. A comunicação entre os dois acontece por WebSocket e API REST. No backend, a orquestração da IA é feita com LangGraph — um sistema de agentes que decide qual ferramenta usar para cada situação.

O projeto ainda vai passar por mudanças, mas a base está sólida. A MomAI já conta com uma loja de extensões para expandir suas capacidades, e novas funcionalidades serão adicionadas com frequência através de atualizações regulares.

— WesleyQDev
