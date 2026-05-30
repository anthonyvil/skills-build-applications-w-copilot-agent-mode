# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19, Node.js, Express, TypeScript, and MongoDB.

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   ├── package.json
│   ├── vite.config.ts
│   └── tsconfig.json
├── backend/           # Express.js + TypeScript API
│   ├── src/
│   ├── package.json
│   ├── tsconfig.json
│   └── .env.example
└── README.md
```

## Technology Stack

### Frontend
- **React 19** - Latest React with new features
- **Vite** - Lightning-fast build tool
- **TypeScript** - Type-safe JavaScript
- **Port**: 5173

### Backend
- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **TypeScript** - Type-safe backend
- **Mongoose** - MongoDB ODM
- **Port**: 8000

### Database
- **MongoDB** - NoSQL database
- **Port**: 27017

## Getting Started

### Prerequisites
- Node.js (v18+)
- npm or yarn
- MongoDB running locally or connection URI

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

The backend API will be available at `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running on `mongodb://localhost:27017` or update the `MONGODB_URI` in `.env`

## Available Scripts

### Frontend
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

### Backend
- `npm run dev` - Start development server with auto-reload
- `npm run build` - Compile TypeScript
- `npm start` - Start production server

## API Endpoints

- `GET /api/health` - Health check endpoint

## License

MIT
