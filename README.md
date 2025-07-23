# 🧠 Resumaid — AI-powered Resume Analyzer

Build an AI-powered Resume Analyzer with React, React Router, and Puter.js! Create job listings, upload candidate resumes, and use AI to automatically evaluate and match resumes to job requirements. Deployed on Vercel for lightning-fast, global access.

[🚀 Live Demo](https://resumaid-ten.vercel.app/)

---

## ✨ Introduction

Resumaid is a fully responsive AI-powered resume analyzer built using React, React Router, and Puter.js. It enables recruiters or hiring managers to post job listings, and candidates to upload resumes, which are then automatically analyzed and matched to job requirements using AI.

You can:
- Upload and store resumes
- Analyze candidate suitability with AI
- Get ATS-like scores and custom feedback
- View smart match results per job

---

## ⚙️ Tech Stack

- **React** — Component-based UI library
- **React Router v7** — Modern routing with data APIs and code splitting
- **Puter.js** — Serverless SDK with built-in auth, storage, and AI
- **Tailwind CSS** — Utility-first CSS framework
- **TypeScript** — Typed JavaScript for better tooling and safety
- **Vite** — Lightning-fast build tool and dev server
- **Zustand** — Minimal state management
- **Vercel** — Hosting & deployment platform (used here instead of Puter hosting)

---

## 🔋 Features

✅ **Client-side Authentication** — Auth with no backend using Puter.js  
✅ **Resume Upload & Storage** — Save resumes securely in the cloud  
✅ **AI Resume Evaluation** — Auto-match resumes to job listings with smart feedback  
✅ **Clean UI & Modern Design** — Built with Tailwind
✅ **Fully Responsive** — Works on mobile, tablet, and desktop  
✅ **Type-safe Codebase** — Built with TypeScript for stability and scalability  
✅ **Reusable Components** — Modular structure for rapid development  
✅ **Fast Deployment** — Deployed on Vercel for global reach

---

## 🤸 Quick Start

### 🔧 Prerequisites

- Git
- Node.js
- npm

### 📦 Installation

```bash
git clone https://github.com/mohitbansal25082006/resumaid.git
cd resumaid
npm install
```

### ▶️ Run Locally

```bash
npm run dev
```

Open your browser and visit:  
**http://localhost:5173**

### 🚀 Deploy to Vercel

To deploy:

1. Push your code to GitHub.
2. Visit [vercel.com](https://vercel.com) and import your repo.
3. Set:
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
   - **Install Command**: *(leave blank)*
   - **Root Directory**: `./`
4. Set `ssr: false` in `react-router.config.ts`
