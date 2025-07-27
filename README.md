<div align="center">
  <br />
 
  <br />
  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
  </div>

  <h3 align="center">Movie App Project</h3>

  <div align="center">
    Learn to build this application step-by-step on the <a href="https://www.youtube.com/@javascriptmastery/videos" target="_blank"><b>JavaScript Mastery</b></a> YouTube channel.
  </div>
</div>

---

## 📋 Table of Contents

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
5. [Snippets](#snippets)
6. [Assets](#assets)
7. [More](#more)

---

## 🚨 Tutorial

> Follow this video tutorial on YouTube: [Watch Here](https://www.youtube.com/watch?v=dCLhUialKPQ)

<a href="https://www.youtube.com/watch?v=dCLhUialKPQ" target="_blank">
  <img src="https://github.com/sujatagunale/EasyRead/assets/151519281/1736fca5-a031-4854-8c09-bc110e3bc16d" alt="YouTube Tutorial" />
</a>

---

## 🤖 Introduction

A modern, responsive movie browser built with **React.js**, **Appwrite**, **TailwindCSS**, and powered by the **TMDB API**.

Easily search, explore trending titles, and view metadata with a smooth and sleek user interface.

Join our 50k+ dev community on [Discord](https://discord.com/invite/n6EdbFJ) if you get stuck or need help.

<a href="https://discord.com/invite/n6EdbFJ" target="_blank">
  <img src="https://github.com/sujatagunale/EasyRead/assets/151519281/618f4872-1e10-42da-8213-1d69e486d02e" />
</a>

---

## ⚙️ Tech Stack

* **Appwrite** – Backend as a Service (auth, DB, storage)
* **React.js** – Reusable component-based UI
* **React-use** – Essential utility hooks
* **Tailwind CSS** – Utility-first styling
* **Vite** – Next-gen frontend tooling (HMR + fast build)

---

## 🔋 Features

* 🔍 **Search Movies**
* 📊 **Trending Algorithm**
* 📱 **Responsive Design**
* 🖌 **Modern UI/UX**
* ♻️ **Reusable Components**

---

## 🤸 Quick Start

### Prerequisites

* Node.js
* npm
* Git

### Clone & Setup

```bash
git clone https://github.com/adrianhajdin/react-movies.git
cd react-movies
npm install
```

### Environment Variables

Create a `.env.local` file:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_db_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
```

### Run Locally

```bash
npm run dev
```

Open: [http://localhost:5173](http://localhost:5173)

---

## 🕸️ Snippets

Sample from `index.css`

```css
body {
  font-family: "DM Sans", serif;
  background: #030014;
}
main {
  min-height: 100vh;
  background-color: #030014;
}
.wrapper {
  max-width: 1280px;
  margin: auto;
  padding: 3rem 1rem;
}
```

Sample `Spinner.jsx`

```jsx
const Spinner = () => (
  <div role="status">
    <svg className="w-8 h-8 animate-spin text-indigo-600" viewBox="0 0 100 101">
      <circle cx="50" cy="50" r="45" stroke="currentColor" strokeWidth="10" fill="none" />
      <path fill="currentFill" d="M93.9676 39.0409..." />
    </svg>
    <span className="sr-only">Loading...</span>
  </div>
);
export default Spinner;
```

---



### ✨ Made with ❤️ by Suchet Indrakanty
