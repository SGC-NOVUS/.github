<div align="center">

# SGC-NOVUS
### System Generations Core • Next-Generation Cloud Ecosystem

[![Web-OS Platform](https://img.shields.io/badge/Platform-NOVUS•OS-00C7FF?style=for-the-badge&logo=linux&logoColor=white)](https://sgc-novus.fun)
[![Core Agent](https://img.shields.io/badge/Agent-Go_1.24-00ADD8?style=for-the-badge&logo=go&logoColor=white)](https://sgc-novus.fun)
[![Panel Engine](https://img.shields.io/badge/Panel-PHP_8.5+-777BB4?style=for-the-badge&logo=php&logoColor=white)](https://sgc-novus.fun)
[![Security](https://img.shields.io/badge/Encryption-AES--256--GCM-success?style=for-the-badge&logo=shield&logoColor=white)](https://sgc-novus.fun)

<br/>

**SGC-NOVUS** — инженерная экосистема и технологический комплекс для автономного управления серверной инфраструктурой, микросервисами, контейнерами и облачными шлюзами на базе **NOVUS•OS**.

[🌐 Официальный портал](https://sgc-novus.fun) • [🔑 NovusID Gateway](https://id.sgc-novus.fun) • [📚 Документация](https://sgc-novus.fun/docs)

---

</div>

## ⚡ Ключевые компоненты экосистемы

### 🖥️ NOVUS•OS (Unified Web-OS Platform)
Инновационная операционная среда для управления серверами и сервисами без прямого ручного редактирования конфигов. 
- **1-Click Controls & App Matrix:** Развёртывание сайтов, приложений и сервисов нативно (Baremetal) или в изолированных Docker-контейнерах.
- **Transactional Nginx Controller:** Атомарная сборка виртуальных хостов, пре-валидация синтаксиса (`nginx -t`) и защита от падений веб-сервера.
- **Встроенный ACME/Lego Engine:** Нативный выпуск и фоновый авто-перевыпуск SSL-сертификатов (Let's Encrypt HTTP-01 и Cloudflare Wildcard DNS-01) на чистом Go.
- **Process Supervisor:** Полный контроль жизненного цикла сервисов на Go, Node.js, Python (WSGI/ASGI) и PHP 8.5+ с авто-рестартом при сбоях.

### 🛡️ CloudVFS & Zero-Knowledge Backup Engine
- **In-Process Rclone Integration:** Автономное взаимодействие с облачными дисками (Google Drive, S3, Cloudflare R2, SFTP, OneDrive) прямо из ядра `novus-agent`.
- **Изолированные App Folders:** Работа по безопасным OAuth-скоупам (`drive.file`, `AppFolder`) без риска компрометации сторонних файлов пользователя.
- **Zero-Knowledge Encryption:** Блочное шифрование архивов (AES-256-GCM) и обфускация файловой структуры до отправки в публичные хранилища.

---

## 🛠 Технологический стек

<div align="center">

| Слой | Стек технологий |
| :--- | :--- |
| **Системный агент (Core Daemon)** | `Go (Golang)` • `librclone` • `lego (ACME)` • `Unix Sockets IPC` |
| **Панель управления (Backend)** | `PHP 8.5+` • `PostgreSQL` • `MariaDB` • `REST API` • `WebSockets` |
| **Веб-интерфейс (Frontend Web-OS)** | `Vue 3` • `TypeScript` • `Vite` • `TailwindCSS` • `PWA` |
| **Инфраструктура и Сеть** | `Nginx Reverse Proxy` • `Docker & Compose` • `FastDL Engine` • `Cloudflare API` |

</div>

---

## 🌐 Сетевая топология и ресурсы

- **Web Platform:** [sgc-novus.fun](https://sgc-novus.fun)
- **Identity & SSO Service:** [id.sgc-novus.fun](https://id.sgc-novus.fun)
- **Infrastructure Nodes:** Одесса, Украина / Распределённый кластер

---

<div align="center">

<sub>© 2026 SGC-NOVUS • System Generations Core Novus. Все права защищены.</sub>

</div>
