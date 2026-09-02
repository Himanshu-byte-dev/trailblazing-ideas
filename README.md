# Civic Voice

A modern web application built with TanStack Start, React, and Tailwind CSS.

**Live site:** https://concept-blaze-forge.lovable.app

---

## Overview

Civic Voice is a full-stack React application scaffolded on an edge-ready
TanStack Start foundation. It ships with file-based routing, server-side
rendering, typed server functions, and a Tailwind v4 design system — so new
features can be added without wiring up build tooling first.

## Features

- **File-based routing** — every file in `src/routes` is a page
- **SSR + streaming** out of the box via TanStack Start
- **Typed server functions** for backend logic, no separate API server
- **Tailwind CSS v4** with CSS-first theming in `src/styles.css`
- **TypeScript everywhere**, strict by default
- **Edge deployable** — runs on Cloudflare Workers-style runtimes

## Tech stack

| Layer | Choice |
| --- | --- |
| Framework | TanStack Start v1 (React 19) |
| Router | TanStack Router (file-based) |
| Build tool | Vite 7 |
| Styling | Tailwind CSS v4 |
| Data | TanStack Query |
| Language | TypeScript |

## Getting started

You need [Node.js](https://nodejs.org) 20+ (install with
[nvm](https://github.com/nvm-sh/nvm#installing-and-updating)).

```sh
git clone <this-repository-url>
cd <repository-name>
npm install
npm run dev
```

The dev server starts at http://localhost:8080.

### Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the dev server with hot reload |
| `npm run build` | Production build |
| `npm run lint` | Lint the codebase |

## Project structure

```
src/
├── routes/          # File-based routes (__root.tsx is the app shell)
├── components/      # Reusable UI components
├── hooks/           # Custom React hooks
├── lib/             # Utilities and shared helpers
├── styles.css       # Tailwind v4 theme tokens and global styles
└── router.tsx       # Router configuration
```

Routing conventions are documented in [`src/routes/README.md`](src/routes/README.md).

## Deployment

The project is developed and deployed with [Lovable](https://lovable.dev).
Open the project in the Lovable editor and click **Publish** to ship changes to
the live URL above. Because the repo is two-way synced, pushing commits here
also updates the Lovable project.

You can also self-host: run `npm run build` and deploy the output to any host
that supports Node or edge runtimes (Cloudflare, Vercel, Netlify, Fly.io).

## Contributing

1. Fork the repository and create a branch: `git checkout -b feature/my-change`
2. Make your changes and run `npm run lint`
3. Open a pull request describing the change

Issues and feature requests are welcome.

---

Made with 💚 with the help of A.I.
