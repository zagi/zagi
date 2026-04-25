# Hi, I'm Michał Zagalski 👋

**Senior Full-Stack Developer** · Warsaw, Poland · 10+ years
*Performance engineering · AI integration · Edge computing · Web3*

---

> **PageSpeed 100/100 Desktop · 95.6 Mobile · CLS 0.000** on a real-time SSR DEX explorer running on Cloudflare Workers.
> Wrote it up in [*The Road to PageSpeed 100*](https://medium.com/coinpaprika/the-road-to-pagespeed-100-part-1-foundation-server-side-wins-85-90-d367c1630de8) — a 3-part Medium series.

## Recent work

- **[DexPaprika](https://dexpaprika.com)** — Vue 3 → Nuxt 4 SSR migration on Cloudflare Workers. Owned the 8-phase PageSpeed program, Bootstrap → Tailwind v4 refactor (53% CSS reduction), 3-tier stale-while-revalidate cache with critical-CSS injection, and the visual + mobile UX rewrite (thumb-bar nav, swipe gestures, refactored right-drawer split into design-token components).

- **[GetName.pl](https://getname.pl)** — Premium `.pl` domain marketplace on Nuxt 4. Full NASK EPP registry integration, Solidity smart contracts on Polygon (`GNRegistry`, `GNMarketplace`, `GNToken` ERC-20, NFT domains), AI domain assistant (OpenAI), real-time auctions with anti-snipe, multi-payment (Stripe / Przelewy24 / crypto), SIWE auth, 40+ tables on PostgreSQL with Drizzle ORM and Better Auth.

- **[CoinPaprika](https://coinpaprika.com)** — Architecting the Next.js 15+ migration on Cloudflare Workers via OpenNext (Turbo monorepo, modular `api-client` / `i18n` / `types` / `ui` packages). Shipped the official PHP SDK v1.5 and `@coinpaprika/api-nodejs-client` v3.0.0 (21 new endpoints, native fetch, dual CJS/ESM, AbortSignal cancellation).

- **Multiple Next.js 15 + PayloadCMS sites on Cloudflare D1/R2** — DOMAR business platform (Claude API content pipeline, 120+ automated SEO scripts), LeoKlima HVAC (PL/EN/UA, Cloudflare Turnstile, lead-gen, JSON-LD), hob.com.pl roofing (Astro → Next.js 15, OpenAI, Framer Motion, next-intl).

## Open source

- **[`nask-epp-client`](https://github.com/zagi/nask-epp-client)** — Node.js client for the NASK EPP protocol (`.pl` domain registry).
- **[`browser-curl`](https://github.com/zagi/browser-curl)** — Bypass WAF 403s by mimicking Chrome 145 headers. MIT.
- **[`parallel-requests`](https://github.com/zagi/parallel-requests)** — Claude Code skill: detects sequential independent HTTP calls and refactors to parallel execution (Promise.all / asyncio.gather + 7 more languages).
- **[`@coinpaprika/api-nodejs-client`](https://github.com/coinpaprika/coinpaprika-api-nodejs-client) v3** & **CoinPaprika PHP SDK v1.5** — full API coverage, dual CJS/ESM, integration tests, GitHub Actions CI.

## Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue%203-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![Nuxt](https://img.shields.io/badge/Nuxt%204-00DC82?style=for-the-badge&logo=nuxt.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js%2015%2B-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-F05138?style=for-the-badge&logo=swift&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![PayloadCMS](https://img.shields.io/badge/PayloadCMS-000000?style=for-the-badge&logo=payloadcms&logoColor=white)

**Edge & Cloud**

![Cloudflare](https://img.shields.io/badge/Cloudflare%20Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![D1](https://img.shields.io/badge/D1-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![R2](https://img.shields.io/badge/R2-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Durable Objects](https://img.shields.io/badge/Durable%20Objects-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Databases & ORM**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=for-the-badge&logo=drizzle&logoColor=black)

**AI & Web3**

![Anthropic](https://img.shields.io/badge/Claude-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6366F1?style=for-the-badge&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Ethers.js](https://img.shields.io/badge/Ethers.js-2535A0?style=for-the-badge&logo=ethereum&logoColor=white)
![Viem](https://img.shields.io/badge/Viem-FFC517?style=for-the-badge&logoColor=black)
![WalletConnect](https://img.shields.io/badge/WalletConnect-3B99FC?style=for-the-badge&logo=walletconnect&logoColor=white)

**Tooling**

![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Speaking & writing

- **Conferences attended:** NuxtNation 2022 & 2024 · Vue.js Nation 2023 & 2025 · ViteConf 2024 · Vue.js DE 2024
- ***The Road to PageSpeed 100*** — 3-part Medium series on going from 85 → 100 on a real-time data app (CoinPaprika):
  - [Part 1: Foundation & Server-Side Wins (85→90)](https://medium.com/coinpaprika/the-road-to-pagespeed-100-part-1-foundation-server-side-wins-85-90-d367c1630de8)
  - [Part 2: Critical Rendering & CLS Battle (90→97)](https://medium.com/coinpaprika/the-road-to-pagespeed-100-part-2-critical-rendering-cls-battle-90-97-4b05150ce17a)
  - [The Final Push: How We Hit PageSpeed 100 on a Real-Time Data Application](https://medium.com/coinpaprika/the-final-push-how-we-hit-pagespeed-100-on-a-real-time-data-application-9a8a9c2b8a19)

## Reach me

- 📫 **zagalski@protonmail.com**
- 🔗 [LinkedIn](https://www.linkedin.com/in/micha%C5%82-zagalski-b371a0196)
- 🐙 [github.com/zagi](https://github.com/zagi)

## Stats

<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=zagi&show_icons=true&hide_border=true&count_private=true&theme=default" alt="zagi's GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zagi&layout=compact&hide_border=true&langs_count=8&theme=default" alt="zagi's top languages" />
</a>

## Off-keyboard

2 dogs, 1 cat, an aquarium with snails. 3D printer humming. Sailing when there's wind. Free-living cat care volunteer in Warsaw since 2016.

If something I made helped you, you can [☕ buy me a coffee](https://buycoffee.to/zagi14).
