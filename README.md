# 👩‍💻 Areeba Sadiq 

Welcome to my **Portfolio**.

This portfolio brings together five projects demonstrating hands-on experience across **full-stack web development, AI-powered applications, automation, robotics, technical documentation, and e-commerce**.

My projects focus on building practical systems using modern technologies, structured Git/GitHub workflows, responsive interfaces, APIs, authentication, testing, AI integration, and reusable software architecture.

---

## 🚀 Featured Projects

| Project                                                                                              | Focus                             | Main Technologies                    |
| ---------------------------------------------------------------------------------------------------- | --------------------------------- | ------------------------------------ |
| 🧠 [Bronze Tier](https://github.com/AreebaSadiq23/Bronze_Tier)                                       | Personal AI Employee & Automation | Python, Obsidian, AI CLI             |
| ✅ [Todo Application](https://github.com/AreebaSadiq23/Todo-application)                              | Full-Stack Task Management        | Next.js, React, FastAPI, PostgreSQL  |
| 🏗️ [RIBUILD Web](https://github.com/AreebaSadiq23/RIBUILD_Web)                                      | Construction & Architecture       | Next.js, React, TypeScript           |
| 🤖 [Physical AI & Humanoid Robotics](https://github.com/AreebaSadiq23/Physical-AI-Humanoid-Robotics) | Robotics + AI / RAG               | Docusaurus, React, FastAPI, Python   |
| 🖤 [Abaya](https://github.com/AreebaSadiq23/Abaya)                                                   | E-Commerce Platform               | Next.js, React 19, TypeScript, Clerk |

---

# 📊 Portfolio Overview

| Metric                 |                                                 Value |
| ---------------------- | ----------------------------------------------------: |
| 📁 Repositories        |                                                 **5** |
| 🔀 Total Pull Requests |                                               **128** |
| 💻 Primary Areas       | Web, Full-Stack, AI, Automation, Robotics, E-Commerce |
| 🔧 Version Control     |                                          Git & GitHub |
| 🧪 Testing             |                                pytest, Vitest, ESLint |
| 🚀 Deployment / DevOps |                        Vercel, Docker, GitHub Actions |

---

# 🧠 1. Bronze Tier — Personal AI Employee

[🔗 View Repository](https://github.com/AreebaSadiq23/Bronze_Tier)

## Overview

Bronze Tier is a **local-first Personal AI Employee automation system** built with Python.

The system monitors an Obsidian vault, detects incoming tasks, processes them through an AI orchestrator, and manages task movement through a structured filesystem workflow.

### Architecture

```text
Obsidian Vault
      │
      ▼
   Inbox/
      │
      ▼
Filesystem Watcher
      │
      ▼
Needs_Action/
      │
      ▼
AI Orchestrator
      │
      ▼
AI Processing
      │
      ▼
Done/
      │
      ▼
Logs/
```

### Key Features

* Local-first AI automation
* Obsidian-based task management
* Filesystem monitoring
* Inbox → Needs_Action → Done workflow
* AI CLI integration
* Task orchestration
* Environment-based configuration
* `DRY_RUN` mode
* Structured logging
* Custom exceptions
* Type hints and documentation
* Automated pytest testing
* flake8 linting
* Docker support
* GitHub Actions CI

### Technologies

* Python
* Obsidian
* Filesystem Watcher
* AI CLI
* pytest
* flake8
* Docker
* GitHub Actions
* Git/GitHub

### Repository Statistics

| Metric        |       Value |
| ------------- | ----------: |
| Pull Requests |       **8** |
| Merged PRs    |       **7** |
| Commits       |      **23** |
| Approx. LOC   | **~10,000** |
| Source Files  |     **30+** |

---

# ✅ 2. Todo Application

[🔗 View Repository](https://github.com/AreebaSadiq23/Todo-application)

## Overview

Todo Application is a **full-stack task management platform** built with Next.js, TypeScript, FastAPI, and PostgreSQL.

It combines a premium minimalist frontend with a structured REST API, authentication, task organization, and dashboard functionality.

### Architecture

```text
User
 │
 ▼
Next.js / React
 │
 ▼
FastAPI REST API
 │
 ▼
Service Logic
 │
 ▼
SQLModel / SQLAlchemy
 │
 ▼
PostgreSQL
```

### Key Features

#### Task Management

* Create tasks
* Update tasks
* Delete tasks
* Task categories
* Task priorities
* Due dates
* Overdue indicators
* Sorting
* Search
* Filtering

#### User Features

* User registration
* Login
* JWT authentication
* Profile management
* Notification preferences
* Dashboard
* My Day functionality

#### UI / UX

* Responsive design
* Premium minimalist interface
* Loading states
* Error states
* Empty states
* Framer Motion animations

### Technologies

**Frontend**

* Next.js
* React
* TypeScript
* Framer Motion
* Axios
* CSS Modules

**Backend**

* Python
* FastAPI
* SQLModel
* SQLAlchemy
* PyJWT

**Database / Deployment**

* PostgreSQL
* Docker
* Vercel

### Repository Statistics

| Metric              |     Value |
| ------------------- | --------: |
| Pull Requests       |    **31** |
| Merged PRs          |    **31** |
| Closed Unmerged PRs |     **0** |
| Open PRs            |     **0** |
| Commits             |   **139** |
| Approx. LOC         | **4,629** |
| Source Files        |   **~50** |

---

# 🏗️ 3. RIBUILD Web

[🔗 View Repository](https://github.com/AreebaSadiq23/RIBUILD_Web)

## Overview

RIBUILD Web is a **construction and architectural services web application** built with Next.js and React.

The project focuses on responsive UI, project galleries, service presentation, interactive sections, reusable components, and frontend developer tooling.

### Architecture

```text
User
 │
 ▼
Next.js Frontend
 │
 ├── Pages / Routes
 │
 ├── Components
 │
 ├── Layouts
 │
 └── UI Sections
```

### Key Features

* Construction-focused responsive UI
* Project galleries
* Service listings
* Interactive homepage
* Call-to-action sections
* Project pages
* Blog pages
* Responsive navigation
* Responsive footer
* Mission section
* Reusable `Container` component
* Reusable UI components
* Optimized remote image handling
* Lucide React icons

### Developer Tooling

* Prettier
* Husky
* Pre-commit hooks
* Git/GitHub workflow
* Structured conventional commits

### Technologies

* Next.js
* React
* TypeScript
* JavaScript
* CSS
* Lucide React
* Prettier
* Husky

### Repository Statistics

| Metric              |     Value |
| ------------------- | --------: |
| Pull Requests       |    **31** |
| Merged PRs          |    **31** |
| Closed Unmerged PRs |     **0** |
| Open PRs            |     **0** |
| Commits             |    **84** |
| Approx. LOC         | **6,543** |
| Source Files        |    **66** |

---

# 🤖 4. Physical AI & Humanoid Robotics

[🔗 View Repository](https://github.com/AreebaSadiq23/Physical-AI-Humanoid-Robotics)

## Overview

Physical AI & Humanoid Robotics is a **technical learning platform combining robotics documentation with an AI-powered Retrieval-Augmented Generation (RAG) chatbot**.

The project combines Docusaurus documentation, React components, authentication interfaces, and a Python/FastAPI backend.

### Architecture

```text
User
 │
 ▼
Docusaurus / React
 │
 ▼
FastAPI Backend
 │
 ▼
RAG Chatbot
 │
 ▼
Robotics Knowledge
 │
 ▼
AI Response
```

### Key Features

#### Robotics Learning

* Structured robotics curriculum
* Technical documentation
* Docusaurus-based learning platform
* Markdown / MDX content

#### AI / RAG

* Interactive RAG chatbot
* Robotics knowledge retrieval
* API validation
* Backend configuration
* Health testing
* Error handling

#### User Interface

* ChatWidget
* CyberCard
* RoboticHero
* Profile page
* Login page
* Signup page
* Responsive navigation
* Error boundaries
* Fallback handling

### Technologies

**Frontend / Documentation**

* React
* TypeScript
* Docusaurus
* Vite
* CSS

**Backend / AI**

* Python
* FastAPI
* Pydantic
* RAG architecture

**Testing / Tooling**

* Vitest
* Pytest
* ESLint
* Prettier
* GitHub Actions

### Repository Statistics

| Metric              |      Value |
| ------------------- | ---------: |
| Pull Requests       |     **39** |
| Merged PRs          |     **39** |
| Closed Unmerged PRs |      **0** |
| Open PRs            |      **0** |
| Commits             |     **90** |
| Approx. LOC         | **~4,000** |
| Source Files        |    **~40** |

---

# 🖤 5. Abaya — E-Commerce Platform

[🔗 View Repository](https://github.com/AreebaSadiq23/Abaya)

## Overview

Abaya is a **modern responsive e-commerce application dedicated to Abayas**, designed around a luxury editorial shopping experience.

The application provides product discovery, product details, cart management, wishlist functionality, authentication, and responsive shopping interfaces.

### Architecture

```text
User
 │
 ▼
Next.js / React
 │
 ├── UI Components
 │     └── Shadcn UI + Tailwind
 │
 ├── Global State
 │     ├── CartContext
 │     └── WishlistContext
 │
 └── Authentication
       └── Clerk
```

### Key Features

#### Shopping

* Abaya product browsing
* Product detail pages
* Shopping cart
* Cart drawer
* Cart quantity management
* Wishlist
* Product collections

#### Authentication

* User sign-in
* User sign-up
* Profile management
* Clerk authentication
* Authentication migration to Clerk

#### Responsive Experience

* Mobile-first design
* Tablet layouts
* Desktop layouts
* Responsive product grids
* Responsive navigation

### State Management

The application uses React Context API for global state.

**CartContext**

* Cart state
* Product quantities
* Add / remove products
* Cart management

**WishlistContext**

* Wishlist state
* Add / remove products
* Wishlist controls

### Technologies

* Next.js App Router
* React 19
* TypeScript
* Tailwind CSS
* Shadcn UI
* Clerk
* Embla Carousel
* React Context API
* ESLint
* Vercel

### Repository Statistics

| Metric              |      Value |
| ------------------- | ---------: |
| Pull Requests       |     **16** |
| Merged PRs          |     **16** |
| Closed Unmerged PRs |      **0** |
| Open PRs            |      **0** |
| Commits             |     **30** |
| Approx. LOC         | **~3,500** |
| Source Files        |    **~60** |

---

# 🛠️ Technical Skills

## Frontend Development

* React
* Next.js
* TypeScript
* Docusaurus
* Responsive Web Design
* Component Architecture
* Tailwind CSS
* CSS / CSS Modules
* Framer Motion
* Shadcn UI
* Embla Carousel
* Lucide React

## Backend Development

* Python
* FastAPI
* REST API Development
* SQLModel
* SQLAlchemy
* PostgreSQL
* Pydantic
* JWT Authentication
* Environment Configuration

## AI & RAG

* Retrieval-Augmented Generation
* LLM Integration
* AI CLI Integration
* AI-powered automation
* Robotics knowledge retrieval
* Vector-based knowledge systems

## Authentication & State

* Clerk
* JWT
* React Context API
* Authentication workflows
* Global application state

## Testing & Code Quality

* pytest
* Vitest
* ESLint
* Prettier
* Husky
* GitHub Actions
* API Testing
* Error Handling

## DevOps & Tools

* Git
* GitHub
* Pull Requests
* Feature Branches
* Docker
* Vercel
* CI/CD
* Environment Variables

---

# 🔄 Development Workflow

Across these projects, I use a structured Git/GitHub development workflow:

```text
Requirement
    ↓
Planning
    ↓
Implementation
    ↓
Testing / Validation
    ↓
Git Commit
    ↓
Feature Branch
    ↓
Pull Request
    ↓
Review / Iteration
    ↓
Merge
```

This workflow allows features, fixes, refactoring, testing improvements, and documentation changes to be developed independently and tracked through GitHub.

---

# 📊 Portfolio at a Glance

| Area                | Technologies / Experience             |
| ------------------- | ------------------------------------- |
| 🌐 Web Development  | React, Next.js, TypeScript            |
| 🔙 Backend          | Python, FastAPI                       |
| 🗄️ Databases       | PostgreSQL                            |
| 🤖 AI               | RAG, LLM Integration, AI Automation   |
| 🦾 Robotics         | Humanoid Robotics Documentation       |
| 🛒 E-Commerce       | Cart, Wishlist, Product Experiences   |
| 🔐 Authentication   | Clerk, JWT                            |
| 🧠 State Management | React Context API                     |
| 🧪 Testing          | pytest, Vitest                        |
| 🎨 UI/UX            | Tailwind, Shadcn, Framer Motion       |
| 📚 Documentation    | Docusaurus, MDX                       |
| ⚙️ Automation       | Filesystem Watchers, AI Orchestration |
| 🐳 DevOps           | Docker, GitHub Actions                |
| 🚀 Deployment       | Vercel                                |
| 🔀 Collaboration    | Git, GitHub, Pull Requests            |
| 📈 Total PRs        | **128**                               |

---

# 🌐 Repository Links

### 🧠 Bronze Tier

https://github.com/AreebaSadiq23/Bronze_Tier

### ✅ Todo Application

https://github.com/AreebaSadiq23/Todo-application

### 🏗️ RIBUILD Web

https://github.com/AreebaSadiq23/RIBUILD_Web

### 🤖 Physical AI & Humanoid Robotics

https://github.com/AreebaSadiq23/Physical-AI-Humanoid-Robotics

### 🖤 Abaya

https://github.com/AreebaSadiq23/Abaya

---

# 🎯 Focus Areas

My current development portfolio covers:

* Full-stack web development
* Modern frontend engineering
* AI-powered applications
* Retrieval-Augmented Generation
* Personal AI automation
* Humanoid robotics education
* E-commerce
* Authentication systems
* State management
* Responsive UI/UX
* REST APIs
* Technical documentation
* Automated testing
* CI/CD workflows
* GitHub-based development

---

# 📌 Summary

These five projects demonstrate hands-on experience across multiple areas of modern software engineering.

From **AI automation and RAG systems** to **full-stack applications, robotics documentation, construction web development, and e-commerce**, the portfolio reflects experience with designing, implementing, testing, documenting, and iterating on software projects.

With **5 repositories and 128 Pull Requests**, this portfolio represents a practical development journey using modern technologies and Git/GitHub-based engineering workflows.

---

## 👩‍💻 Author

# Areeba Sadiq

Software Engineering Portfolio

**GitHub:** [@AreebaSadiq23](https://github.com/AreebaSadiq23)

---

⭐ **Explore the repositories above to see the code, development history, features, and implementation details of each project.**
