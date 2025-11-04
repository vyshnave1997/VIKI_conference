
````markdown
# 🎥 Viki Conference

A modern video conferencing web app built with **Next.js 14**, **Clerk Authentication**, and **Stream Video SDK**.  
It provides secure sign-in, real-time video streaming, and a sleek UI powered by **Tailwind CSS** and **Radix UI**.

---

## 🚀 Features

- 🔐 **Authentication** with [Clerk](https://clerk.com/) (Sign-in, Sign-up, User Management)
- 🎥 **Video Streaming & Calls** via [Stream Video SDK](https://getstream.io/video/)
- 💬 **UI Components** using [Radix UI](https://www.radix-ui.com/) and [Lucide Icons](https://lucide.dev/)
- 🧩 **Reusable Components** with `class-variance-authority` and `clsx`
- 🎨 **Responsive Design** using Tailwind CSS + Tailwind Animate
- 🗓️ **Date Picker** integration with `react-datepicker`
- ⚡ Built on **Next.js 14** (App Router)

---

## 🧰 Tech Stack

| Category | Tools |
|-----------|--------|
| **Framework** | [Next.js 14](https://nextjs.org/) |
| **Language** | [TypeScript](https://www.typescriptlang.org/) |
| **Auth** | [Clerk](https://clerk.com/) |
| **Video SDK** | [Stream](https://getstream.io/video/) |
| **UI** | [Tailwind CSS](https://tailwindcss.com/), [Radix UI](https://www.radix-ui.com/), [Lucide React](https://lucide.dev/) |
| **Utilities** | `clsx`, `class-variance-authority`, `tailwind-merge` |
| **Date Handling** | `react-datepicker` |

---

## 🏗️ Project Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/viki-video.git
cd viki-video
````

### 2️⃣ Install dependencies

```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3️⃣ Configure environment variables

Create a `.env.local` file in the root directory:

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key
```

> 🔑 You can get these from your Clerk and Stream dashboards.

---

### 4️⃣ Run the development server

```bash
npm run dev
```

Visit 👉 [http://localhost:3000](http://localhost:3000)

---

## 🏁 Build for Production

```bash
npm run build
npm run start
```

---

## 🧹 Lint & Format

```bash
npm run lint
```

---

## 🧪 Folder Structure

```
viki-video/
├── app/                # Next.js app directory
├── components/         # Reusable UI components
├── lib/                # Utilities & helpers
├── public/             # Static assets
├── styles/             # Global styles & Tailwind
├── .env.local          # Environment variables
├── package.json
└── tailwind.config.js
```

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this project and submit a PR.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 💡 Credits

* [Clerk](https://clerk.com/)
* [Stream Video SDK](https://getstream.io/video/)
* [Next.js](https://nextjs.org/)
* [Tailwind CSS](https://tailwindcss.com/)
* [Radix UI](https://www.radix-ui.com/)

```

---

Would you like me to make it **specific to your use case** (for example, if “Viki Video” is for team meetings, online tutoring, or video events)? I can tailor the README description and features accordingly.
```
