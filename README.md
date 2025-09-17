# FitPickAI

WardrobeAI is a full-stack web application that helps users organize their virtual wardrobe and automatically generates a **daily outfit of the day (OOTD)**. Users can upload their clothes, mark availability (e.g., laundry), and get personalized outfit suggestions displayed on an avatar.

Built with **Next.js, Tailwind CSS, Supabase, and Vercel**.

---

## ✨ Features

- **User Accounts** – Secure authentication with Supabase Auth.
- **Wardrobe Management** – Upload clothing images and categorize by type (shirts, pants, shoes, etc.).
- **Outfit Generator** – ML model selects a daily outfit (avoids unavailable/repeated items).
- **Outfit of the Day** – See your auto-generated look on an avatar.
- **Responsive UI** – Clean design with Tailwind + shadcn/ui.

---

## 🛠️ Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/) (React + TypeScript)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + [shadcn/ui](https://ui.shadcn.com/) + [Framer Motion](https://www.framer.com/motion/)
- **Backend / Database**: [Supabase](https://supabase.com/) (Postgres, Auth, Storage)
- **Hosting**: [Vercel](https://vercel.com/) (CI/CD from GitHub)
- **Media Storage**: Supabase Storage
- **ML**: [Hugging Face](https://huggingface.co/) models for clothing selection

---

## 🚀 Getting Started

Visit [fitpickai](https://fitpickai.vercel.app/), or developers can also run locally:

### 1. Clone Repo

```bash
git clone https://github.com/cheesuschris/fitpickai.git
cd fitpickai
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create a local .env file

```bash
NEXT_PUBLIC_SUPABASE_URL=https://vxvonbjdddinyztmhddp.supabase.co
NEXT_PUBLIC_SUPABASE_ANON_KEY=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJzdXBhYmFzZSIsInJlZiI6InZ4dm9uYmpkZGRpbnl6dG1oZGRwIiwicm9sZSI6ImFub24iLCJpYXQiOjE3NTgxMjAzODYsImV4cCI6MjA3MzY5NjM4Nn0.D0SwpxETW9S6Is_m0yk19JYr85O6WD1KgehsWlnrtqU
```

### 4. Run dev server

```bash
npm run dev
```

---

## ⏳Future implementations

- Advanced outfit recommendation (season, occasion, weather-aware).
- Auto-tag clothing with ML (color, type, style).
- Share outfits with friends/social features.
- Calendar view of outfits.
- Outfit Tracker/Historical Log
