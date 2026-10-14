<p align="center">
  <img src="https://raw.githubusercontent.com/SGC-NOVUS/.github/main/assets/banner.jpg" alt="SGC-NOVUS Banner" width="100%">
</p>

<div align="center">

# SGC-NOVUS
### System Generations Core • Decoupled Cloud Infrastructure & Sovereign Identity

[![NOVUS•OS](https://img.shields.io/badge/Web--OS-NOVUS•OS-00C7FF?style=for-the-badge&logo=linux&logoColor=white)](https://panel.sgc-novus.xyz)
[![Go Agent](https://img.shields.io/badge/Agent-Go_1.24-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://sgc-novus.fun)
[![PHP Engine](https://img.shields.io/badge/Backend-PHP_8.5+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://panel.sgc-novus.xyz)
[![Zero-Knowledge](https://img.shields.io/badge/Security-AES--256--GCM-success?style=for-the-badge&logo=shield&logoColor=white)](https://sgc-novus.fun)

<br/>

**🌐 Язык / Мова / Language:**  
**[ 🇬🇧 English ](#-english-overview)** • **[ 🇺🇦 Українська ](#-українська-версія)** • **[ 🇷🇺 Русский ](#-русская-версия)**

---

### 🔗 Production Endpoints & Ecosystem Network

| Сервис | Назначение | Боевой URL |
| :--- | :--- | :--- |
| **Официальный портал** | Презентация экосистемы, продукты и манифест | [sgc-novus.fun](https://sgc-novus.fun) |
| **NOVUS•OS Web-OS** | Панель управления кластером, сайтами и процессами | [panel.sgc-novus.xyz](https://panel.sgc-novus.xyz) |
| **NovusID Gateway** | Единая точка аутентификации (SSO, OAuth2, токены) | [id.sgc-novus.fun](https://id.sgc-novus.fun) |
| **Документация и API** | Архитектурные спецификации и технические гайды | [sgc-novus.fun/docs](https://sgc-novus.fun/docs) |
| **Flow Orchestrator** | Потоковые микросервисы и шина интеграций | [flow.sgc-novus.fun](https://flow.sgc-novus.fun) |
| **Novus Life Runtime** | Интеллектуальный шлюз ботов и автоматизации | [bot.novus-life.online](https://bot.novus-life.online) |

---

</div>

## 🇬🇧 English Overview

**SGC-NOVUS** (*System Generations Core Novus*) is an enterprise-grade cloud ecosystem and automated Web-OS architecture designed for sovereign infrastructure management, zero-dependency cloud backups, and process orchestration.

### Key Architectural Pillars:
- **NOVUS•OS (Unified Web-OS):** Eliminates raw server file modifications. Delivers transactional Nginx management with atomic syntax verification (`nginx -t`), global 50x error interception, and automated SSL orchestration via pure Go `lego` (HTTP-01 & Cloudflare Wildcard DNS-01).
- **Core Supervisor (`novus-agent`):** In-kernel Go daemon handling multi-runtime services (Go, Node.js, Python WSGI/ASGI, PHP-FPM) with crash recovery, live WebSocket telemetry, and container lifecycle supervision.
- **librclone CloudVFS & Zero-Knowledge Engine:** Native, in-process cloud synchronization with Google Drive, AWS S3, Cloudflare R2, and SFTP. Utilizes sandboxed OAuth App Folders (`drive.file`) to guarantee zero-audit cloud security and enforces client-side AES-256-GCM encryption before data leaves the cluster.

---

<details>
<summary><b>🇺🇦 Українська версія (Натисніть, щоб розгорнути)</b></summary>
<br/>

## 🇺🇦 Огляд екосистеми SGC-NOVUS

**SGC-NOVUS** (*System Generations Core Novus*) — хмарна інженерна екосистема та платформа Web-OS нового покоління, створена для автономного керування серверами, мікросервісами, контейнерами та ізольованими сховищами.

### Ключові технологічні модулі:
- **NOVUS•OS (Керування веб-ресурсами):** Повний перехід від ручного редагування конфігураційних файлів до транзакційного UI/UX. Атомарна збірка віртуальних хостів Nginx із пре-валідацією синтаксису, фірмовий перехоплювач помилок 50x та вбудований випуск сертифікатів через Go-рушій `lego` (Let's Encrypt та Cloudflare Wildcard DNS-01).
- **Системний супервізор (`novus-agent`):** Автономний Go-демон, що керує фоновими процесами (Go, Node.js, Python, PHP-FPM), забезпечує миттєвий авто-перезапуск при збоях та транслює live-логи через WebSocket.
- **CloudVFS та Zero-Knowledge бекапи:** Пряма інтеграція `librclone` всередині Go-агента без системних FUSE-нестиковок. Вивантаження даних в ізольовані папки застосунків (Google Drive, S3, Cloudflare R2, SFTP) без проходження платних аудитів Google та наскрізне шифрування AES-256-GCM.

</details>

---

<details>
<summary><b>🇷🇺 Русская версия (Нажмите, чтобы развернуть)</b></summary>
<br/>

## 🇷🇺 Обзор экосистемы SGC-NOVUS

**SGC-NOVUS** (*System Generations Core Novus*) — программный комплекс и облачная платформа Web-OS для сквозного управления серверными ресурсами, сайтами, базами данных и распределёнными сервисами.

### Ключевые возможности платформы:
- **NOVUS•OS (Панель и Веб-сервер):** Транзакционный Nginx-контроллер с проверкой синтаксиса до применения, защита от падений веб-сервера, стилизованная страница 50x и нативный ACME Lego-контроллер без внешнего Certbot на Python.
- **Мульти-рантайм Супервизор:** Встроенный в Go-агент менеджер процессов с поддержкой Go-бинарников, приложений Node.js, Python (Gunicorn/Uvicorn), изоляцией прав и живым стримингом логов (Access, Error, Console).
- **Облачный VFS-движок резервного копирования:** Встроенная библиотека `librclone` для прямой работы с Google Drive, S3, Cloudflare R2 и SFTP. Изоляция в безопасные App Folders (не требующие платных аудитов безопасности) и сквозное Zero-Knowledge шифрование архивов на лету (AES-256-GCM).

</details>

---

## 🛠 Technology Stack

<div align="center">
┌────────────────────────────────────────────────────────────────────────┐
│                        SGC-NOVUS ECOSYSTEM                             │
├───────────────────┬───────────────────┬────────────────────────────────┤
│   FRONTEND LAYER  │   BACKEND CORE    │      SYSTEM DAEMON (ROOT)      │
│   Vue 3 / Vite    │   PHP 8.5+ FPM    │   Go 1.24 novus-agent          │
│   TypeScript      │   PostgreSQL 18   │   librclone Engine (VFS)       │
│   TailwindCSS     │   MariaDB 11.x    │   ACME lego (HTTP/DNS-01)      │
│   PWA Manifest    │   Unix Socket IPC │   Process & Crash Supervisor   │
└───────────────────┴───────────────────┴────────────────────────────────┘
</div>

---

<div align="center">

<sub>© 2026 SGC-NOVUS • System Generations Core Novus. Odesa, Ukraine. All rights reserved.</sub>

</div>
