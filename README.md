<div align="center">
  <h1>👋 Hey, I'm Vivek Anand! 🚀</h1>
  <img src="./gif-hello.gif" alt="Vivek Anand" width="1500" style="border-radius: 50%;" />

  <p style="font-size: 1.2em; color: #E0E0E0;">
    Full Stack Developer building production AI-powered systems — RAG pipelines, LLM integrations, and scalable web apps. I care about what happens after the demo: real retrieval pipelines, real guardrails, real deployments. 💻
  </p>
</div>

---

## 👨‍💻 About Me

Full Stack Developer building and deploying production web applications and AI-powered systems with TypeScript, React, Next.js, Node.js, PostgreSQL, and MongoDB. Hands-on experience with REST APIs, authentication, RAG pipelines, hybrid and vector search, LLM integration, and tool calling, from backend and frontend through deployment and client handover.

---

## 💼 Recent Work

### Trainee Software Developer — Prime NRI Property Management (May 2026 – Sep 2026)

Owned backend architecture across client and admin domains for a production AI platform built by a 3-developer team, using Next.js, TypeScript, and PostgreSQL/pgvector on Neon.

- Architected the RAG retrieval pipeline — hybrid vector/keyword search and embedding-based reranking — backed by a 3-layer LLM guardrail system spanning prompt-injection defense, jailbreak detection, and hallucination checks
- Built admin control-plane APIs for lead management, knowledge-base curation, and authentication rate-limiting
- Identified and patched an unauthenticated PII-enumeration vulnerability; hardened rate-limiting and session-token handling against auth-bypass vectors

### Freelance Full Stack Developer — Ernest Wells Ltd, UK (Remote) (Jun 2026)

Independently built and deployed a UK accountancy firm's lead-generation site on Astro 6 (hybrid SSR/static, Vercel), TypeScript, and Tailwind CSS 4, with 20+ reusable components and 9 statically generated service pages from dynamic routes.

- Modeled all content as 18 Zod-validated Astro Content Collections integrated with CloudCannon CMS, letting non-technical staff manage copy, pricing, FAQs, and testimonials independently
- Built a serverless contact API — honeypot filtering, server-side validation, HTML-escaped output — persisting leads to Google Sheets with Resend notifications, backed by an Alpine.js interactive form
- Shipped core conversion tools — a 4-step service-recommendation quiz, tax estimator, and pre-filled WhatsApp handoffs — alongside technical SEO via JSON-LD and Open Graph
- Managed Vercel deployment, custom domain configuration, launch, and full client handover

### LEO — Local-First AI Personal Assistant (Jul 2026 – Present)

Directed the AI-assisted build of LEO (via Claude Code) as a personal testbed for evaluating AI models — a modular, hexagonal-style architecture across a 4-package monorepo, built with Electron, TypeScript, Node.js, and Ollama.

- Circuit-breaker-protected LLM/voice fallback chain
- Bounded tool-calling agent loop with local markdown RAG
- Real-time voice pipeline (Whisper STT, dual TTS, barge-in handling), with MCP integration on the roadmap

---

## 💼 Projects

### Project 1: [Crownify 🧢](https://github.com/CodeWith-vivek/Crownify)

**Crownify** is an industry-level e-commerce platform for branded caps and hats. Migrated from a legacy EJS/MVC monolith to a React SPA with SSR on public storefront routes, delivered in phases with zero downtime; re-platformed hosting from AWS EC2/Nginx to Render alongside the rewrite.

**Technologies Used**:
- **React, Node.js, Express.js**: SPA frontend with SSR storefront routes and server-side logic.
- **MongoDB**: For efficient data storage and management.
- **Razorpay**: Checkout with server-side signature verification.
- **Jest, Vitest, Playwright**: 3-tier test strategy automated via GitHub Actions CI.

**Key Features**:
- 🛒 React SPA storefront with SSR on public routes, migrated with zero downtime.
- 🏗️ Refactored 1,000+ line controllers into a layered Routes → Controllers → Services → Models architecture across 15+ domain modules, with centralized error handling.
- 💳 Razorpay checkout backed by a transaction-safe wallet ledger and coupon rollback engine.
- 🔐 Production security controls — double-submit CSRF protection, Helmet headers, rate-limited auth endpoints, and MongoDB-backed session management.
- ✅ 3-tier test strategy — Jest integration, Vitest component, and Playwright E2E tests — automated via GitHub Actions CI.

**My Role**: As the lead developer, I led the monolith-to-SPA migration, the controller refactor, the payment/wallet system, security hardening, and the CI test pipeline.

This project showcases my expertise in large-scale migrations, secure payment systems, and production-grade testing.

---

## 🛠️ Mini Projects

- ⚛️ **MERN Stack Projects**:
- **[Crownify](https://github.com/CodeWith-vivek/crownify2024)**: An industry-level e-commerce platform for branded caps, built with EJS, Node.js, Express.js, MongoDB, Razorpay, and OAuth.
  - **[React-Redux User Management System](https://github.com/CodeWith-vivek/react-userMangement)**: A full-stack MERN application with a React-Redux frontend for efficient state management, paired with a Node.js, Express.js, and MongoDB backend for user data handling.
  - **[Student Management System](https://github.com/CodeWith-vivek/typescript-studentManagement)**: A TypeScript-powered  project for managing student records, featuring a responsive EJS frontend and a robust backend.

- 🌐 **React Frontend Projects**:
  - **[Netflix Clone](https://github.com/CodeWith-vivek/React-netflix-clone)**: A dynamic Netflix-inspired interface built with React, leveraging an external API for movie data.
  - **[OLX Clone](https://github.com/CodeWith-vivek/react-olx-clone)**: A React-based marketplace clone with Firebase integration for real-time data handling.
  - **[To-Do List App](https://github.com/CodeWith-vivek/React-todo)**: A sleek task management app developed with React, featuring intuitive task creation and tracking.

---

## 🛠️ My Tech Stack  

```yaml
Languages: TypeScript, JavaScript (ES6+), SQL, HTML5, CSS3, C, Java  
Frontend: React.js, Next.js, Redux, Astro, Tailwind CSS, Alpine.js, Vite, Bootstrap  
Backend: Node.js, Express.js, RESTful APIs, JWT Auth, RBAC, Drizzle ORM, Zod  
Databases: PostgreSQL, pgvector, MongoDB, MySQL, Firebase  
AI/GenAI: RAG (Retrieval-Augmented Generation), Hybrid Search, Vector Search, Embeddings, LLM Integration,
          Prompt Engineering, AI Agents, Tool Calling, LLM Guardrails, Vercel AI SDK, Anthropic Claude,
          OpenAI Embeddings, Ollama, Claude Code  
Desktop: Electron  
Tools/Cloud: Git, GitHub, Docker, Postman, AWS (EC2), Nginx, Vercel, Netlify, Render, Cloudinary  
Concepts: Data Structures & Algorithms, OOP, SOLID Principles, MVC
```

## 🛠️ Languages & Tools

<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="50" height="50"/></a>
  <a href="https://www.cprogramming.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="50" height="50"/></a>
  <a href="https://www.typescriptlang.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="50" height="50"/></a>
  <a href="https://reactjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="React" width="50" height="50"/></a>
  <a href="https://nextjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original-wordmark.svg" alt="Next.js" width="50" height="50" style="filter: invert(1);"/></a>
  <a href="https://getbootstrap.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="Bootstrap" width="50" height="50"/></a>
  <a href="https://www.w3.org/Style/CSS/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" width="50" height="50"/></a>
  <a href="https://www.w3.org/html/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" width="50" height="50"/></a>
  <a href="https://redux.js.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redux/redux-original.svg" alt="Redux" width="50" height="50"/></a>
  <a href="https://astro.build/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/astro/astro-original.svg" alt="Astro" width="50" height="50"/></a>
  <a href="https://tailwindcss.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="Tailwind CSS" width="50" height="50"/></a>
  <a href="https://nodejs.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="Node.js" width="50" height="50"/></a>
  <a href="https://expressjs.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="Express.js" width="50" height="50"/></a>
  <a href="https://www.nginx.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="Nginx" width="50" height="50"/></a>
  <a href="https://www.mongodb.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="MongoDB" width="50" height="50"/></a>
  <a href="https://www.postgresql.org" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="PostgreSQL" width="50" height="50"/></a>
  <a href="https://www.mysql.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" width="50" height="50"/></a>
  <a href="https://www.docker.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="50" height="50"/></a>
  <a href="https://vercel.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vercel/vercel-original.svg" alt="Vercel" width="50" height="50" style="filter: invert(1);"/></a>
  <a href="https://aws.amazon.com" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="AWS" width="50" height="50"/></a>
  <a href="https://firebase.google.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="Firebase" width="50" height="50"/></a>
  <a href="https://www.figma.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="Figma" width="50" height="50"/></a>
  <a href="https://www.getpostman.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="Postman" width="50" height="50"/></a>
  <a href="https://git-scm.com/" target="_blank"><img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="Git" width="50" height="50"/></a>
  <a href="https://ollama.com/" target="_blank"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v13/icons/ollama.svg" alt="Ollama" width="50" height="50" style="filter: invert(1);"/></a>
  <a href="https://www.electronjs.org/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg" alt="Electron" width="50" height="50"/></a>
</p>

---


<div align="center" style="display: flex; flex-direction: column; justify-content: center; align-items: center; background-color: #0D1117; padding: 0 20px 20px 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
  <h1>ɢɪᴛʜᴜʙ ꜱᴛᴀᴛꜱ</h1>
  <div style="display: flex; justify-content: center; align-items: center; margin-bottom: 20px;">
    <a href="https://github.com/CodeWith-vivek"><img src="https://github-readme-stats-chi-orpin.vercel.app/api?username=CodeWith-vivek&rank_icon=github&hide_border=true&theme=transparent&text_color=ffffff" alt="Vivek's GitHub Stats" width="355" height="175" style="margin-right: 10px;" /></a>
    <a href="https://github.com/CodeWith-vivek"><img src="https://github-readme-streak-stats.herokuapp.com/?user=CodeWith-vivek&stroke=ffffff&background=0000&ring=ffffff&fire=ffffff&currStreakNum=ffffff&currStreakLabel=ffffff&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true" alt="Vivek's Streak" width="465" height="175" /></a>
  </div>
  <a href="https://github.com/CodeWith-vivek"><img src="https://github-readme-stats-chi-orpin.vercel.app/api/top-langs?username=CodeWith-vivek&show_icons=true&locale=en&layout=compact&theme=transparent&text_color=ffffff&hide_border=true" alt="Top Languages" width="355" height="175" style="margin-bottom: 20px;" /></a>
  <a href="https://github.com/CodeWith-vivek"><img src="https://activity-graph.vercel.app/graph?username=CodeWith-vivek&bg_color=0000&color=ffffff&line=ffffff&point=ffffff&area=true&hide_border=true" width="850" height="300" alt="Contribution Constellation"/></a>
  <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy-eight.vercel.app/?username=CodeWith-vivek&theme=transparent&no-bg=true&no-frame=true&title_color=ffffff&text_color=ffffff" alt="Trophies" style="margin-top: 20px;" /></a>
</div>

---

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CodeWith-vivek/CodeWith-vivek/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CodeWith-vivek/CodeWith-vivek/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/CodeWith-vivek/CodeWith-vivek/output/github-snake.svg" />
</picture>



- 📫 How to reach me **vivekanandthanuja97@gmail.com**

## 📬 Connect with Me

<p align="center">
  <a href="https://www.linkedin.com/in/vivek-anand-453bba17a" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" height="30" width="40" /></a>
  <a href="https://www.instagram.com/__v_i_v_e_k_._a_n_a_n_d" target="_blank"><img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram"  height="30" width="40"/></a>
</p>

<div align="center">
  <p>💡 <em>Let's build something extraordinary together!</em></p>
</div>