<div align="center">

# MijuDrama

**A modern platform for discovering, tracking, rating, and discussing Asian drama, donghua, and manhua.**

[![Next.js](https://img.shields.io/badge/framework-Next.js_15-000000?logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![React](https://img.shields.io/badge/ui-React_19-61DAFB?logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/language-TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Tailwind CSS](https://img.shields.io/badge/styling-Tailwind_CSS_4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Prisma](https://img.shields.io/badge/orm-Prisma_6-2D3748?logo=prisma&logoColor=white)](https://www.prisma.io)
[![MongoDB](https://img.shields.io/badge/database-MongoDB_Atlas-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com/atlas)
[![better-auth](https://img.shields.io/badge/auth-better--auth-000000)](https://www.better-auth.com)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
![Status](https://img.shields.io/badge/status-beta-orange)

### [🌐 mijudrama.com](https://mijudrama.com)

</div>

---

**MijuDrama** is a modern Asian-entertainment database and editorial blog for **discovering, tracking, rating, and discussing** Chinese dramas, **donghua** (Chinese animation), **manhua** (Chinese comics), films, and the people behind them. Browse curated listings, build a watchlist, rate and review titles, follow live next-episode countdowns, join the community forum, and read in-depth editorial coverage.

> 📖 This is a **public showcase** of the project. The application source code is private.

## ✨ Features

- **Catalog** — dramas, movies, variety, donghua & manhua, with sectioned listings (Trending / Currently Airing / Recently Added / Top Rated / Upcoming) and rich filter/sort.
- **Track** — personal watchlist (want / watching / watched), 1–10 ratings + written reviews, and custom public lists.
- **Donghua & Manhua** — AniList-powered directory with **live next-episode countdowns**, legal "where to watch / where to read" links, seasons, staff, characters, and recommendations.
- **Community** — threaded comments, a discussion **forum**, character search, and per-title community stats.
- **Editorial blog** — a custom Lexical rich-text editor, drama review posts, and people/actor profiles with filmographies.
- **Polish** — dark mode, SEO-first rendering (ISR, structured data, sitemaps), and an accessible, responsive UI.

## 🛠 Tech Stack

| Area | Technology |
|---|---|
| Framework | Next.js 15 (App Router, Turbopack) · React 19 |
| Language | TypeScript |
| Styling | Tailwind CSS 4 · Radix UI |
| Database | Prisma 6 + MongoDB (Atlas) |
| Auth | better-auth (email/password, Google, 2FA, admin) |
| Infra | Upstash Redis · Cloudinary + Cloudflare R2 · Resend |
| Testing | Vitest · Playwright + Lighthouse |
| Data | TMDB · AniList · Wikidata |

## 📸 Screenshots

### Home

![Home](assets/screenshots/home.png)

### Catalog

Every content type has a directory **listing** and a rich **detail** page.

#### Dramas

| Listing | Detail — _Let's Fight (来战)_ |
|---|---|
| ![Drama listing](assets/screenshots/drama-list.png) | ![Drama detail](assets/screenshots/drama-detail.png) |

#### Movies

| Listing | Detail — _Big World (2024)_ |
|---|---|
| ![Movie listing](assets/screenshots/movie-list.png) | ![Movie detail](assets/screenshots/movie-detail.png) |

#### Variety Shows

| Listing | Detail — _Keep Running (奔跑吧)_ |
|---|---|
| ![Variety listing](assets/screenshots/variety-list.png) | ![Variety detail](assets/screenshots/variety-detail.png) |

#### Donghua

| Listing | Detail — _Heaven Official's Blessing_ |
|---|---|
| ![Donghua listing](assets/screenshots/donghua-list.png) | ![Donghua detail](assets/screenshots/donghua-detail.png) |

#### Manhua

| Listing | Detail — _Grandmaster of Demonic Cultivation_ |
|---|---|
| ![Manhua listing](assets/screenshots/manhua-list.png) | ![Manhua detail](assets/screenshots/manhua-detail.png) |

### People & Characters

| People listing | Person — _Ju Jingyi_ |
|---|---|
| ![People listing](assets/screenshots/people-list.png) | ![Person detail](assets/screenshots/person-detail.png) |

| Character search | Character — _Wuxian Wei_ |
|---|---|
| ![Characters listing](assets/screenshots/characters-list.png) | ![Character detail](assets/screenshots/character-detail.png) |

### Community & Editorial

| Forum | Updates | Blog |
|---|---|---|
| ![Forum](assets/screenshots/forum.png) | ![Updates](assets/screenshots/updates.png) | ![Blog](assets/screenshots/blog.png) |

<!-- Screenshots live in assets/screenshots/ — see that folder's README for the full list. -->

## 🤝 Contributing

MijuDrama is in open beta — you can try it live at **[mijudrama.com](https://mijudrama.com)**. The application code is private, so what moves the project forward most is real-world feedback from people who use it.

Here's how you can help:

- 🐞 **Hit a glitch?** Flag it on the [issue tracker](https://github.com/bunseueng/mijudrama/issues).
- 🎬 **Catalog gap?** Ask for a drama, donghua, or manhua to be added.
- 💡 **Bright idea?** Pitch a feature or a tweak you'd love to see.

Every report, request, and suggestion genuinely shapes what gets built next.

## ☕ Support

MijuDrama is a solo project, built and run in spare hours. If it brightens your watchlist, a coffee helps keep the servers humming and the late-night commits flowing.

[![Buy me a coffee on Ko-fi](https://img.shields.io/badge/Buy_me_a_coffee-Ko--fi-FF5E5B?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/mijudrama)

## 📄 License

<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-0AA06E?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="MIT License" /></a>

Open-sourced under the **MIT License** — free to study, fork, and build upon.
Copyright © 2026 [**bunseueng**](https://github.com/bunseueng).

---

<div align="center">

Crafted with ☕ &amp; late nights by **[bunseueng](https://github.com/bunseueng)**

</div>
