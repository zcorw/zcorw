# Zcorw

Frontend-focused software engineer working across web applications and Electron desktop clients.

My work centers on maintainable interfaces, reusable components, API integration, and system modernization. Personal projects extend this foundation into backend architecture, data modeling, and containerized deployment.

## Featured Work

### [PasswdMan](https://github.com/zcorw/PasswdMan2) — Application Design and Implementation

A personal credential vault for organizing passwords and secure notes, with search and import/export workflows for backup and migration.

The first generation brings together frontend implementation, REST APIs, database design, authentication, and application-layer encryption. The second generation is a redesign in progress, revisiting the interface, security model, and application architecture in a single repository.

| Generation | Architecture | Repositories |
| --- | --- | --- |
| v1 — original implementation | Vue 3 frontend, NestJS API, MySQL | [Frontend](https://github.com/zcorw/PasswdMan-ui) · [Backend](https://github.com/zcorw/PasswdMan-server) |
| v2 — redesign in progress | React, FastAPI, PWA; frontend and backend in one repository | [PasswdMan2](https://github.com/zcorw/PasswdMan2) |

**Engineering focus:** Authentication, sensitive-data handling, client–server integration, and architectural evolution.

**Technologies across generations:** Vue, React, TypeScript, NestJS, FastAPI, MySQL, PWA, Docker.

### [Web Engineering Journey](https://github.com/zcorw/web-engineering-journey) — Technical Progression

A documented progression from browser and network fundamentals to reusable frontend abstractions, NestJS architecture, and full-stack systems.

Source-level experiments and linked projects connect implementation examples with changes in design and engineering approach. Larger applications retain their own repositories and Git history; this repository explains the relationships and lessons across them.

**Progression:** Web fundamentals → reusable frontend engineering → backend architecture → full-stack systems.

[Frontend engineering](https://github.com/zcorw/web-engineering-journey/blob/main/docs/frontend-engineering.md) · [Backend architecture](https://github.com/zcorw/web-engineering-journey/blob/main/docs/backend-engineering.md) · [Technical timeline](https://github.com/zcorw/web-engineering-journey/blob/main/docs/timeline.md) · [Lessons learned](https://github.com/zcorw/web-engineering-journey/blob/main/docs/lessons-learned.md)

Earlier implementations are preserved as historical work, with their context and limitations documented rather than presented as current production recommendations.

## Additional Applications

### [FlowLedger](https://github.com/zcorw/flow-ledger-2)

A personal finance and asset-management application developed across two architectural generations. The second-generation redesign focuses on monthly asset snapshots, multi-currency valuation, liabilities, historical exchange rates, and data import/export and backup workflows.

**Distinctive focus:** Financial data modeling and valuation over time.

**Repositories:** [v2 full-stack redesign](https://github.com/zcorw/flow-ledger-2) · [v1 frontend](https://github.com/zcorw/FlowLedger-ui) · [v1 API and Telegram bot](https://github.com/zcorw/FlowLedger-server).

**Stack:** React, TypeScript, FastAPI, PostgreSQL, SQLAlchemy, ECharts, Docker.

### [FE Study System](https://github.com/zcorw/fe-study-system)

A multi-repository study platform for Japan’s Fundamental Information Technology Engineer Examination. The quiz application, shared question bank, daily study automation, and Telegram integration have separate responsibilities within the system.

**Distinctive focus:** Component boundaries, service integration, and study automation.

**Repositories:** [System overview](https://github.com/zcorw/fe-study-system) · [Quiz application](https://github.com/zcorw/fe-quiz-app) · [Question bank](https://github.com/zcorw/fe-question-bank-service) · [Daily runner](https://github.com/zcorw/fe-daily-runner).

**Stack:** Next.js, React, TypeScript, FastAPI, SQLite, Telegram, Docker, Nginx.

### [IPA Screenshot Exam Server](https://github.com/zcorw/ipa-siken)

An examination service that presents questions from extracted regions of archived IPA exam PDFs rather than relying on OCR-transcribed text. SQLite stores exam metadata and answer mappings; extraction tools and Git LFS support the source PDFs, screenshots, and data files.

**Distinctive focus:** Document-to-question workflows and image-based question presentation.

**Stack:** Node.js, SQLite, Python, HTML, CSS, Docker, Git LFS.

### [AlignSpeak](https://github.com/zcorw/AlignSpeak)

An AI-assisted reading and speaking practice application, combining a React interface, FastAPI backend, speech-processing workflows, and containerized deployment in a single repository.

**Distinctive focus:** Language-learning interfaces and speech-processing integration.

**Stack:** React, TypeScript, Vite, FastAPI, PostgreSQL, Docker.

## Focused Engineering Examples

### [Electron SQLCipher Demo](https://github.com/zcorw/electron-sqlcipher-demo)

A minimal Windows x64 Electron example demonstrating encrypted local storage and persistence across application restarts. Database access stays in the main process, while the renderer uses a limited interface exposed through preload and `contextBridge`.

**Scope:** A focused integration example, not a complete desktop client or production-grade key-management solution.

**Stack:** Electron, Node.js, JavaScript, SQLCipher.

[English documentation](https://github.com/zcorw/electron-sqlcipher-demo/blob/main/README-en.md)

## Core Technologies

Used across professional work, personal projects, and focused experiments; the project pages describe their specific scope.

| Area | Technologies |
| --- | --- |
| Frontend | JavaScript, TypeScript, React, Vue, Next.js, Vite, Webpack, Sass |
| Desktop | Electron |
| Backend | Node.js, NestJS, Express, Koa, Python, FastAPI, REST APIs |
| Data and deployment | PostgreSQL, MySQL, SQLite, Docker Compose, Nginx, Git, Git LFS |
| Code quality | TypeScript, ESLint, Prettier |

## Engineering Focus

- Maintainable frontend architecture and reusable abstractions.
- API integration and clear boundaries between interfaces, services, and data.
- Incremental modernization and architectural improvements to existing systems.
- Containerized development and deployment, supported by practical documentation.
