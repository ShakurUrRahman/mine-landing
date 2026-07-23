# Mine Landing

A Next.js landing page for **Md. Shakurur Rahman**'s business portfolio — services, work samples, and contact — built as the Week 1 capstone for the **FE-01 AI Engineering** track.

## Who this is for

- **Visitors & clients** — A public marketing site to learn about the business and get in touch.
- **Course evaluators** — Demonstrates progress on the FE-01 AI-assisted development capstone.
- **Contributors** — Solo project for now; issues and suggestions welcome.

## What this is

A frontend-focused landing page built with:

- **Next.js** (App Router)
- **React**
- **TypeScript**
- **Tailwind CSS**
- **npm** as the package manager

> **Note:** Express is not part of this project. The backend, if needed later, will use Next.js API routes or server actions — not a separate Express server.

## Status

🚧 **In progress** — Week 1 of FE-01 AI Engineering track.

The repository is initialized (README, LICENSE, tooling config), but the **Next.js app scaffold is not set up yet**. There is no `package.json` or runnable app at this stage.

### Roadmap

| Week | Goal |
|------|------|
| 1 | Repo setup, README, project conventions |
| 2 | Next.js scaffold, base layout, hero section |
| 3 | Services / portfolio sections |
| 4 | Contact form, polish, deploy to Vercel |

## Getting started

### Prerequisites

- **Node.js** 20 or later
- **npm** (comes with Node.js)

### Setup (once the Next.js scaffold exists)

```bash
git clone https://github.com/ShakurUrRahman/mine-landing.git
cd mine-landing
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Scripts (expected after scaffold)

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm start` | Run the production server |
| `npm run lint` | Run ESLint |

### Environment variables

Copy `.env.example` to `.env.local` and fill in any required values once they are defined.

## Project structure (planned)

```
mine-landing/
├── app/              # Next.js App Router pages and layouts
├── components/       # Reusable UI components
├── public/           # Static assets
└── ...
```

## Conventions

- Functional components with **PascalCase** filenames
- **Named exports** preferred over default exports
- Commits follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `chore:`, `docs:`)

## Links

- **Live demo:** _Coming soon_
- **Course:** FE-01 AI Engineering track

## License

MIT — see [LICENSE](LICENSE).
