# News App

A simple news viewing application built with Next.js 15 and React 19. News data is loaded from a local SQLite database and displayed in a clean, responsive interface using CSS Modules.

## Tech Stack

- **Next.js 15**
- **React 19**
- **SQLite (via better-sqlite3)**
- **CSS Modules**

## Features

- Filter news articles by **year** and **month**
- Server-side data fetching with SQLite
- Modular and maintainable styling with CSS Modules

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- SQLite3 (installed on your system)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/plinadev/news-app.git
   cd news-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the development server:

   ```bash
   npm run dev
   ```

4. Open your browser at [http://localhost:3000](http://localhost:3000)

## Project Structure

```
/news-app
├── app/              # Next.js app directory (routes, layout, pages)
├── lib/              # SQLite database access and helpers
├── public/           # Static assets
├── styles/           # CSS Modules
├── database/         # Local SQLite DB file (if checked in)
├── package.json
└── README.md
```
