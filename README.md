# SkillSync – MERN Resume Builder & Job Tracker (Minimal Starter)

This repository contains a minimal MERN stack app boilerplate for SkillSync.

## Backend Setup

1. Go to `/server`
2. Run:
```bash
npm install express mongoose cors dotenv
```
3. Create a `.env` file based on `.env.example` with your MongoDB URI and JWT secret.
4. Start the server:
```bash
node index.js
```

## Frontend Setup

1. Go to `/client`
2. Run:
```bash
npm install
npm start
```

## Deployment

- Backend: Deploy `/server` on Render or similar.
- Frontend: Deploy `/client` on Netlify.