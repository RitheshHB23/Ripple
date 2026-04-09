# Ripple

Ripple is a prototype social impact platform built with Next.js, TypeScript, and Tailwind CSS.

## What’s Included

- Landing page with AI-style micro-action messaging
- Cause cards and live activity feed
- Mock backend API routes for causes, actions, impact, and authentication
- Dynamic home page content loaded from `/api/causes`

## Run the App

```bash
npm install
npm run dev
```

Then open `http://localhost:3000`.

## API Endpoints

- `GET /api/causes`
- `POST /api/actions`
- `GET /api/user/impact`
- `POST /api/auth/login`
- `POST /api/auth/register`

## Notes

This project uses mock data in `src/lib/mockData.ts` and can be extended to connect to a real database and authentication backend.
