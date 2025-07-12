# PromptSync

**Intelligent synchronization between ChatGPT (LLM) and your daily schedule.**

PromptSync is an innovative solution that connects large language models like ChatGPT with personal productivity tools — such as Google Calendar, Google Tasks, and other scheduling/task apps — to automate, plan, sync, and organize your daily routine.

> **Automate your day. Manage events and tasks. Get smart feedback. Sync with ease.**

---

## ✨ Key Features

- Automated daily planning with context-aware decisions powered by AI.
- Routine export as smart, encoded URLs.
- Bidirectional synchronization with Google Calendar, Tasks, and (soon) Gmail.
- Generation and parsing of return files (JSON, ICS, etc).
- Support for multiple calendars and categories (e.g., Rescheduled, Completed).
- Extensible design for future integrations (Apple Calendar, Microsoft 365, etc).

---

## 📦 Modular Architecture

PromptSync is organized as a product composed of microservices. Planned modules include:

- `core`: core logic and routine interpretation engine
- `api`: public interface for incoming/outgoing links (GET/POST)
- `calendar-adapter`: interface to calendar services (Google Calendar, etc)
- `tasks-adapter`: interface to task services (Google Tasks, etc)
- `mail-scanner` *(upcoming)*: email parsing to create actionable tasks

---

## ⚖️ Licensing

This project uses a **dual licensing model**:

- **Apache License 2.0** – for personal, educational, or community use.
- **Commercial License** – required for corporate use or monetized products.

**You are free to use, modify, and distribute this code under Apache 2.0**, provided that:
- You do not use the name `PromptSync` for commercial purposes without permission;
- You contact the author to obtain a commercial license when required.

📩 **For commercial inquiries**: [contact@promptsync.dev](mailto:contact@promptsync.dev)

---

## 🚧 Project Status

🚀 In early development – awaiting initial commits, API documentation, and infrastructure setup on Google Cloud Platform.

---

## 📌 Contributions

Contributions are welcome! This project will be open to community contributions for technical improvements, adaptations, and integrations. Contribution guidelines will be published soon.

---

## 📚 Documentation

Under construction. Follow the first modules and diagrams coming soon.

---

📖 **Portuguese version available in [LEIAME.md](./LEIAME.md)**
