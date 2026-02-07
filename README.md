# TaskManager Frontend

A modern, production-ready React application for task management, built with Vite, TypeScript, and Tailwind CSS.

## Features

- **Auth System**: Login, registration, and JWT persistence.
- **Dashboard**: Stats overview and activity charts.
- **Task Manager**: Full CRUD operations with modals and toast notifications.
- **Responsive Design**: Mobile-first approach with Tailwind CSS.
- **Clean Architecture**: Modular components, hooks, and services.

## Tech Stack

- **Framework**: React 18 with TypeScript
- **Tooling**: Vite
- **Styling**: Tailwind CSS
- **Routing**: React Router 6
- **API**: Axios
- **Icons**: Lucide React
- **Charts**: Recharts
- **Animations**: Framer Motion
- **Toasts**: React Hot Toast

## Getting Started

### 1. Prerequisites
- Node.js (v18+)
- npm

### 2. Installation
```bash
# From the project root
cd frontend

# Install dependencies
npm install
```

### 3. Configuration
The app uses environment variables defined in `.env`.
The default `VITE_API_URL` is set to `http://localhost:8000/api/v1`.

### 4. Running the App
```bash
npm run dev
```
The app will be available at [http://localhost:5173](http://localhost:5173).

## Directory Structure
```text
frontend/
├── src/
│   ├── components/   # Reusable UI components
│   ├── context/      # Context providers (Auth)
│   ├── layouts/      # Page layout wrappers
│   ├── pages/        # View components
│   ├── routes/       # Route definitions
│   ├── services/     # API service and interceptors
│   ├── types/        # TypeScript interfaces
│   └── App.tsx       # Root component
├── .env              # Environment config
├── tailwind.config.js # Tailwind settings
└── vite.config.ts    # Vite settings
```
