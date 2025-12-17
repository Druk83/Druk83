# Привет! Я Druk

Разрабатываю **terminal-first AI-инструменты и CLI-агентов**. Люблю проекты, где всё работает локально, оффлайн и воспроизводимо: два режима (автономный агент и прямое управление из терминала), строгая телеметрия и минимум «магии».

---

## GitHub сводка (декабрь 2025)
- `7` публичных репозиториев (Rust, Batchfile, Jupyter, JavaScript); профиль запущен ― 28.11.2023.
- Свежие коммиты: **RRDCS** (06.12.2025), **micromap** fork (19.10.2025), **clip_rs** (16.10.2025), **summific** (12.10.2025).
- Фокус: терминальные quality-gates, оффлайн CLIP-инференс, Windows-утилиты подготовки кода и MCP-интеграции.

---

## Основные проекты 2025
- **RRDCS** (`Rust/Docs`, main) ― Robot-Resistant Development Control System. Линейка fail-fast quality gates (покрытие 80%+, стилевые чекеры, ArcUnit, SAST) и tooling слой (CLI, REST API, IDE-плагины, git hooks) для работы без Copilot/LLM-зависимости. <https://github.com/Druk83/RRDCS>
- **clip_rs v0.1.0** (`Rust`, ONNX + Candle) ― локальная переимплементация OpenAI CLIP с CPU inference. CLI `clip-cli`, Rust API, примеры, оффлайн-политика тестов и управление весами через `CLIP_WEIGHTS_DIR`. <https://github.com/Druk83/clip_rs>
- **Summific v0.2.0** (`Batchfile`, Windows 11) ― десктоп-инструмент «собрать проект в читаемые тома». Интеграция в контекстное меню Explorer («Summific folder» / «Summific ignore list»), сортировка по языкам, фильтры, готовые бандлы для LLM и Model Context Protocol. <https://github.com/Druk83/summific>
- **micromap fork** (`Rust`) ― стековый linear map без heap/хешей для микросетей (≤20 ключей). Держу актуальные бенчмарки, документацию и синк с upstream (yegor256/micromap). <https://github.com/Druk83/micromap>
- **NVSOR** (`Jupyter Notebook`) ― Neural Video Search with Object Recognition: пайплайн CLIP-эмбеддингов, FAISS-индекса и Google Colab (T4) для быстрого поиска по видеофрагментам. <https://github.com/Druk83/NVSOR>

---

## Формат и инструменты
- **Terminal-first AI Agents** ― stateless/stateful режимы, конфигурация через `.env`/YAML, запуск из CLI/cron/CI.
- **Direct control** ― ручные CLI-команды без прослойки «агент»; всё скриптуется и повторяется.
- **AI-инструменты для кода** ― минификация, диффы, статический анализ, эмбеддинги и автономные пайплайны.
- **OSS-реинжиниринг и исследования** ― переписываю libs (CLIP → Rust, micromap), веду README/ADR, пишу статьи.

---

## Публикации
- [Минификация кода и LLM: миф или польза?](https://habr.com/ru/articles/931508/)
- [Микросервисы и авто-масштабирование: путь к динамическим RPA-платформам](https://habr.com/ru/articles/928918/)

---

## Принципы
- **CLI-first** ― весь функционал доступен из терминала, GUI опционален.
- **Deterministic & Reproducible** ― фиксированные версии, кеши, режим offline.
- **Observability** ― структурные логи (`key=value`, `p95_ms`, `rss_mb`), `--debug`, понятные метрики.
- **Secure by default** ― локальная обработка, политика весов/моделей, минимум телеметрии.

---

## Стек
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)

---

## Статистика
![GitHub stats](https://github-readme-stats.vercel.app/api?username=Druk83&show_icons=true&theme=dark&hide_border=true&count_private=true&t=1733515200)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Druk83&layout=compact&theme=dark&hide_border=true&t=1733515200)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Druk83&theme=dark&hide_border=true&t=1733515200)

---

## Контакты
- Email: <drukdruking83@gmail.com>
- Telegram: [@druk83](https://t.me/druk83)

<details>
<summary>EN version</summary>

## Hi, I'm Druk

I build **terminal-first AI tools and CLI agents**. Everything runs locally/offline, supports both autonomous agent mode and direct keyboard control, and ships with reproducible telemetry.

---

## GitHub digest (Dec 2025)
- `7` public repositories (Rust, Batchfile, Jupyter, JavaScript); profile created on Nov 28, 2023.
- Active repos: **RRDCS** (updated 06 Dec 2025), **micromap** fork (19 Oct 2025), **clip_rs** (16 Oct 2025), **summific** (12 Oct 2025).
- Focus areas: terminal quality gates, offline CLIP inference, Windows tooling for AI-ready code bundles.

---

## Key projects
- **RRDCS** ― Robot-Resistant Development Control System with fail-fast gates (>=80 % coverage, style checks, ArcUnit, SAST) plus tooling layer (CLI, REST, IDE add-ons, git hooks). <https://github.com/Druk83/RRDCS>
- **clip_rs v0.1.0** ― Rust reimplementation of OpenAI CLIP (ONNX + Candle backends, CPU inference, `clip-cli`, offline weights/tests). <https://github.com/Druk83/clip_rs>
- **Summific v0.2.0** ― Windows desktop tool that merges codebases into language-specific volumes, adds Explorer context menu entries, honors ignore lists, exports AI/LLM-ready artifacts with MCP support. <https://github.com/Druk83/summific>
- **micromap fork** ― stack-only linear map for micro-sized datasets; keeps upstream benchmarks/docs in sync (yegor256/micromap). <https://github.com/Druk83/micromap>
- **NVSOR** ― Neural Video Search with Object Recognition (CLIP embeddings + FAISS index + Google Colab workflow) for instant scene retrieval. <https://github.com/Druk83/NVSOR>

---

## Workflow
- **Terminal-first AI agents** with `.env`/YAML config, stateless/stateful modes, cron/CI friendly.
- **Direct control** via scripts and CLI without extra agent layers for fast one-off runs.
- **AI code tooling** for minification, diffs, static checks, embeddings, autonomous pipelines.
- **OSS rewrites & research** across CLIP, micromap, and supporting docs/ADRs.

---

## Publications
- [Code Minification and LLMs: Myth or Benefit?](https://habr.com/ru/articles/931508/)
- [Microservices and Auto-scaling: Path to Dynamic RPA Platforms](https://habr.com/ru/articles/928918/)

---

## Principles
- **CLI-first**, optional GUI.
- **Deterministic & reproducible** builds, caches, offline mode.
- **Observability** with structured logs (`key=value`, `p95_ms`, `rss_mb`) and `--debug`.
- **Secure by default** ― local processing plus tight model/weights policy.

---

## Contacts
- Email: <drukdruking83@gmail.com>
- Telegram: [@druk83](https://t.me/druk83)

</details>

---
