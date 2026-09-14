<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:1E293B,100:0F172A&text=Enterprise%20Event%20%26%20Participant%20Engine&fontColor=FFFFFF&fontSize=36&fontAlignY=40&desc=Next.js%2016%20%20Turbopack%20%20Supabase%20SSR%20%20PostgreSQL%20%20Groq%20AI%20%20FFmpeg%20Video%20Engine&descColor=94A3B8&descFontSize=15&descAlignY=62" width="100%" alt="Enterprise Event & Participant Engine" />

<br />

[![GitHub stars](https://img.shields.io/github/stars/chilkotiKartik/=for-the-badge&logo=github&color=1E293B)](https://github.com/chilkotiKartik/enterprise-event-system/stargazers)
[![License](https://img.shields.io/badge/License-MIT-0284c7?style=for-the-badge)](LICENSE)
[![Maintained](https://img.shields.io/badge/Maintained%3F-yes-10b981?style=for-the-badge)](https://github.com/chilkotiKartik/enterprise-event-system)
[![Author](https://img.shields.io/badge/Author-Kartik%20Chilkoti-6366f1?style=for-the-badge)](https://github.com/chilkotiKartik)

</div>

---

## 📌 Project Overview

A full-scale enterprise platform engineered for large-scale event operations, participant onboarding, automated communications, and AI-assisted workflows. Features integrated client-side FFmpeg for video processing, Groq LLM integration for automated query triage, and PostgreSQL migrations.

---

## 🚀 Key Features

- **AI-Powered Event Assistance:** Integrated Groq LLM API for automated attendee inquiry resolution and workflow routing.
- **Client-Side Media Processing:** WASM-powered FFmpeg for video transcoding and participant ID proof verification directly in-browser.
- **Enterprise Identity & Data Access:** Supabase SSR with PostgreSQL role-based authorization for event administrators and participants.
- **Progressive Web App (PWA):** Offline capability with service workers and responsive mobile-first views.

---

## 🛠️ Architecture & Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend Framework** | Next.js 16 (Turbopack), React 19, TypeScript |
| **Backend & Database** | PostgreSQL (pg), Supabase SSR, Node.js |
| **AI & Media Engine** | Groq SDK (LLM Triage), @ffmpeg/ffmpeg (WASM Video Processing) |
| **UI & Animation** | Tailwind CSS, Framer Motion, Lucide Icons, Next PWA |
| **Email & Services** | Nodemailer, Country-State-City |

---

## 📂 Repository Structure

`	ext
enterprise-event-system/
??? app/                    # Next.js App Router (Pages, Layouts, API Routes)
??? docs/                   # API Specifications, Architecture & User Flow Diagrams
??? scripts/                # Utility scripts & icon generators
??? event_participants_migration.sql # Production PostgreSQL migration schema
??? AWS_MIGRATION_GUIDE.md  # Cloud deployment and infrastructure guide
`

---

## ⚙️ Environment Configuration

Create a .env.local or .env file in the root directory:

`nv
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
GROQ_API_KEY=your_groq_api_key
DATABASE_URL=postgresql://user:password@localhost:5432/events_db
SMTP_HOST=smtp.mailgun.org
SMTP_USER=your_smtp_user
SMTP_PASS=your_smtp_password
`

---

## 🚦 Getting Started

### 1. Clone the Repository
`ash
git clone https://github.com/chilkotiKartik/enterprise-event-system.git
cd enterprise-event-system
`

### 2. Install Dependencies
`ash
npm install
`

### 3. Run Development Server
`ash
npm run dev
`

Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

---

## 👤 Author

**Kartik Chilkoti**
- **GitHub:** [@chilkotiKartik](https://github.com/chilkotiKartik)
- **Email:** [chilkotikartik@gmail.com](mailto:chilkotikartik@gmail.com)

---

<div align="center">
<sub>Engineered with precision by <strong>Kartik Chilkoti</strong> &bull; All rights reserved.</sub>
</div>
