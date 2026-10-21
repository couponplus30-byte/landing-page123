# landing-page7788

AI Landing Page Maker SaaS — High-converting landing page synthesis engine with voice-to-page intelligence, real-time sandboxed live previews, multi-session chat history, n8n webhook integration, Supabase cloud sync, and full English / Arabic (LTR / RTL) localization.

## 🚀 Features

- **⚡ AI Generation Engine**: Natural language prompt processing with automated fallback synthesizers.
- **🎙️ Voice-to-Page (Speech Recognition)**: Multilingual speech-to-text in Arabic and English for hands-free creation.
- **🌐 Internationalization (i18n)**: Default English interface with seamless 1-click toggle to Arabic (`dir="rtl"`).
- **🛡️ Bulletproof Crash Guards**: Process-level unhandled exception shields, 50MB payload limits, and React Error Boundaries.
- **📦 Multi-Session Isolated History**: Per-user storage isolation preventing session crosstalk across browsers or accounts.
- **📡 Public Live Hosting**: Instant raw HTML live previews served directly at `/p/:id`.
- **🔗 Supabase & n8n Sync**: Dual persistence with resilient local JSON fallbacks and cloud databases.

## 🛠️ Tech Stack

- **Frontend**: React 19, TypeScript, Tailwind CSS, Vite, Lucide Icons, React Router 7.
- **Backend**: Node.js, Express, Helmet, CORS, Rate Limiters, Supabase JS, Axios.

## 🏃 Running Locally

### 1. Frontend:
```bash
npm install
npm run dev
```

### 2. Backend:
```bash
cd backend
npm install
node server.js
```
