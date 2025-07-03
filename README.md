# SmartTrackAI 🧠🐞

SmartTrackAI is a full-stack issue tracking system enhanced with AI. It helps developers log and manage issues while AI suggests relevant tags, detects duplicates, and predicts ticket priority.

## Features
- 🐛 Log bugs or feature requests
- 🎯 AI-generated tag and priority suggestions
- 🔍 Smart duplicate issue detection
- 🔐 JWT-based authentication
- 🌐 Deployed with Vercel + Render

## Tech Stack
- **Frontend**: React, TypeScript, Tailwind, shadcn/ui
- **Backend**: Node.js, Express, Prisma
- **DB**: PostgreSQL
- **AI**: OpenAI API (GPT-4)
- **Deploy**: Vercel (frontend), Render (backend), Railway (PostgreSQL)

## Setup

```bash
# Frontend
cd frontend
npm install
npm run dev

# Backend
cd ../backend
npm install
npm run dev
