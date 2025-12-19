# Welcome to the Vibe - Music Streaming Platform

A modern music streaming platform for discovering and enjoying African music.

## Getting Started

### Prerequisites

- Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

### Installation

```sh
# Step 1: Navigate to the frontend directory
cd frontend

# Step 2: Install the necessary dependencies
npm install

# Step 3: Start the development server
npm run dev
```

The application will be available at `http://localhost:5173`

### Build for Production

```sh
npm run build
```

The production build will be in the `dist` directory.

## Technologies

This project is built with:

- **Vite** - Build tool and dev server
- **TypeScript** - Type-safe JavaScript
- **React** - UI library
- **shadcn-ui** - UI component library
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing

## Project Structure

```
frontend/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Page components
│   ├── contexts/       # React contexts (Player, Auth)
│   ├── lib/            # Utilities and API client
│   └── assets/         # Static assets
├── public/             # Public assets
└── package.json       # Dependencies and scripts
```

## Features

- 🎵 Music streaming and playback
- 🎨 Modern, responsive UI
- 📱 Mobile-friendly design
- 🔍 Search functionality
- 📚 Library management
- ❤️ Liked songs
- 🎧 Music player with controls
