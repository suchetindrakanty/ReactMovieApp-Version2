<div align="center">
  <br />
    <a href="https://www.youtube.com/watch?v=dCLhUialKPQ" target="_blank">
      <img src="public/readme/hero.png" alt="Project Banner">
    </a>
  <br />
  
  <div>
    <img src="https://img.shields.io/badge/-React_JS-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-Vite-black?style=for-the-badge&logoColor=white&logo=vite&color=646CFF" alt="vite" />
  </div>

  <h3 align="center">React Movies Application</h3>

  <p align="center">
    A modern movie browsing application built with React, Appwrite, and TMDB API
    <br />
    <a href="https://github.com/adrianhajdin/react-movies/issues">Report Bug</a>
    ·
    <a href="https://github.com/adrianhajdin/react-movies/issues">Request Feature</a>
  </p>
</div>

## 📋 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Configuration](#configuration)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## ✨ Features

- Browse trending movies from TMDB API
- Search functionality with instant results
- Responsive design for all devices
- Modern UI with Tailwind CSS
- Appwrite backend integration
- Loading states and error handling

## 🛠 Tech Stack

- **Frontend**: React.js, Vite
- **Styling**: Tailwind CSS
- **Backend**: Appwrite
- **API**: The Movie Database (TMDB)
- **Build Tool**: Vite


## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/adrianhajdin/react-movies.git
cd react-movies
```

2. Install dependencies:
```bash
npm install
```

3. Configure environment variables (see [Configuration](#configuration))

4. Run the development server:
```bash
npm run dev
```

## ⚙️ Configuration

Create a `.env.local` file in the root directory with the following variables:

```env
VITE_TMDB_API_KEY=your_tmdb_api_key
VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
VITE_APPWRITE_DATABASE_ID=your_appwrite_database_id
VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
```

## 📂 Project Structure
