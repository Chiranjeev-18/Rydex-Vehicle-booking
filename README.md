# Rydex Vehicle Booking Monorepo

This repository contains two apps:

- `rydex` - the Next.js frontend and API routes
- `socketServer` - the Socket.IO server used by the app

## Folder Structure

- `rydex/` - main web app
- `socketServer/` - realtime socket server

## Setup

1. Install dependencies for each app:

```bash
cd rydex
npm install

cd ../socketServer
npm install
```

2. Create environment files from the examples:

- `rydex/.env.example`
- `socketServer/.env.example`

3. Start the apps:

```bash
cd rydex
npm run dev
```

```bash
cd socketServer
npm run dev
```

## Notes

- Do not commit real `.env` files.
- The frontend expects several external services such as MongoDB, Google auth, Razorpay, Stripe, Cloudinary, Zego, and email credentials.