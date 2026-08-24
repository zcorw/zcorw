# Zcorw

Frontend-focused software engineer building full-stack web applications, developer tools, and automation systems.

Primary areas include frontend architecture, API integration, system redesign, containerized deployment, and production-oriented engineering.

## Selected Projects

### FlowLedger

A personal finance and asset-management project developed across two architectural generations.

The first generation uses separate frontend and backend repositories. The backend provides both the Web API and Telegram Bot services.

The second generation redesigns the product around monthly asset snapshots, multi-currency valuation, liabilities, historical exchange rates, data import and export, automated testing, deployment, and backup workflows.

- `flow-ledger-2` — second-generation full-stack redesign
- `FlowLedger-ui` — first-generation React frontend
- `FlowLedger-server` — first-generation API and Telegram Bot services

**Stack:** React, TypeScript, FastAPI, PostgreSQL, SQLAlchemy, ECharts, Playwright, Docker

---

### PasswdMan

A personal credential vault for storing, organizing, and searching passwords and secure notes, with import and export workflows for backup and migration.

The first generation protects sensitive client–server communication with a hybrid protocol: per-session AES-CBC encryption and HMAC-SHA256 integrity protection, with the session key exchanged through RSA-OAEP.

The second generation redesigns the communication layer around X25519 key agreement and AES-GCM authenticated encryption. It also introduces end-to-end encrypted vault synchronization, allowing the server to store and synchronize only encrypted vault data.

- `PasswdMan2` — second-generation full-stack redesign in progress
- `PasswdMan-ui` — first-generation Vue frontend
- `PasswdMan-server` — first-generation NestJS backend

**Stack:** Vue, React, TypeScript, NestJS, FastAPI, MySQL, PWA, Docker

---

### FE Study System

A multi-repository study platform for Japan’s Fundamental Information Technology Engineer Examination.

The system separates the web quiz application, shared question bank, daily study automation, Telegram integration, and deployment responsibilities into independent components.

- `fe-study-system` — system overview and integration
- `fe-quiz-app` — web-based quiz application
- `fe-question-bank-service` — shared question bank service
- `fe-daily-runner` — daily study content automation

**Stack:** Next.js, React, TypeScript, FastAPI, SQLite, Telegram, Docker, Nginx

---

### [IPA Screenshot Exam Server](https://github.com/Zcorw/ipa-siken)

A screenshot-based examination service built for archived IPA examination materials.

The project stores exam metadata, question screenshots, and answer mappings in SQLite. Question pages are rendered directly from extracted image regions, avoiding a dependency on OCR-transcribed question text.

It also includes tools for extracting question images from source PDFs, automated tests for data access and page rendering, Docker-based deployment, and Git LFS management for PDFs, screenshots, and SQLite data files.

**Stack:** Node.js, SQLite, Python, HTML, CSS, Docker, Git LFS

---

### [AlignSpeak](https://github.com/Zcorw/AlignSpeak)

An AI-assisted reading and speaking practice application.

The project combines a React frontend, FastAPI backend, speech-processing workflows, and a containerized deployment structure in a single repository.

**Stack:** React, TypeScript, Vite, FastAPI, PostgreSQL, Docker

## Core Technologies

### Frontend

JavaScript, TypeScript, React, Vue, Next.js, Vite, Webpack, Material UI, Sass

### Backend

Node.js, NestJS, Express, Koa, Python, FastAPI, REST APIs

### Desktop

Electron

### Data and Infrastructure

PostgreSQL, MySQL, SQLite, Docker Compose, Nginx, Git LFS, CI/CD

### Testing and Quality

ESLint, Prettier, TypeScript

## Engineering Focus

- Maintainable frontend architecture
- Full-stack application development
- API and service integration
- Modernization of existing systems
- Automated testing and quality gates
- Containerized deployment and production operations
