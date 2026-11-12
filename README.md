# Hua Chen

### Senior Full-Stack Software Engineer | React & Next.js | Node.js & Python/Django | AI Engineering

I’m a software engineer based in Ontario, Canada, with **17+ years of professional software development experience** building and maintaining production applications. I work across frontend architecture, Node.js and Python backend APIs, database integration, automated testing, and delivery pipelines. More recently, I’ve been building practical **AI-powered applications** using LangGraph, OpenAI APIs, retrieval-augmented generation (RAG), and vector search.

**Open to opportunities:** Senior Software Engineer · Full-Stack Developer · AI Application Engineer

[United Supermarket live website](https://adelaide.unitedsupermarketlondon.ca/) · [Appointment Booking live demo](https://appointment.founderdesign.com/) · [QR Code Creator live demo](https://qrcode.founderdesigngroup.ca/) · [GitHub repositories](https://github.com/huachenlihx?tab=repositories) · [npm packages](https://www.npmjs.com/~huachenlihx)

## What I bring

- **Production full-stack engineering:** React, Next.js, TypeScript, Node.js, Python, Django, Django REST Framework, REST APIs, and WebSockets. My earlier Node.js backend work at United Supermarket included user authentication and product-management services.
- **Enterprise software delivery:** Developed and maintained production applications at **NCR / Candescent (2021–2026)**, including reusable React components shared across multiple applications and development teams, and real-time UI updates powered by WebSockets.
- **AI application development:** Designed document ingestion and chunking, embedding and vector retrieval pipelines, LangGraph orchestration, grounded LLM responses, and AI-assisted training features.
- **Quality and delivery:** Authored and maintained Jenkinsfiles and Jenkins CI jobs, investigated build failures, developed Playwright end-to-end tests, and worked with Git, Docker, code reviews, and WCAG guidance.
- **AI-assisted engineering workflows:** Use Claude Code, Cursor, and OpenAI Codex (configured in VS Code); developed and customized Cursor skills, rules, hooks, and automation for code reviews, task planning, performance analysis, and Git/Jira workflows.
- **Experience beyond the JavaScript ecosystem:** Professional Java development at Tekdesk, C#, AWS services, SQL databases, and backend systems.

## Technology stack

| Area | Technologies |
| --- | --- |
| **Frontend** | React, Next.js, React Native (Expo), TypeScript, JavaScript, Tailwind CSS, shadcn/ui |
| **Backend** | Node.js (REST APIs, authentication, product management), Python, Django, Django REST Framework, REST APIs, WebSockets, Java, C# |
| **AI / LLM** | LangGraph, LangChain, OpenAI APIs, RAG, embeddings, FAISS, PyTorch, multilingual MiniLM, Qwen |
| **AI coding agents** | Claude Code, Cursor, OpenAI Codex (VS Code), customized Cursor skills, rules, hooks, and workflows |
| **Databases** | PostgreSQL, MySQL, MariaDB, Microsoft SQL Server |
| **Cloud & DevOps** | AWS (EC2, S3, RDS, Lambda, Elastic Beanstalk), Docker, Jenkins (Jenkinsfiles, CI jobs, build troubleshooting), Git, CI/CD, cPanel |
| **Testing & Quality** | Playwright, Vitest, accessibility / WCAG, API testing |
| **Collaboration** | Jira, Agile development, code reviews, cross-team reusable components |

## Selected work

### Professional Node.js Backend Work — United Supermarket

**Node.js · REST APIs · User Authentication · Product Management**

- Developed Node.js backend services for user authentication and product management.
- Designed REST API endpoints and implemented server-side business logic supporting these functions.

*This describes my earlier professional role at United Supermarket (2018–2019), separately from the more recent Next.js/Django applications described below. The original project source is not publicly available.*

### United Supermarket — Business Applications & AI Integration

**Next.js · Django REST Framework · Python · React Native · SQL · LangGraph · OpenAI APIs · RAG · FAISS**

Built multilingual business-facing web and administrative applications with workflow automation, an AI-powered customer chat assistant, and AI-assisted employee training.

- Developed customer-facing interfaces and Django-backed content and administrative workflows.
- Implemented operational reporting, PDF document generation, and CSV/XLSX exports.
- Built scheduled training reminders and other business-process automation features.
- Built a **LangGraph-based RAG chat assistant** that ingests business knowledge from PDF, Markdown, and text documents, uses OpenAI embeddings and FAISS semantic retrieval, and generates document-grounded answers.
- Added **AI-assisted training-question generation** in English and Chinese using OpenAI APIs, including caching and regeneration when training content changes.
- Independently resolved cross-subdomain authentication and CSRF issues across Next.js and Django services.

**[Live website](https://adelaide.unitedsupermarketlondon.ca/)**

*Application source code is not publicly shared.*

### United Supermarket Adelaide — React Native Mobile App

**React Native · Expo · TypeScript · Django REST APIs · Firebase Cloud Messaging**

Developed a mobile application for United Supermarket Adelaide, connecting shoppers to store information and weekly promotions while integrating with the existing Django backend.

- Built weekly flyer browsing with image previews and zoom interactions, alongside store information and contact screens.
- Implemented mobile push notifications using Firebase Cloud Messaging and Expo, with in-app announcements and navigation to relevant content.
- Added application version checks and support for portrait and landscape layouts.
- Integrated the mobile experience with Django REST APIs used by the broader United Supermarket platform.

*Private repository; mobile application not publicly released.*

### QR Code Creator — Full-Stack Web Application

**Next.js · React · TypeScript · Python · Django REST Framework · Stripe**

A production-oriented QR code generator with customizable designs, logo overlays, downloadable PNG/SVG/PDF assets and ZIP bundles, responsive UI, API integration, and Stripe donation checkout.

- Designed frontend and backend capabilities for QR asset creation and delivery.
- Implemented form protection, API integrations, and payment webhook handling.
- Worked on PostgreSQL integration and deployment workflows for the Django backend.

**[Live demo](https://qrcode.founderdesigngroup.ca/)** · **[Frontend source](https://github.com/huachenlihx/qr-code-creator-frontend)**

### Appointment Booking Platform — Full-Stack Web Application

**Next.js 16 · React 19 · TypeScript · Tailwind CSS · Python · Django REST Framework · PostgreSQL · MySQL / MariaDB · Docker · AWS · Vitest**

Designed, developed, and deployed a full-stack appointment scheduling platform with separate customer-facing and backend applications, secure session authentication, role-based permissions, and automated appointment notifications. The production application runs across two HTTPS subdomains under `founderdesign.com`.

**Frontend — `appointment_web` (private repository)**

- Built a responsive five-step booking flow covering contact information, service selection, date, time, and confirmation, with sign-in required before proceeding and validated contact details.
- Implemented customer account management, appointment history, cancellation and rescheduling workflows, and accessible help dialogs.
- Added TypeScript checks and Vitest tests; deployed a Next.js static export to cPanel.

**Backend — `appointment_api` (private repository)**

- Developed Django REST APIs for appointment availability, capacity-controlled bookings, staff assignments, cancellations, and rescheduling.
- Implemented Django session authentication, CSRF protection, role-based permissions, and customer/staff email notifications with calendar invitations.
- Built scheduled appointment reminders with independent customer/staff send tracking, selective retries after email failures, and concurrency protection for scheduled runs.
- Configured PostgreSQL and MySQL/MariaDB compatibility, database migrations, Docker-based development and deployment environments, and production deployment on cPanel.

**Cloud & Deployment**

- Containerized the application stack using Docker Compose with Django, PostgreSQL, Next.js, Nginx, and Mailpit.
- Worked with AWS S3 APIs for static frontend asset storage and website-hosting experiments, alongside Lambda API testing.
- Configured environment-specific deployment workflows, HTTPS, cross-origin authentication, and CSRF protection.

**[Live appointment website](https://appointment.founderdesign.com/)** · **[Live API](https://api-appointment.founderdesign.com/)**

*Both GitHub repositories (`appointment_web` and `appointment_api`) are private; source code is not publicly accessible.*

### AI Engineering — RAG, Agents & Multilingual Document Q&A

**LangGraph · LangChain · OpenAI APIs · FAISS · PyTorch · MiniLM · Qwen**

I design and develop practical AI capabilities that connect language models to application workflows and source documents, including:

- **Production-integrated RAG (United Supermarket):** Personally designed and implemented a RAG pipeline using document loading and chunking, OpenAI embeddings, FAISS semantic retrieval, and LangGraph orchestration, integrated with a Django REST Framework-powered AI chat assistant. Used GPT-4o mini for document-grounded responses and fallback behavior when relevant information is unavailable.
- **AI-assisted employee training (United Supermarket):** Integrated OpenAI-powered English/Chinese question suggestions into training workflows. This is *document-grounded content generation*, distinct from the FAISS-backed chat retrieval pipeline.
- **Local multilingual document Q&A (exploratory project):** Worked with multilingual MiniLM embeddings, PyTorch-based similarity retrieval, LangGraph, and a local Qwen model to explore private, document-based question answering. Evaluated grounding limitations when a model's answer did not reliably follow retrieved context.

*The United Supermarket implementation is part of the business application above; private application code and business content are not publicly shared.*

## AI Coding Agents & Developer Workflows

**Claude Code · Cursor · OpenAI Codex (VS Code) · Bash · PowerShell · Python · Git/Jira**

Alongside building AI-enabled applications, I use AI coding agents in day-to-day engineering and have developed and customized supporting development workflows:

- Configured OpenAI Codex in Visual Studio Code and worked with Claude Code and Cursor for development, debugging, and code review.
- Developed and customized Cursor skills and rules for React code review, performance optimization, and persistent planning across multi-step tasks.
- Worked with Bash/PowerShell hooks and Python scripts supporting agent workflows, browser automation, and Git/Jira branch synchronization.
- Use automated tests, code review, and CI validation to assess generated code rather than treating AI output as automatically correct.

*Some tools and supporting workflow components are third-party; the description above refers to my own configuration, development, and customization work.*

## Open-source React / TypeScript packages

I publish reusable tools for React and Next.js development. Selected packages:

| Package | Purpose |
| --- | --- |
| [pdfjs-embed-viewer](https://www.npmjs.com/package/pdfjs-embed-viewer) | PDF embedding and viewing in React / Next.js |
| [form_recaptcha](https://www.npmjs.com/package/form_recaptcha) | Reusable CAPTCHA component for web forms |
| [pagination-dropdown-select](https://www.npmjs.com/package/pagination-dropdown-select) | Dropdown selection with pagination |
| [complex-column-csv-exporter](https://www.npmjs.com/package/complex-column-csv-exporter) | CSV export for complex data structures |
| [json-column-csv-blob](https://www.npmjs.com/package/json-column-csv-blob) | CSV/Blob utilities for JSON-based data |
| [display-buffered-pdf](https://www.npmjs.com/package/display-buffered-pdf) | Displaying PDF buffer content |

**[View my npm profile](https://www.npmjs.com/~huachenlihx)**

## Engineering approach

I care about **maintainability, reusable architecture, accessible interfaces, reliable APIs, and production-ready delivery**. I enjoy taking ownership of features end to end—from problem analysis and implementation through debugging, testing, and deployment. My AI interests build on that foundation: integrating LLMs into software systems with practical use cases and clear operational boundaries.

## Connect

- **Email:** `huachenlihx@gmail.com`
- **GitHub:** [github.com/huachenlihx](https://github.com/huachenlihx)
- **npm:** [npmjs.com/~huachenlihx](https://www.npmjs.com/~huachenlihx)
- **Live business application:** [United Supermarket Adelaide](https://adelaide.unitedsupermarketlondon.ca/)
- **Appointment Booking:** [Live website](https://appointment.founderdesign.com/)
- **Demo:** [QR Code Creator](https://qrcode.founderdesigngroup.ca/)

I’m interested in opportunities where I can contribute to **senior full-stack engineering, frontend platform development, backend services, or AI-enabled products**.
