# Zcorw

Frontend-focused software engineer building full-stack web applications, developer tools, and automation systems.

Primary areas include frontend architecture, API integration, system redesign, containerized deployment, and production-oriented engineering.

## Selected Projects

### FlowLedger

A personal finance and asset-management project developed across two architectural generations.

The first generation uses separate frontend and backend repositories. The backend provides both the Web API and Telegram Bot services.

The second generation redesigns the product around monthly asset snapshots, multi-currency valuation, liabilities, historical exchange rates, data import and export, automated testing, deployment, and backup workflows.

- [`PasswdMan2`](https://github.com/Zcorw/PasswdMan2) — second-generation full-stack redesign in progress
- [`PasswdMan-ui`](https://github.com/Zcorw/PasswdMan-ui) — first-generation Vue frontend
- [`PasswdMan-server`](https://github.com/Zcorw/PasswdMan-server) — first-generation NestJS backend

**Stack:** Vue, React, TypeScript, NestJS, FastAPI, PostgreSQL, Docker

---

### FE Study System

A multi-repository study platform for Japan’s Fundamental Information Technology Engineer Examination.

The system separates the web quiz application, shared question bank, daily study automation, Telegram integration, and deployment responsibilities into independent components.

- [`fe-study-system`](https://github.com/Zcorw/fe-study-system) — system overview and integration
- [`fe-quiz-app`](https://github.com/Zcorw/fe-quiz-app) — web-based quiz application
- [`fe-question-bank-service`](https://github.com/Zcorw/fe-question-bank-service) — shared question bank service
- [`fe-daily-runner`](https://github.com/Zcorw/fe-daily-runner) — daily study content automation

**Stack:** Next.js, React, TypeScript, FastAPI, SQLite, Telegram, Docker

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
