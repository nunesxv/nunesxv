# Hi 🫡, I'm Lucas Xavier

**Full Stack, Back-end & AI Automation Developer** | Software Engineering Student
Focused on architecting scalable web applications, robust REST APIs, AI agents, and high-performance databases using **Node.js**, **TypeScript**, **React**, **Next.js**, **Python**, **PostgreSQL**, **Supabase**, and **n8n**.

## 🌐 Connect & Where to find me

<p align="left">
  <a href="https://www.linkedin.com/in/lucas-xavier-3565b8313/">
    <img src="https://img.shields.io/badge/LinkedIn-Lucas_Xavier-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:eng.lucasxv@gmail.com">
    <img src="https://img.shields.io/badge/Email-eng.lucasxv@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/nunesxv">
    <img src="https://img.shields.io/badge/GitHub-nunesxv-181717?style=for-the-badge&logo=github" />
  </a>
  <a href="https://instagram.com/lucasnunex">
    <img src="https://img.shields.io/badge/Instagram-@lucasnunex-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
</p>

---

## 🧠 What I do

- 🤖 **AI Agents & Conversational Automation (n8n, Gemini API, Tool Calling)**
- 🏗️ Full-stack Web Apps (Next.js, React)
- 💳 Payment Gateway Integrations & Checkout
- 🔐 Backend, Auth & Database Modeling (Supabase, PostgreSQL, SQL)
- 🐍 Python Automation, Media Pipelines (FFmpeg, Neural TTS) & Scraping
- ⚡ Systems Architecture & Networking (Java)
- 📍 Geolocation & Logistics Features
- 📊 Data Management & Statistical Analysis
- 🧩 Business Logic & Economic Modeling

---

## 🛠️ Tech Stack

### AI & Automation
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)

### Frontend
![JavaScript](https://img.shields.io/badge/JavaScript-FFD43B?style=for-the-badge&logo=javascript&logoColor=000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs)
![Tailwind](https://img.shields.io/badge/TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git)
![Insomnia](https://img.shields.io/badge/Insomnia-5849BE?style=for-the-badge&logo=insomnia)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma)

---

## 🚀 Featured Engineering Projects / Projetos em Destaque

### 🤖 [Zykon AI Receptionist — 24/7 AI Agent & Media Automation Pipeline](https://github.com/nunesxv/zykon_ai_receptionist_showcase)
Agente conversacional orientado a ferramentas (*Tool Calling*) para clínicas e negócios locais, hospedado em infraestrutura própria (**Orange Pi 4 Pro ARM64**) com orquestração n8n e pipeline de mídia automatizado.
- **Tech Stack**: `n8n` • `Google Gemini 3.1 Flash-Lite` • `LangChain` • `Python` • `FFmpeg` • `Edge Neural TTS` • `Linux ARM64`
- **Key Highlights**:
  - **Tool Calling & Lock Condicional**: Consulta dinâmica de slots e atualização atômica exigindo `slotCode` + `status == 'livre'`, cravando TTL de 30min para blindar a agenda contra *race conditions*.
  - **Injeção Determinística de Contexto**: `sessionId` e metadados injetados pelo trigger sem intervenção do LLM, eliminando risco de alucinação de identificadores.
  - **Pipeline de Mídia Automatizado**: Scripts em Python para corte/aceleração de vídeos via `FFmpeg`, geração de narração neural normalizada em `-16 LUFS` e renderização de carrosséis `1080x1350` com Headless Chrome.
  - **Self-Hosted Zero-Cost**: Implantado em hardware dedicado Orange Pi 4 Pro (ARM64, 4GB DDR5) garantindo resposta rápida (~1.8s) e soberania operacional.

### 🛠️ [VL_Assistence — Full-Stack Technical Lab & Service Order Management](https://github.com/nunesxv/VL_Assistence_showcase)
Sistema completo de gestão para laboratórios de assistência técnica com integração cross-device para check-in fotográfico e governança jurídica.
- **Tech Stack**: `React.js (Vite)` • `TypeScript` • `Tailwind CSS` • `Node.js` • `Express` • `Prisma ORM` • `PostgreSQL (Supabase)` • `Multer`
- **Key Highlights**:
  - **RESTful API & ORM**: Backend estruturado em TypeScript com Express e modelagem relacional declarativa com Prisma ORM no Supabase PostgreSQL.
  - **Painel Financeiro Integrado**: Cálculo em tempo real de liquidez disponível, lucro líquido mensal e provisionamento automatizado para compra de peças.
  - **Check-in Fotográfico Cross-Device**: Geração dinâmica de QR Code na bancada desktop para captura direta de evidências fotográficas em rota mobile isolada com upload multipart/form-data via Multer.
  - **Resolução de Gargalos**: Isolamento de layout em rotas mobile para evitar vazamento visual (*layout leak*) e fallback condicional de hardware para câmeras de smartphone em ambientes locais.

### 📦 [SaaS Delivery Multi-Tenant — Real-Time Delivery & Merchant Platform](https://github.com/nunesxv/saas_delivery_showcase)
Plataforma SaaS multi-tenant unificando a experiência do consumidor (Storefront) ao painel administrativo dos lojistas (Dashboard & God Mode).
- **Tech Stack**: `React.js` • `TypeScript` • `Tailwind CSS` • `Supabase (PostgreSQL)` • `Row-Level Security (RLS)` • `Realtime WebSockets` • `Vercel`
- **Key Highlights**:
  - **Isolamento Multi-Tenant**: Blindagem rigorosa de dados multi-tenant via Row Level Security (RLS) no PostgreSQL, prevenindo vazamentos de dados entre estabelecimentos.
  - **Cálculo de Frete Inteligente (Haversine)**: Eliminação de dependência de APIs externas de roteamento calculando a distância por geometria esférica server-side via GPS do navegador.
  - **Checkout Reativo**: Resumo financeiro reativo suportando Pix, Cartão e Dinheiro com recálculo instantâneo antes da submissão.
  - **Engine de Fidelidade & Gestão de Caixa**: Regras de fidelidade personalizáveis por loja e módulo SPA para conciliação financeira de entradas (*suprimentos*) e sangrias em tempo real.
  - **Resolução de Schema Drift**: Troubleshooting e correção de desvio de schema entre instâncias de desenvolvimento e produção Vercel sem downtime.

---

## 🚀 Philosophy

> "Code isn't just about making a system work. It's about architecting honest foundations that turn failures into opportunities."

⭐ If you like my work, consider starring a repository
🤝 Always open to collaborations, partnerships, and cool ideas
