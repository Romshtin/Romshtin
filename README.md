# Привет, я Роман 👋

**Автоматизирую задачи с помощью ИИ.<br>Раньше — тестировщик, автотестировщик, разработчик. Сейчас расту в руководителя проекта.**
&nbsp;
## 🚀 Что делаю сейчас

- **Автоматизация с ИИ**

  Решаю задачи: от создания сайтов под конкретные нужды до разработки AI-чатботов с памятью и пониманием контекста

- **Project Management**

  Организую работу команд, планирую сроки и обеспечиваю качество продукта
&nbsp;

## 💬 Проект: AI-чат-бот «ВкусГрад»

**Telegram-бот с искусственным интеллектом для службы поддержки доставки еды**

- **Умные ответы**

  Бот понимает вопросы на естественном языке и ищет ответы в базе знаний (RAG)

- **Статус заказа**

  Пользователь отправляет номер, бот показывает статус и предлагает повторить заказ

- **Возвраты и проблемы**

  Многошаговый диалог: причина → номер → детали → фото → подтверждение

- **Эскалация оператору**

  Когда бот не уверен, сохраняет обращение для человека

**Стек:** aiogram, LangChain, FAISS, Ollama, FastAPI, SQLite → [chat-bot](https://github.com/Romshtin/chat-bot)
&nbsp;

## 📚 База знаний и MCP

**Локальная цифровая база знаний в формате Markdown с семантическим поиском через MCP-сервер**

- **Локальное хранение**

  Заметки и исходники книг хранятся локально; авторские материалы исключены из Git через `.gitignore`

- **Векторный индекс**

  LanceDB + SentenceTransformers (`all-MiniLM-L6-v2`) для семантического поиска по заметкам

- **MCP-сервер**

  Интеграция с Claude Code через Model Context Protocol: добавляй `.md`-файлы — они проиндексируются автоматически

- **Безопасность**

  Никакие секреты, IP-адреса, токены или персональные данные не хранятся в репозитории

**Стек:** LanceDB, SentenceTransformers, MCP → [knowledge_base](https://github.com/Romshtin/knowledge_base)
&nbsp;

## 🔍 Поиск людей в Telegram/VK

**Разведывательный пайплайн для Claude Code: собирает публичные посты и комментарии из открытых Telegram-каналов и VK-групп, фильтрует по взвешенным маркерам и складывает в JSON-архив для ручного разбора**

- **Два источника**

  Telegram (Telethon + SOCKS5-мост) и VK (API с user/service токенами)

- **Маркерная фильтрация**

  Взвешенные маркеры и минимальный score — остаются только релевантные записи

- **PowerShell-скилл**

  Запуск из Claude Code одной командой: `/find_ppl` — подъём моста, сбор, фильтрация, гашение моста

- **Этичные ограничения**

  Только публичные данные, без спама, без автоматизации авторизации, без хранения секретов в репе

**Стек:** Telethon, python-socks, requests, PKCE VK ID SDK, PowerShell 5.1 → [find_ppl](https://github.com/Romshtin/find_ppl)
&nbsp;

## 🔧 Бэкграунд

- **QA Engineer**

  Ручное и исследовательское тестирование, аналитика качества

- **Automation QA**

  Selenium, API-тесты, CI/CD пайплайны, Postman, Python

- **Developer**

  Автоматизация на Python, скрипты, внутренние инструменты

- **AI Automator**

  LLM, агентные сценарии, RAG-системы, MCP
&nbsp;

## 🛠️ Стек

- **AI / LLM**

  Ollama, LangChain, FAISS, SentenceTransformers, MCP

- **Backend**

  Python, FastAPI, aiogram, SQLite, pydantic

- **QA / Автоматизация**

  Selenium, pytest, Postman, Git, CI/CD

- **Векторные базы**

  LanceDB, semantic search, embeddings
&nbsp;

## 📫 Контакты

[![Telegram](https://img.shields.io/static/v1?style=for-the-badge&logo=telegram&message=telegram&label=&color=4165a3&labelColor=000000)](https://t.me/Romshtin)
[![Email](https://img.shields.io/static/v1?style=for-the-badge&logo=gmail&message=gmail&label=&color=e8203b&labelColor=000000)](mailto:roman.kirillov.qa@gmail.com)
