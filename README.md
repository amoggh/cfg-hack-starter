# cfg-hack-starter

A production-ready hackathon starter template designed for rapid MVP development during J.P. Morgan Code for Good.

## Purpose

This repository is built to reduce setup time during hackathons and allow the team to focus on solving real-world problems rather than configuring infrastructure.

It provides:
- Pre-configured frontend + backend structure
- Authentication setup
- Database integration
- Clean folder structure
- Ready-to-deploy configuration

## Tech Stack

Frontend:
- React (Vite)
- Tailwind CSS

Backend:
- Node.js
- Express.js

Database:
- MongoDB Atlas

Deployment:
- Vercel (Frontend)
- Render (Backend)

## Architecture

User → React Frontend → Express API → MongoDB

- Frontend handles UI and API requests
- Backend manages authentication and business logic
- MongoDB stores structured data

## Project Structure

cfg-hackstarter/
│
├── client/        # React frontend
├── server/        # Express backend
├── docs/          # Architecture diagrams
└── README.md

## ⚙️ Setup Instructions

### 1. Clone the repository
git clone <repo-link>

### 2. Setup Backend
cd server
npm install
npm run dev

### 3. Setup Frontend
cd client
npm install
npm run dev

### 4. Environment Variables
Create a .env file in /server:

MONGO_URI=your_mongodb_uri
PORT=5000

## Current Features

- User Authentication (JWT-based)
- CRUD API structure
- Modular folder architecture
- Environment-based configuration
- Deployment-ready setup

## Why This Matters for Code for Good

During a 24-hour hackathon:

- Infrastructure time is minimized
- Team can focus on core problem-solving
- Rapid feature addition becomes easier
- Deployment can be done quickly for demo

This template is designed for speed, clarity, and scalability.

## Live Demo

Frontend: <link>
Backend API: <link>

## Future Enhancements

- Role-based authentication
- Logging and monitoring
- Docker containerization
- CI/CD pipeline setup
