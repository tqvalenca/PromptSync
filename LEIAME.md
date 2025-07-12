# PromptSync

**Integração inteligente entre o ChatGPT (IA/MLG) e sua agenda diária.**

PromptSync é uma solução inovadora que conecta modelos de linguagem generativa (LLMs), como o ChatGPT, com serviços de produtividade pessoal — como Google Calendar, Google Tasks e outros apps de agenda/tarefas — para automatizar, planejar, sincronizar e organizar sua rotina.

> **Automatize seu planejamento diário. Gerencie compromissos e tarefas. Receba feedbacks inteligentes. Sincronize com facilidade.**

---

## ✨ Principais Recursos

- Planejamento diário automatizado com suporte a decisões contextuais feitas por IA.
- Exportação da rotina como links inteligentes via URL codificada.
- Sincronização bidirecional com Google Calendar, Tasks e (em breve) Gmail.
- Geração e leitura de arquivos de retorno (JSON, ICS, etc).
- Suporte para múltiplos calendários e categorias (ex: Reprogramado, Concluído).
- Design extensível para integração futura com Apple Calendário, Microsoft 365 e mais.

---

## 📦 Estrutura Modular

O PromptSync é estruturado como um produto composto por microsserviços. Entre os módulos planejados:

- `core`: motor de processamento e interpretação de rotina
- `api`: ponto de entrada e saída para links externos (GET/POST)
- `calendar-adapter`: interface com serviços de calendário (Google Calendar, etc)
- `tasks-adapter`: interface com serviços de tarefas (Google Tasks, etc)
- `mail-scanner` *(futuro)*: captura de e-mails importantes como tarefas

---

## ⚖️ Licença

Este projeto é distribuído sob **licença dupla**:

- **Apache License 2.0** – para uso pessoal, educacional ou comunitário.
- **Licença comercial restrita** – obrigatória para uso por empresas, entidades comerciais, ou produtos derivados com fins lucrativos.

**Você pode usar, estudar, modificar e compartilhar o código livremente sob os termos da Apache 2.0**, desde que:
- Não utilize o nome `PromptSync` para fins comerciais sem autorização;
- Para uso comercial, entre em contato com o autor para obter licença específica.

📩 **Solicitações comerciais**: [contact@promptsync.dev](mailto:contact@promptsync.dev)

---

## 🚧 Status do Projeto

🚀 Em desenvolvimento inicial – aguardando primeiros commits, documentação da API e configuração da infraestrutura no Google Cloud Platform.

---

## 📌 Contribuições

Contribuições são bem-vindas! Este projeto será aberto à comunidade para evoluções técnicas, correções, adaptações e integrações. Instruções detalhadas de contribuição serão publicadas em breve.

---

## 📚 Documentação

Em construção. Acompanhe os primeiros módulos e diagramas no repositório em breve.

---

📖 **English version available in [README.md](./README.md)**
