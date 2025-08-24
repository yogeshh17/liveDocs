
LiveDocs is a collaborative text editor built using **Next.js**, **TypeScript**, **TailwindCSS**, and **Liveblocks** for real-time functionality.

🎓 **Learning by Building** – This project was developed step-by-step to deepen understanding of full-stack development, real-time collaboration, and modern frameworks like Next.js and Liveblocks.

The goal of this project was to replicate core features of Google Docs while learning about authentication, document management, and live collaboration in a production-like setup.

---


## 🔋 Features

✅ GitHub Authentication (via NextAuth)  
✅ Real-Time Collaborative Editing  
✅ Document Creation, Deletion & Sharing  
✅ Inline + General Comments with Threads  
✅ Active Collaborator Presence  
✅ Email Notifications (for shares/comments)  
✅ Fully Responsive Layout  
✅ Clean, Modular Code Structure  

---

## ⚙️ Tech Stack

- **Next.js** – React framework for SSR and routing  
- **TypeScript** – Type-safe development  
- **Liveblocks** – Real-time collaboration infrastructure  
- **Lexical Editor** – Rich text editor  
- **ShadCN UI** – Accessible UI components  
- **Tailwind CSS** – Utility-first styling  
- **NextAuth (with GitHub)** – Secure authentication  

---


## 🚀 Getting Started

> ⚠️ Make sure you have the following installed:
- Git
- Node.js
- npm or yarn

### 1. Clone the Repository

```bash
git clone https://github.com/yogeshh17/liveDocs.git
cd liveDocs
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the root:

```env
# Clerk (Auth)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Liveblocks (Real-time)
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
LIVEBLOCKS_SECRET_KEY=
```

### 4. Run the Development Server

npm run dev


Visit `http://localhost:3000` to try it out!

