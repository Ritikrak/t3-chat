# 🤖 T3 Chat AI

A modern AI-powered chat application built with **Next.js**, **Prisma**, **PostgreSQL**, **Better Auth**, **Tailwind CSS**, and **Shadcn UI**. It provides secure authentication, persistent conversations, and a real-time chat experience with an intuitive and responsive interface.

---

## ✨ Features

### 🔐 Authentication
- Secure user authentication with **Better Auth**
- Sign up and sign in functionality
- Session management
- Protected routes
- User account support

### 💬 AI Chat
- Real-time AI conversations
- Persistent chat history
- Create multiple chat sessions
- Continue previous conversations
- Instant message updates
- Context-aware responses

### 🗂 Chat Persistence
- Store conversations in PostgreSQL
- Retrieve previous chats anytime
- Message history per user
- Conversation management

### 🎨 Modern UI
- Built with **Shadcn UI**
- Styled using **Tailwind CSS**
- Responsive design
- Light/Dark mode support
- Smooth and intuitive interface

### ⚡ Performance
- Server-side rendering with Next.js
- Optimized API routes
- Fast page loading
- Type-safe database access with Prisma

---

# 🏗 Tech Stack

## Frontend
- Next.js 15
- React
- TypeScript
- Tailwind CSS
- Shadcn UI

## Backend
- Next.js API Routes / Server Actions
- Better Auth

## Database
- PostgreSQL
- Prisma ORM

## Real-Time Features
- Streaming responses
- Persistent chat sessions
- Live message updates

---

# 📂 Project Structure

```bash
t3-chat-ai/
│
├── app/
│   ├── api/
│   ├── chat/
│   ├── auth/
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   ├── ui/
│   ├── chat/
│   ├── sidebar/
│   └── navbar/
│
├── lib/
│   ├── auth.ts
│   ├── prisma.ts
│   └── utils.ts
│
├── prisma/
│   ├── schema.prisma
│   └── migrations/
│
├── public/
├── styles/
├── .env
├── package.json
└── README.md
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/t3-chat-ai.git
cd t3-chat-ai
```

## Install Dependencies

```bash
npm install
```

---

# ⚙️ Environment Variables

Create a `.env` file in the root directory:

```env
DATABASE_URL="postgresql://username:password@localhost:5432/t3chat"

BETTER_AUTH_SECRET=your_secret_key
BETTER_AUTH_URL=http://localhost:3000

OPENAI_API_KEY=your_openai_api_key
```

---

# 🗄 Database Setup

Generate Prisma Client:

```bash
npx prisma generate
```

Run migrations:

```bash
npx prisma migrate dev
```

Open Prisma Studio:

```bash
npx prisma studio
```

---

# ▶️ Running the Application

Start the development server:

```bash
npm run dev
```

Open:

```text
http://localhost:3000
```

---

# 📊 Database Schema

### User
- id
- name
- email
- password
- createdAt

### Chat
- id
- title
- userId
- createdAt

### Message
- id
- role
- content
- chatId
- createdAt

---

# 🔄 Application Flow

1. User signs up or logs in using Better Auth.
2. A new chat session is created.
3. Messages are sent to the AI model.
4. Responses are streamed in real time.
5. Conversations are stored in PostgreSQL.
6. Users can revisit and continue previous chats.
7. All chats remain persistent across sessions.

---

# 📸 Features Overview

- 🧠 AI Chat Assistant
- 💬 Realtime Streaming Responses
- 🗃 Persistent Chat History
- 🔐 Better Auth Authentication
- 🌙 Dark Mode Support
- 📱 Responsive Design
- ⚡ Fast and Optimized
- 🎨 Beautiful UI with Shadcn UI
- 🛡 Type-Safe Database Queries with Prisma

---

# 🛠 Available Scripts

Start development server:

```bash
npm run dev
```

Build production:

```bash
npm run build
```

Start production server:

```bash
npm start
```

Lint code:

```bash
npm run lint
```

---

# 🔒 Security

- Secure authentication with Better Auth
- Environment variable protection
- Session management
- Protected API routes
- Database access through Prisma ORM

---

# 🚀 Future Improvements

- Voice conversations
- File uploads
- Image generation support
- Multi-model support
- Chat sharing
- Team workspaces
- Conversation search
- Markdown rendering
- Syntax highlighting for code blocks
- Export chats to PDF or Markdown

---

# 🤝 Contributing

1. Fork the repository

2. Create a new branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, please consider giving it a **star** on GitHub!

Made with ❤️ using **Next.js + Prisma + PostgreSQL + Better Auth + Tailwind CSS + Shadcn UI**.
