# Business Analytics Dashboard

A full-stack application for managing and displaying business analytics with SEO optimization features.

![Dashboard Screenshot](/screenshots/dashboard.png)

## Features
- Business data submission form
- Google rating simulation
- AI-generated SEO headlines
- Headline regeneration
- Responsive design

## Tech Stack
- **Frontend**: React + Tailwind CSS
- **Backend**: Node.js + Express
- **State Management**: React Context API

## Setup Instructions

### Prerequisites
- Node.js v16+
- npm v8+
- Git

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/business-dashboard.git
   cd business-dashboard
   ```

2. Set up backend:
   ```bash
   cd backend
   npm install
   ```

3. Set up frontend:
   ```bash
   cd ../frontend
   npm install
   ```

## Running the Application

1. Start backend server:
   ```bash
   cd backend
   npm start
   ```
   Server runs on `http://localhost:5001`

2. Start frontend development server:
   ```bash
   cd frontend
   npm start
   ```
   App runs on `http://localhost:3000`

## Environment Variables

Backend requires these environment variables (create `.env` file in backend folder):
```
PORT=5001
CORS_ORIGIN=http://localhost:3000
```

## Deployment

[Instructions for deploying to Vercel/Render/Netlify]