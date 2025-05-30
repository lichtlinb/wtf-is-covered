# WTF Is Covered?

**Tagline:** Explain my health insurance like I’m 5.

WTF Is Covered? is a mobile-first, AI-powered assistant that helps everyday people understand their health insurance. Upload your benefits PDF or EOB, and it instantly gives you a human-friendly summary. Then ask questions — like “Is insulin covered?” or “What’s my ER copay?” — and get answers in plain English.

---

## 🧱 Tech Stack
- Frontend: Bolt.js / Vercel
- AI Engine: OpenAI GPT-4o
- Backend: Supabase / Postgres
- File Parsing: PDF.co or GPT-4o Vision
- Auth: Magic.link / Firebase
- Hosting: Vercel

---

## 🚀 Getting Started

1. Clone the repo  
   `git clone https://github.com/YOUR_USERNAME/wtf-is-covered.git`

2. Install dependencies  
   `npm install`

3. Copy environment variables  
   `cp .env.example .env`

4. Run locally  
   `npm run dev`

---

## 📁 Folder Structure
- `/pages` — Next.js pages
- `/components` — Reusable components
- `/utils` — Helpers and GPT prompt logic
- `/public` — Static assets

---

## 📦 .env.example
See `.env.example` for required config.

---

## 🧠 Prompt Sample
```
System: You are a helpful insurance interpreter. Explain health benefits clearly and simply.

User: Can I get bloodwork without paying out of pocket?
```

---

## 📜 License
MIT
