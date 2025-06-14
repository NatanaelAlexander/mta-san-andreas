# MTA San Andreas

A modern web application for MTA San Andreas, built with Astro and deployed on Cloudflare Pages.

[![Deployed on Cloudflare Pages](https://img.shields.io/badge/Deployed%20on-Cloudflare%20Pages-blue)](https://mta-san-andreas.pages.dev)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Package Manager**: [pnpm](https://pnpm.io)
- **Deployment**: [Cloudflare Pages](https://pages.cloudflare.com)
- **Domain**: [mta-san-andreas.pages.dev](https://mta-san-andreas.pages.dev)

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`           | Installs dependencies                            |
| `pnpm dev`               | Starts local dev server at `localhost:4321`      |
| `pnpm build`             | Build your production site to `./dist/`          |
| `pnpm preview`           | Preview your build locally, before deploying     |
| `pnpm astro ...`         | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help`   | Get help using the Astro CLI                     |

## 🚀 Deployment

This project is automatically deployed to Cloudflare Pages. Any push to the main branch will trigger a new deployment.

- **Production URL**: [mta-san-andreas.pages.dev](https://mta-san-andreas.pages.dev)
- **Build Command**: `pnpm build`
- **Build Output Directory**: `dist`

## 👀 Want to learn more?

Feel free to check [Astro's documentation](https://docs.astro.build) or jump into their [Discord server](https://astro.build/chat).
