
---

````markdown
# DeepSeek Clone – Real-Time Streaming AI Chat Application  

A **full-stack AI-powered chat app** inspired by DeepSeek, built with the **MERN stack + modern web technologies**.  
Supports **real-time AI streaming**, **voice input**, **secure authentication**, and a **responsive UI**.  

---

## 🚀 Features  
- Real-time streaming chat via **DeepSeek API + Server-Sent Events (SSE)**  
- **JWT + Google OAuth authentication** with protected routes  
- Persistent chat history with **MongoDB + Zustand state management**  
- Voice-to-text input using **Web Speech API**  
- **Responsive UI** with **Next.js 15, React 19, Tailwind CSS, Shadcn UI**  
- **Monorepo architecture** (Turborepo) for scalable codebase  

---

## 🛠 Tech Stack  
**Frontend:** Next.js 15, React 19, TypeScript, Tailwind CSS, Shadcn UI, Zustand  
**Backend:** Node.js, Express.js, MongoDB, JWT, Google OAuth, REST API, SSE  
**Infra:** Monorepo (Turborepo), Vercel (optional), Web Speech API  

---

## ⚙️ Installation  
```bash
git clone https://github.com/your-username/deepseek-clone.git
cd deepseek-clone
pnpm install
````

Add `.env` with:

```
MONGO_URI=your-mongodb-uri
JWT_SECRET=your-secret
GOOGLE_CLIENT_ID=your-client-id
GOOGLE_CLIENT_SECRET=your-client-secret
DEEPSEEK_API_KEY=your-deepseek-api-key
```

Run backend:

```bash
cd apps/server && pnpm run dev
```

Run frontend:

```bash
cd apps/client && pnpm run dev
```

---

## 📂 Structure

```
deepseek-clone/
│── apps/client   # Next.js frontend
│── apps/server   # Express backend
│── packages/     # Shared UI, config, utils
│── .env.example
│── README.md
```

---

## 📈 Roadmap

* [ ] Export conversations (PDF/Markdown)
* [ ] Team chat with shared threads
* [ ] Dockerized deployment

---

