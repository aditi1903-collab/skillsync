# SkillSync – AI-Powered Resume Builder & Job Tracker

SkillSync is a MERN stack web application that helps users build resumes and track job applications. It's built using:

- React (Tailwind CSS) for the frontend
- Node.js + Express + MongoDB for the backend
- JWT for authentication

## Features
- User Authentication (JWT)
- Resume Builder Form
- Job Application Tracker
- Responsive Dashboard

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/SkillSync.git
cd SkillSync
```

### 2. Setup the Backend

```bash
cd server
npm install
cp .env.example .env
# Add your MONGO_URI and JWT_SECRET to .env
npm run dev
```

### 3. Setup the Frontend

```bash
cd ../client
npm install
npm start
```

### 4. Deploy

- **Frontend**: Deploy `/client` folder on **Netlify**
- **Backend**: Deploy `/server` folder on **Render**

## .env Setup

### `/server/.env.example`
```
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
```

---

## License
MIT License
