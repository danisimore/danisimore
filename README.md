<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3c72,100:2a5298&height=180&section=header&text=Danil%20Vorobyev&fontSize=46&fontColor=ffffff&fontAlignY=35&desc=Full-Stack%20Engineer&descSize=18&descAlignY=56" width="100%" alt="Danil Vorobyev, Full-Stack Engineer" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=2A82DA&center=true&vCenter=true&width=620&lines=Backend+on+Python%2C+FastAPI+and+Odoo+17;Kafka+%E2%86%92+RabbitMQ+%E2%86%92+FastAPI+%E2%86%92+Odoo;Telegram+bots+with+AI+agents;Landing+pages+with+GSAP+animations;Scrapers%2C+integrations%2C+automation" alt="Typing SVG" /></a>

<p>
  <img src="https://img.shields.io/badge/ISP_RAS-Python_Developer-2a5298?style=flat-square" alt="ISP RAS, Python Developer" />
  <img src="https://img.shields.io/badge/Experience-3.5%2B_years-2a5298?style=flat-square" alt="Experience 3.5+ years" />
  <img src="https://img.shields.io/badge/Location-Kursk,_Russia-2a5298?style=flat-square" alt="Location Kursk, Russia" />
  <img src="https://img.shields.io/badge/Open_to-freelance-2ea44f?style=flat-square" alt="Open to freelance" />
</p>

<b>English</b> · <a href="https://github.com/danisimore/danisimore/blob/main/README.ru.md">Русский</a>

</div>

## 👋 About me

I'm a Python developer at [ISP RAS](https://www.ispras.ru/en/) since 2024. I build enterprise systems on **Odoo 17** and the Python services around them: message queues, background processing, integrations and data exports.

- 🔭 Now working on a clinical trial management system (CTMS) on Odoo 17
- ⚙️ I like reliable backends: idempotency, retries, queues and clean PostgreSQL
- 🤖 In my spare time I build Telegram bots with LLM agents and market data tools
- 🎨 I also make responsive layouts from Figma and landing pages with CSS and GSAP animations
- 💬 Ask me about Odoo internals, Celery, RabbitMQ and Kafka
- 📫 Open to freelance projects, contacts are at the bottom

## 🛠 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi,django,postgres,redis,rabbitmq,kafka,docker,linux,nginx,html,css,sass,js,bootstrap,figma,git,gitlab,bash,sqlite&perline=10" alt="Python, FastAPI, Django, PostgreSQL, Redis, RabbitMQ, Kafka, Docker, Linux, Nginx, HTML, CSS, Sass, JavaScript, Bootstrap, Figma, Git, GitLab, Bash, SQLite" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Odoo_17-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo 17" />
  <img src="https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white" alt="Celery" />
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/aiogram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="aiogram" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/GSAP-0AE448?style=for-the-badge&logo=gsap&logoColor=black" alt="GSAP" />
</p>

| Area | Tools |
|---|---|
| **Backend** | Python 3.11, FastAPI, Django REST Framework, Odoo 17 (ORM, OWL, QWeb), asyncio, aiohttp |
| **Frontend** | HTML, CSS, SCSS, JavaScript, Bootstrap, GSAP, responsive layout from Figma |
| **Queues and tasks** | Kafka, RabbitMQ, Celery, Redis |
| **Databases** | PostgreSQL, SQLAlchemy 2, Alembic, asyncpg, SQLite |
| **Bots and AI** | aiogram, LLM tool calling (DeepSeek, GigaChat), LangChain, faster-whisper |
| **Scraping and documents** | Playwright, BeautifulSoup, httpx, Google Sheets API, XlsxWriter, python-docx |
| **Quality and infra** | pytest, mypy, ruff, pre-commit, Docker Compose, GitLab CI, Nginx |

## 💼 What I've built at work

> The commercial code is private, so here is the short version.

- **Reliable document delivery.** Designed and built three Python microservices from scratch: Kafka → Transactional Outbox (PostgreSQL) → RabbitMQ → Inbox (FastAPI) → Odoo. At-least-once delivery, idempotent consumers, deduplication, exponential backoff with jitter, DLQ, health checks and watchdogs.
- **Text processing outside the monolith.** Moved document normalization out of Odoo into an async service: HTML sanitizing, language and sentiment detection, keywords, field mapping for Telegram, Twitter, LinkedIn and other platforms.
- **Celery inside Odoo 17.** Set up the Celery app with RabbitMQ, Redis and Flower: priority queues, DLQ and retry policies for heavy operations.
- **Data collection forms.** Main developer of a forms module built on Odoo Survey: new question types, editable matrix tables, access rules, XLSX export and printing.
- **Reports with LLM.** Document feeds embedded into reports, text rewriting with GigaChat via LangChain, and my own HTML → DOCX converter.
- **Clinical trials (CTMS).** Editing of submitted eCRFs with a "before → after" history, automatic status rules, audit log for 21 models, Excel export of 110k answers in under 6 seconds.

## 🚀 Pet projects

| Project | What it does | Stack |
|---|---|---|
| 🎯 **[SkinEdge](https://github.com/danisimore/skinedge)** | Arbitrage scanner for CS2, Dota 2 and Rust item markets. Compares 7 marketplaces, checks real sales, counts fees exactly in `Decimal`, keeps a paper trading journal, sends Telegram alerts and has a local web app | Python 3.11, httpx, Pydantic, Typer, SQLite, pytest, mypy (strict) |
| 🤖 **[BaldAI](https://github.com/danisimore/baldAI)** | Telegram bot with an AI sales assistant: answers questions about products, searches the catalog and fills the cart through LLM tool calling, understands voice messages | aiogram, FastAPI, DeepSeek API, faster-whisper, PostgreSQL, Docker |
| 🏋️ **[PharaonGym Agent](https://github.com/danisimore/pharaongym_agent)** | AI consultant bot for a fitness club, built on the same agent core | aiogram, FastAPI, LLM tool calling, PostgreSQL, Docker |
| 📡 **[Client Radar](https://github.com/danisimore/client_radar)** | Collects company data from rusprofile.ru and writes it to Google Sheets | Playwright, BeautifulSoup, gspread |
| 🍽️ **[MenuApp](https://github.com/danisimore/menuApp)** | Async REST API for restaurant menus with Redis cache, Celery sync from Google Sheets, pytest suite and OpenAPI docs | FastAPI, SQLAlchemy 2, PostgreSQL, Redis, Celery, RabbitMQ, Docker |

## 📫 Contacts

<div align="center">

<a href="https://t.me/YOUR_TELEGRAM"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
<a href="mailto:YOUR_EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://kwork.ru/user/YOUR_KWORK_LOGIN"><img src="https://img.shields.io/badge/Kwork-hire_me-FF6F00?style=for-the-badge" alt="Kwork" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e3c72,100:2a5298&height=100&section=footer" width="100%" alt="" />

</div>
