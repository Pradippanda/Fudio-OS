Installation Guide

Requirements

Before installing Fudio OS, make sure you have:

- Node.js 20+
- npm or pnpm
- Git
- Supabase Project

---

Clone the Repository

git clone https://github.com/Pradippanda/Fudio-OS.git
cd Fudio-OS

---

Install Dependencies

npm install

---

Configure Environment Variables

Create a ".env.local" file:

NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=

---

Start Development Server

npm run dev

Open:

http://localhost:3000

---

Build for Production

npm run build
npm start
