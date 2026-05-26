# Book Management (React + Vite + Tailwind)

A polished Book Management frontend built with React, Vite, TailwindCSS and JSON Server (mock API).

## Features
- View, add, edit, delete books
- Search by title/author
- Filter by genre
- Loading states, error handling, empty states
- Responsive, modern UI

## Quick Start

1. Install dependencies

```bash
npm install
```

2. Start mock API and dev server (runs both concurrently):

```bash
npm run start
```

- JSON Server runs at `http://localhost:3001`
- Vite dev server runs at `http://localhost:5173`

3. Open the app in your browser.

## Mock API

The repository contains `db.json` used by `json-server`.

### Endpoints
- `GET /books`
- `POST /books`
- `PUT /books/:id`
- `DELETE /books/:id`

## Deployment
- For Vercel or Netlify, build with `npm run build` and deploy the `dist` folder.
- Ensure the API is provided (JSON Server isn't used in production). Use a hosted API or mock service.

## Notes
- API base URL: `http://localhost:3001` (change in `src/utils/constants.js` if needed)
- Tailwind is configured in `tailwind.config.cjs`

Enjoy! 🎉
