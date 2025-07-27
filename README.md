# 🎬 Movie App

A sleek, responsive movie browsing app built with **React.js**, **Appwrite**, and **Tailwind CSS**. This project leverages the **TMDB API** to display trending movies, search functionality, and more.


<div align="center">
  <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" />
  <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" />
  <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" />
</div>

---

## 📽️ Tutorial

Watch the complete build walkthrough on **JavaScript Mastery** YouTube channel:

> 📺 [Watch Tutorial](https://www.youtube.com/watch?v=dCLhUialKPQ)  
> 👨‍👩‍👧‍👦 [Join the JSM Discord (50k+ devs)](https://discord.com/invite/n6EdbFJ)

---

## 📋 Table of Contents

1. [Introduction](#introduction)  
2. [Tech Stack](#tech-stack)  
3. [Features](#features)  
4. [Getting Started](#getting-started)  
5. [Code Snippets](#code-snippets)  
6. [Assets](#assets)  
7. [More Resources](#more-resources)  

---

## 🤖 Introduction

This app allows users to:

- Browse trending movies
- Search by title
- View movie ratings and metadata
- Experience a beautiful and modern UI

Built with a fully responsive layout and clean architecture to promote maintainability and scalability.

---

## ⚙️ Tech Stack

- **React.js** – UI development with reusable components  
- **Appwrite** – Backend services for database, storage, and auth  
- **Tailwind CSS** – Utility-first CSS framework  
- **TMDB API** – Movie database API for content  
- **Vite** – Fast build tool and dev server  
- **React-Use** – Collection of useful React hooks  

---

## 🔋 Features

- 🔍 **Search Movies**  
- 📈 **Trending Algorithm**  
- 📱 **Fully Responsive UI**  
- 🎨 **Modern UX**  
- ♻️ **Reusable Components**

---

## 🤸 Getting Started

### ✅ Prerequisites

Make sure you have the following installed:

- [Git](https://git-scm.com/)  
- [Node.js & npm](https://nodejs.org/)

### 🧱 Clone the Repo

```bash
git clone https://github.com/adrianhajdin/react-movies.git
cd react-movies
📦 Install Dependencies
bash
Copy
Edit
npm install
🔐 Setup Environment Variables
Create a .env.local file in the root:

env
Copy
Edit
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
Get your API keys from TMDB and Appwrite.

🚀 Run the App
bash
Copy
Edit
npm run dev
Open your browser and go to: http://localhost:5173

🕸 Code Snippets
You can explore useful code snippets in the /components, /utils, and /styles directories of this project.

Example spinner component:

jsx
Copy
Edit
import React from 'react'

const Spinner = () => {
  return (
    <div role="status">
      <svg
        className="w-8 h-8 text-gray-200 animate-spin fill-indigo-600"
        viewBox="0 0 100 101"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path d="M100..." fill="currentColor" />
        <path d="M93..." fill="currentFill" />
      </svg>
      <span className="sr-only">Loading...</span>
    </div>
  );
};

export default Spinner;
