<p align="center">
  <img src="banner.png" alt="u4lab banner" width="100%">
</p>
# 👨‍💻 u4lab | Backend Engineer & Bot Infrastructure Architect

Проектирую и внедряю сложные распределенные системы, автоматизацию бизнес-логики и высоконагруженные мосты между платформами. Мой фокус — **Performance**, **Scalability** и **Reverse Engineering**.

---

### 🛠 Tech Stack

* **Core:** Python 3.11+ (Asyncio), C++ (Basics)
* **Frameworks:** FastAPI, Aiogram 3.x, Discord.py, Starlette
* **Data:** PostgreSQL (SQLAlchemy / Asyncpg), MongoDB (Motor), Redis (FSM & Caching)
* **Ops:** Docker & Compose, Poetry, Nginx, CI/CD, Linux Server Management
* **Expertise:** API Reverse Engineering, Multi-tenant Architecture, Media Processing Pipelines, Message Routing Systems.

---

### 🏗 Key Projects & Expertise

#### 🔒 DocPulse PA-2.0 (Private Framework)
**Professional Parser Agent Infrastructure**
* Разработал модульный фреймворк для управления жизненным циклом парсер-агентов (Runtime: Start/Stop/Status).
* Внедрил систему `DirectSender` с механизмом экспоненциальных повторов (Exponential Backoff) для гарантированной доставки данных в бэкенд.
* Реализовал изолированный `MediaManager` для валидации, обработки и ротации временных медиа-файлов.

#### 🚀 AMultibot
**High-Efficiency Multi-tenant Gateway**
* Архитектура для запуска неограниченного количества независимых ботов на одном инстансе FastAPI.
* Динамическая регистрация вебхуков и изоляция данных между инстансами.
* Оптимизация ресурсов: общая бизнес-логика при раздельных контекстах данных.

#### 🕊 TWFeed & Disresend
**Cross-Platform Integration & Reverse Engineering**
* **TWFeed:** Построил систему доставки контента из Twitter/X без использования официального API. Внедрил рендеринг твитов в PNG через Playwright для сохранения оригинального визуального стиля.
* **Disresend:** Enterprise-решение для синхронизации Discord и Telegram. Сложная обработка Markdown-разметки, вложений и трансляция Cross-Replies между несовместимыми API.
* Использование мультипроцессности (DPC) для обеспечения стабильности парсеров.

#### 💬 MsgRelayBot
**Customer Support Infrastructure**
* Система двустороннего релея сообщений (CRM-like) на базе Telegram Forum Topics.
* Архитектура «один топик = один клиент», позволяющая вести сотни диалогов внутри одной группы.
* Полная интернационализация (i18n) и управление конфигурацией через ENV для быстрой кастомизации.

---

### 📊 Engineering Philosophy

- **Clean Code:** Предпочитаю строгую типизацию и следование принципам SOLID.
- **Robustness:** Любая внешняя интеграция должна иметь механизмы обработки ошибок и автоматического восстановления.
- **Security:** Безопасное хранение токенов и шифрование чувствительных данных.

---

### 📞 Connect with me
* **News & Tech:** [@u4_studio](https://t.me/u4_studio)
* **Contact & Info:** [@u4_about](https://t.me/u4_about)

---
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=u4lab&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
</p>
