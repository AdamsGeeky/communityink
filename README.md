# 🌍 Community Ink

---

## ✨ Project Overview

**CommunityInk** is an open-source  Platform Empowering Students to Share, Learn, and Connect Through a Modern Campus-Centric.  platform built by students for students. It serves as a central hub where students can

- 📚 Share learning resources
- 🧑‍🤝‍🧑 Collaborate on projects
- 📰 Stay updated on academic and campus activities
- 🧠 Build their digital portfolio

This project is part of a mentorship initiative where beginner and intermediate developers learn by building real-world impactful software together.
---

## 🚀 Live Preview

🌍 [communityink.netlify.app](https://communityink.netlify.app)  
*(Note: Current version is being rebuilt with modern stack.)*

---

## 🧱 Folder Structure

```bash
communityink/
├── client/          # Frontend (Next.js)
├── server/          # Backend (Node.js + Express)
├── README.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── LICENSE

---

## 🛠️ Tech Stack

### ✨ Frontend (Client)
- **Framework**: Next.js 14 (App Router)
- **UI**: ShadCN + TailwindCSS
- **TypeScript**: For safer, scalable code
- **Deployment**: Vercel

### ⚙️ Backend (Server)
- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: Supabase (PostgreSQL + Auth + Storage)
- **Authentication**: Supabase Auth + Middleware
- **APIs**: RESTful design

---

## 🧩 Features

- 🔐 **Authentication**: Secure user login and role-based access control
- 📝 **Feed System**: Create, read, and interact with community posts
- 📂 **Resource Uploads**: Share and download academic files
- 📢 **Notifications**: Get updates in-app
- 💬 **Communication**: Seamless WhatsApp and Telegram integration
- 📰 **Blog**: Hashnode embedded for technical and project updates

---

# Project Structure

## Getting Started

1. Clone the Repository

``bash
git clone https://github.com/open-source-learners/communityink.git
cd communityink
```

2. Set Up Branches

```bash
git checkout -b client-dev origin/client-dev
git checkout -b server-dev origin/server-dev
```

### Frontend (Client)

```bash
cd client
npm install
npm run dev
```


# Beginner-Friendly Issues

We use labels like:

- good first issue

- frontend-beginner

- backend-beginner

- help wanted
 
[Check the Issues Page](https://github.com/open-source-learners/communityink/issues)

# Contributing
We follow a mentorship-first and learn-by-doing approach.
Read our CONTRIBUTING.md to get started.

# Branch strategy:

- main – Stable deployed version

- client-dev – Ongoing frontend work

- server-dev – Ongoing backend work