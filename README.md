# Real-Time Collaborative Document App

A full-stack collaborative document editing application built with **Next.js**, **Liveblocks**, **Clerk**, **Permit.io**, **Tailwind CSS**, and **shadcn/ui**.
This project supports real-time presence, access control, and user authentication.

🔗 **Read the full article here:** [How I Built a Real-Time Collaborative Editor with Next.js, Clerk, Permit, and Liveblocks](#)

---

## Tech Stack

* **Next.js** – React framework for fast frontend & API routes
* **Clerk** – User authentication and management
* **Permit.io** – Role-based access control and authorization
* **Liveblocks** – Real-time collaboration
* **Tailwind CSS** & **shadcn/ui** – For modern, responsive UI components

---

## Getting Started

### 1. **Clone the repo**

```bash
git clone https://github.com/OmaJuliet/live-docs.git
cd live-docs
```

### 2. **Install dependencies**

```bash
npm install
# or
yarn install
```

### 3. **Set up environment variables**

Create a `.env.local` file and add:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable
CLERK_SECRET_KEY=your_clerk_secret
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

LIVEBLOCKS_SECRET_KEY=your_liveblocks_key
PERMIT_API_KEY=your_permit_key
```

> Make sure you’ve configured your Clerk, Liveblocks, and Permit.io projects.

### 4. **Run the development server**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

---

## 📄 License

MIT – free to use and modify. Contributions are welcome!

---