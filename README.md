# mochammadkevin.github.io

Personal portfolio and blog, built with [Astro](https://astro.build/) and deployed via GitHub Pages.

Live at: **https://mochammadkevin.github.io**

---

## About

This site includes:
- **Home** — brief introduction
- **Projects** — showcase of personal and professional work
- **Writings** — links to articles published on Medium

> **Note:** This repository contains only the compiled static output. The Astro source project is maintained separately and its `/dist` contents are copied here for deployment.

---

## Viewing Locally

Clone the repo and serve it with any static file server:

```bash
git clone https://github.com/mochammadkevin/mochammadkevin.github.io.git
cd mochammadkevin.github.io
```

Then pick one of:

```bash
# Python (no install needed)
python3 -m http.server 8000

# Node.js
npx serve

# or
npx http-server
```

Open `http://localhost:8000` in your browser.

---

## Deployment

This repo is deployed automatically via GitHub Pages — pushing to `main` publishes the site.

The manual workflow is:
1. Make changes in the source Astro project
2. Run `astro build` to generate the `/dist` folder
3. Copy `/dist` contents into this repository
4. Commit and push to `main`

---

## Tech Stack

| Tool                                     | Purpose                |
| ---------------------------------------- | ---------------------- |
| [Astro](https://astro.build/)            | Static site generator  |
| [Tailwind CSS](https://tailwindcss.com/) | Styling                |
| TypeScript                               | Type-safe scripting    |
| GitHub Pages                             | Hosting                |

---

## Features

- Dark mode toggle (persisted via `localStorage`)
- Fully responsive layout
- Paginated projects listing
- Zero JavaScript frameworks at runtime (Astro islands)
