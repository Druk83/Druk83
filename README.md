# Привет! Я Druk

Разрабатываю **terminal-first AI-инструменты и CLI-агентов**. Люблю проекты, где всё работает локально, оффлайн и воспроизводимо: два режима (автономный агент и прямое управление из терминала), строгая телеметрия и минимум «магии».

---

## GitHub сводка (январь 2026)
- `8` публичных репозиториев (Rust, Batchfile, Jupyter, JavaScript); профиль запущен ― 28.11.2023.
- Свежие коммиты: **TrainingGround** (01.01.2026), **RRDCS** (06.12.2025), **micromap** fork (19.10.2025), **clip_rs** (16.10.2025), **summific** (12.10.2025).
- Фокус: терминальные quality-gates, оффлайн CLIP-инференс, Windows-утилиты подготовки кода и MCP-интеграции.

---

## Ключевые проекты
- **RRDCS** (`Rust/Docs`, main) ― Robot-Resistant Development Control System. Линейка fail-fast quality gates (покрытие 80%+, стилевые чекеры, ArcUnit, SAST) и tooling слой (CLI, REST API, IDE-плагины, git hooks) для работы без Copilot/LLM-зависимости. <https://github.com/Druk83/RRDCS>
- **clip_rs v0.1.0** (`Rust`, ONNX + Candle) ― локальная переимплементация OpenAI CLIP с CPU inference. CLI `clip-cli`, Rust API, примеры, оффлайн-политика тестов и управление весами через `CLIP_WEIGHTS_DIR`. <https://github.com/Druk83/clip_rs>
- **MASS** (`Rust`) ― backend для системы MASS (Microservices Automation & Scripting System): автоматическая генерация RPA‑микросервисов из текстовых описаний, веб‑интерфейс, Docker-интеграция и мониторинг (Prometheus/Grafana). <https://github.com/Druk83/mass>
- **TrainingGround** (`TypeScript/Rust/Python`) ― тренировочный полигон по русскому языку: PWA + Rust API + Python генератор, dev quickstart, мониторинг и инфраструктурные скрипты. <https://github.com/Druk83/TrainingGround>
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
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash)
![PowerShell](https://img.shields.io/badge/PowerShell-012456?style=for-the-badge&logo=powershell)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch)
![ONNX](https://img.shields.io/badge/ONNX-000000?style=for-the-badge&logo=onnx)
![FAISS](https://img.shields.io/badge/FAISS-262626?style=for-the-badge)
![Postgres](https://img.shields.io/badge/Postgres-316192?style=for-the-badge&logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis)
![FFmpeg](https://img.shields.io/badge/FFmpeg-000000?style=for-the-badge&logo=ffmpeg)
![Qdrant](https://img.shields.io/badge/Qdrant-0FC3C3?style=for-the-badge)

 

---

## Статистика
<!-- Social / compact badges (static fallbacks when API badges are down) -->
[![trophy](https://github-profile-trophy.vercel.app/?username=Druk83&theme=dark&no-frame=true)](https://github.com/Druk83) [![GitHub](https://img.shields.io/badge/GitHub-Druk83-181717?style=social&logo=github)](https://github.com/Druk83) [![Top Lang](https://img.shields.io/badge/Top%20Lang-Rust-orange?style=flat&logo=rust)](https://github.com/Druk83)

<!-- Contributions heatmap (alternative to full stats) -->
![contributions](https://ghchart.rshah.org/Druk83)

*Badges auto-update — last checked: 2026-01-02. Some dynamic badge services (e.g., `github-readme-stats`) may be temporarily unavailable; we use static fallbacks to avoid broken images.*

---

## Контакты
- Email: <drukdruking83@gmail.com>
- Telegram: [@druk83](https://t.me/druk83)

<details>
<summary>EN version</summary>

## Hi, I'm Druk

I build **terminal-first AI tools and CLI agents**. Everything runs locally/offline, supports both autonomous agent mode and direct keyboard control, and ships with reproducible telemetry.

---

## GitHub digest (Jan 2026)
- `8` public repositories (Rust, Batchfile, Jupyter, JavaScript); profile created on Nov 28, 2023.
- Active repos: **TrainingGround** (01 Jan 2026), **RRDCS** (updated 06 Dec 2025), **micromap** fork (19 Oct 2025), **clip_rs** (16 Oct 2025), **summific** (12 Oct 2025).
- Focus areas: terminal quality gates, offline CLIP inference, Windows tooling for AI-ready code bundles.

---

## Key projects
- **RRDCS** ― Robot-Resistant Development Control System with fail-fast gates (>=80 % coverage, style checks, ArcUnit, SAST) plus tooling layer (CLI, REST, IDE add-ons, git hooks). <https://github.com/Druk83/RRDCS>
- **clip_rs v0.1.0** ― Rust reimplementation of OpenAI CLIP (ONNX + Candle backends, CPU inference, `clip-cli`, offline weights/tests). <https://github.com/Druk83/clip_rs>
- **Summific v0.2.0** ― Windows desktop tool that merges codebases into language-specific volumes, adds Explorer context menu entries, honors ignore lists, exports AI/LLM-ready artifacts with MCP support. <https://github.com/Druk83/summific>
- **micromap fork** ― stack-only linear map for micro-sized datasets; keeps upstream benchmarks/docs in sync (yegor256/micromap). <https://github.com/Druk83/micromap>
- **MASS Backend** (`Rust`) — backend for MASS (Microservices Automation & Scripting System): generates RPA microservices from text prompts, web UI, Docker integration and Prometheus/Grafana monitoring. <https://github.com/Druk83/mass>
- **TrainingGround** (`TypeScript/Rust/Python`) — language training playground for Russian (PWA + Rust API + Python generator), with developer quickstart and monitoring. <https://github.com/Druk83/TrainingGround>
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
