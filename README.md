# 🚀 AI Content Factory

An end-to-end AI content production and workflow automation platform built with **n8n, Docker, REST APIs, AI models, and Google Sheets**.

AI Content Factory is designed to orchestrate the creation, processing, storage, and publishing of digital content through modular automation workflows.

The system brings multiple AI-powered capabilities together under a centralized workflow architecture.

---

## 🎯 Project Overview

AI Content Factory is an automation platform designed to reduce the manual work involved in producing digital content.

Instead of managing image generation, video generation, content planning, prompt engineering, file processing, storage, and publishing independently, the platform coordinates these processes through **n8n workflows and API integrations**.

The project is built around a modular architecture so individual AI capabilities can be developed, tested, and extended independently.

---

## ✨ Key Features

- 🤖 AI agent orchestration
- 📝 AI content generation
- 🎨 AI image generation
- 🎬 AI video generation
- 🧠 AI prompt engineering
- ⚙️ n8n workflow automation
- 🔗 REST API integrations
- 📊 Google Sheets integration
- 🐳 Docker-based deployment
- 🐧 Ubuntu self-hosting
- 📁 Binary file processing
- 🔄 Multi-workflow architecture
- 🗂️ Prompt management
- 🛠️ Error handling and workflow debugging
- 📦 Generated media management

---

# 🏗️ System Architecture

The platform uses a centralized orchestration model where a master workflow coordinates specialized AI workflows.

```text
                              USER
                                │
                                ▼
                       MASTER ORCHESTRATOR
                                │
              ┌─────────────────┼─────────────────┐
              │                 │                 │
              ▼                 ▼                 ▼
         CONTENT AI         IMAGE AI          VIDEO AI
              │                 │                 │
              └─────────────────┼─────────────────┘
                                │
                                ▼
                       FILE PROCESSING
                                │
                                ▼
                     STORAGE / DATA LAYER
                                │
                         Google Sheets
                                │
                                ▼
                          PUBLISHING
```

---

# 🧰 Technology Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow orchestration and automation |
| Docker | Containerized deployment |
| Ubuntu Linux | Self-hosted infrastructure |
| REST APIs | External service and AI integrations |
| Git | Version Control |
| GitHub | Source control and project documentation |
| FAL AI | Image & Video Generation |
| Google Sheets | Content and workflow data management |

---

# 📁 Project Structure

```
AI-Content-Factory/
│
├── assets/
│   └── Project assets and supporting resources
│
├── configs/
│   └── Configuration files
│
├── database/
│   └── Local database and structured data
│
├── docs/
│   └── Project documentation and technical references
│
├── generated/
│   └── Generated content and media
│
├── logs/
│   └── Workflow and application logs
│
├── prompts/
│   └── Reusable AI prompts and prompt templates
│
├── screenshots/
│   └── Project and workflow screenshots
│
├── workflows/
│   └── Exported n8n workflows
│
├── .env.example
├── .gitignore
├── CHANGELOG.md
├── LICENSE
├── PROJECT_STANDARDS.md
├── README.md
└── ROADMAP.md
```

---

# ⚙️ Current Workflows

The repository currently contains workflows for:

- AI Content Planner
- AI Image Generator
- AI Video Generator
- AI Content Pipeline
- Google Sheets Integration
- Prompt Management
- Workflow Orchestration

---

# 📈 Current Development Status

✅ Docker Environment

✅ Self-hosted n8n environment

✅ AI Image Generation

✅ AI Video Generation

✅ Binary File Processing

✅ REST API integration

✅ Google Sheets integration

✅ Prompt management

✅ Modular workflow architecture

🔄 Automated video assembly

🔄 Automated publishing workflows

🔄 Automated publishing workflows

---

# 🧪 Engineering Challenges

- Docker container management
- Linux file permissions
- Binary data handling
- REST API integration
- AI workflow orchestration
- Large media processing
- Workflow error handling
- API debugging
- Multi-workflow coordination
- Structured content management
- Self-hosted automation infrastructure


---

# 🗺️ Roadmap

## Content & Media
- [ ] Automatic video merging with FFmpeg
- [ ] Voice generation
- [ ] Automated caption generation
- [ ] Advanced media processing

## Publishing
- [ ] TikTok publishing
- [ ] Instagram publishing
- [ ] YouTube publishing
- [ ] Additional social media integrations

## Analytics
- [ ] Content performance tracking
- [ ] Analytics dashboard
- [ ] Workflow execution analytics

## Platform
- [ ] Multi-user support
- [ ] Improved workflow monitoring
- [ ] Additional AI providers
- [ ] Expanded automation modules

---

# 📸 Screenshots

Project screenshots and workflow demonstrations are available in:

/screenshots

Additional architecture diagrams and technical documentation are available in:

/docs

---

# 📚 Documentation

Important documentation includes:

- PROJECT_STANDARDS.md
- ROADMAP.md
- CHANGELOG.md
- /docs
- /workflows

---

# 🛣️ Project Philosophy

AI Content Factory is being developed around three principles:

- Automation

Reduce repetitive manual work through reliable workflows.

- Modularity

Build specialized workflows that can be reused and extended.

- Scalability

Design the system so additional AI providers, content types, integrations, and publishing platforms can be added over time.

---

# 👨‍💻 Author

## Ogheneochuko Godswill

AI Automation Engineer

AI Workflow Engineer • Automation • APIs • Cloud • DevOps

GitHub:
https://github.com/godswillmamus54-max

LinkedIn:
https://www.linkedin.com/in/ogheneochuko-godswill

Email:
godswillmamus54@gmail.com

---

# License

MIT
