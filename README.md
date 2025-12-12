# Delivery Starter (Node.js + Express + Mongoose)

## What is inside
- Minimal starter with models: User (driver), Order, Location
- Basic routes:
  - POST /auth/login  (phone + password)
  - POST /orders      (create order)
  - GET  /orders/:id
  - POST /orders/:id/assign
  - POST /orders/:id/status
  - POST /drivers/:id/location
  - POST /drivers/:id/status

## Quick start
1. Copy `.env.example` to `.env` and set values.
2. `npm install`
3. `npm run dev` (requires nodemon) or `npm start`
4. Ensure MongoDB is running and MONGO_URI points to it.

## Notes
- This is only a minimal starter for demonstration and local development.
- Add authentication middleware, input validation, rate-limiting, and production hardening as needed.
