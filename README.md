# Expense Tracker Dashboard

A full-stack expense tracking dashboard for managing personal finances with authentication, transaction tracking, dashboard summaries, and smart insights.

## Features
- User registration and login with JWT-based authentication
- Transaction management with category assignment and date filters
- Dashboard summaries, category breakdowns, and monthly trend charts
- Smart insights for recurring expenses, budget alerts, and next-month forecasts
- Prisma + PostgreSQL backend and Vite + React frontend

## Tech Stack
- Frontend: React, Vite, Tailwind CSS, Recharts, Axios
- Backend: Node.js, Express, Prisma, PostgreSQL, Zod, JWT

## Project Structure
- backend/: Express API, Prisma schema, routes, controllers, and services
- frontend/: React dashboard UI with charts and data views

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
Created by: Sumit Kumar
Intern ID: CITS101
