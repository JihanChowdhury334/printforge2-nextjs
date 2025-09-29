# PrintForge 3D Models

A modern **3D model showcase platform** built with **Next.js 15**, **TypeScript**, and **Tailwind CSS**.  
The app allows browsing, filtering, and viewing details of 3D models with a clean responsive UI.

---

## 🚀 Features
- **Home & About Pages**: Simple landing and info sections.
- **3D Models Index**: Search and filter models dynamically.
- **Categories Navigation**: Browse models by category with a sticky sidebar.
- **Model Details**: Individual pages showing description, likes, category tags, and added date.
- **Responsive Design**: Fully optimized for desktop and mobile.
- **Reusable Components**: `ModelCard`, `ModelsGrid`, `Pill`, `Navbar`, `NavLink`, etc.

---

## 🛠️ Tech Stack
- **Framework**: [Next.js 15](https://nextjs.org/)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Icons**: React Icons
- **Data**: Static JSON (`models.json`, `categories.json`)  

---

## 📂 Project Structure
```
app/
 ├─ about/               → About page
 ├─ 3d-models/           → Models index, categories, details
 │   ├─ [id]/page.tsx    → Model detail page
 │   ├─ categories/      → Category-specific pages
 │   └─ page.tsx         → All models + search
 ├─ components/          → Reusable UI components
 ├─ lib/                 → Data fetching helpers
 ├─ layout.tsx           → Root layout
 ├─ globals.css          → Global styles
 └─ page.tsx             → Home page
```

---

## ⚡ Getting Started

Clone the repo:
```bash
git clone https://github.com/YOUR-USERNAME/printforge2-nextjs.git
cd printforge2-nextjs
```

Install dependencies:
```bash
npm install
```

Run locally:
```bash
npm run dev
```

Build for production:
```bash
npm run build
npm start
```

---

## 📜 License
MIT License — feel free to use and adapt this project.
