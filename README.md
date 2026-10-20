<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="read.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">read.me.at</h1>

<p align="center"><strong>Read me, at length.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://read.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#screenshots">Screenshots</a> ·
  <a href="#built-with">Built with</a>
</p>

Writing gets lost when it is scattered across platforms that each own a slice of it. I built read.me.at as the one home for mine: blog posts, digital-garden notes, project write-ups and life updates as a full-stack software engineer working in React, Next.js and modern web technologies. It is made for reading, with full-text search, series and a reader mode, and you can follow along by RSS, newsletter, or comments on one me.at account.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="read.me.at at a glance: four collections, built for reading, search that reads bodies, follow along your way" width="880">
  </picture>
</p>

## Why read.me.at

| The usual blog | read.me.at |
| --- | --- |
| Posts only | Posts, notes, projects and life updates, each with its own index |
| Search that matches titles | Full-text search across article bodies, with snippets and highlighting |
| One feed for everything | One feed for everything, plus one per collection |
| Comments through a third-party widget | Threaded comments and reactions on the shared me.at account |

## Features

- **Four collections**: posts, notes, projects and life updates, each with its own index and a unified front page.
- **Article pages**: table of contents, multi-part series, previous and next navigation, and related posts.
- **Full-text search**: search across article bodies, with scored results, snippets and highlighting.
- **Comments and reactions**: threaded comments with reactions and reply notifications, using the shared me.at account.
- **Newsletter**: double opt-in subscribe, confirm and unsubscribe.
- **RSS feeds**: one feed for everything and one per collection.
- **Reader mode**: a distraction-free reading toggle.
- **Uses page**: the gear, editor and tools behind the work.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How read.me.at works: write, compile, publish, find, discuss" width="880">
  </picture>
</p>

Everything is written in MDX and compiled by Content Collections into typed documents, and release builds skip anything marked as a draft. Each collection gets its own index and feed, search covers article bodies rather than just titles, and comments and reactions use the same account as the rest of the family.

## Screenshots

<table>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/post-dark.png"><img src=".github/assets/post.png" alt="Blog posts and notes"></picture><br><sub>Blog posts and notes: search, sort and tag filters.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/notes-dark.png"><img src=".github/assets/notes.png" alt="Notes"></picture><br><sub>Notes: technical notes, quick tips and documentation snippets.</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/project-dark.png"><img src=".github/assets/project.png" alt="Projects"></picture><br><sub>Projects: my project write-ups alongside my public GitHub repositories.</sub></td>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/project--saas-tracking-dark.png"><img src=".github/assets/project--saas-tracking.png" alt="Project write-up"></picture><br><sub>Project write-up: an article page with its stats.</sub></td>
  </tr>
  <tr>
    <td width="50%"><picture><source media="(prefers-color-scheme: dark)" srcset=".github/assets/uses-dark.png"><img src=".github/assets/uses.png" alt="Uses"></picture><br><sub>Uses: the gear, editor and tools behind the work.</sub></td>
    <td width="50%"></td>
  </tr>
</table>

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
  <img src="https://img.shields.io/badge/MDX-Content%20Collections-525252?style=flat-square&logo=mdx&logoColor=white" alt="MDX with Content Collections">
  <img src="https://img.shields.io/badge/Drizzle-Postgres-737373?style=flat-square&logo=drizzle&logoColor=white" alt="Drizzle ORM and Postgres">
</p>

- Next.js 16 (App Router) and React 19
- TypeScript
- Tailwind CSS 4
- MDX compiled with Content Collections
- oRPC and TanStack Query
- Drizzle ORM and Postgres
- Better Auth (shared me.at account)

## Part of the me.at family

read.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
