# Expense Tracker Dashboard

A full-stack expense tracking dashboard with authentication, transaction management, dashboard summaries, and smart insights.

## Features
- User registration and login with JWT-based authentication
- Transaction CRUD with category assignment and date filters
- Dashboard summary cards, category breakdowns, and monthly trend charts
- Smart insights for recurring expenses, budget alerts, and next-month forecasts
- Prisma + PostgreSQL backend and Vite + React frontend

## Tech Stack
- Frontend: React, Vite, Tailwind CSS, Recharts, Axios
- Backend: Node.js, Express, Prisma, PostgreSQL, Zod, JWT

## Project Structure
- backend/: Express API, Prisma schema, routes, controllers, services
- frontend/: React app with charts and dashboard UI

## Setup
1. Install dependencies in both folders.
2. Create a PostgreSQL database and add the connection string to the backend environment file.
3. Run Prisma migrations and start the development servers.

## Local Development
```bash
cd backend
npm install
npx prisma migrate dev --name init
npm run dev
```

```bash
cd frontend
npm install
npm run dev
```

## Author
Made by: Sumit Kumar
Intern ID: CITS101
