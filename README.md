<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img width="100%" alt="Saif Ibrahim, Full-Stack Developer and Product Builder" src="./assets/banner-light.svg">
</picture>

<p align="center">
  <a href="https://saifibrahim.vercel.app"><img src="https://img.shields.io/badge/Portfolio-saifibrahim.vercel.app-18181B?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:saif.ibrahim3070@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20touch-18181B?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<br>

## About

I build complete products: I scope the idea, design the interface, model the data, write the backend logic and ship it to production. Most of my work is full-stack TypeScript on React and Supabase, with the database doing the heavy lifting: business rules, permissions and money operations live in PostgreSQL, not in the browser.

I work on my own products and on client platforms, from offline-first apps to membership stores with their own admin panels.

<table>
  <tr>
    <td width="33%" valign="top"><b>Focus</b><br><sub>Full-stack web applications, e-commerce and admin dashboards</sub></td>
    <td width="33%" valign="top"><b>Approach</b><br><sub>Understand the problem, plan the data, then build frontend, backend and integrations as one system</sub></td>
    <td width="33%" valign="top"><b>Currently</b><br><sub>Building and maintaining production platforms alongside my own products</sub></td>
  </tr>
</table>

<br>

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>FlowCash</h3>
      <sub><code>PERSONAL PRODUCT</code> &nbsp; <code>FULL-STACK</code></sub>
      <p>An offline-first personal finance PWA for expenses, income, budgets, savings goals, debts and subscriptions across several payment sources. Installs on Android as a real app.</p>
      <p><b>My role</b><br>Designed and built the whole product, from UI to database and deployment.</p>
      <p><b>Highlights</b><br>Every money operation runs through atomic PostgreSQL functions, so balances stay correct under simultaneous updates. Row-Level Security on all user data, a custom service worker for offline use, CSV/PDF export and backup.</p>
      <p><sub>React 19 · TanStack Start · TypeScript · Supabase · PostgreSQL · Tailwind CSS</sub></p>
      <p><a href="https://flow-cash.vercel.app">Live app</a> &nbsp;·&nbsp; <a href="https://saifibrahim.vercel.app/projects/flowcash">Case study</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>Blackframe Studio</h3>
      <sub><code>CLIENT PLATFORM</code> &nbsp; <code>FULL-STACK</code></sub>
      <p>An asset platform for DaVinci Resolve editors: free plugins, LUTs, footage and sound, plus a paid Studio membership with its own store, pricing, downloads and customer accounts.</p>
      <p><b>My role</b><br>Developer of the platform. Built the web app, customer accounts, membership checkout integration, protected file delivery and the admin control room the team uses to run the site.</p>
      <p><b>Highlights</b><br>Access and download rules enforced in the database, not the UI. Role-based admin panel, team-editable content and page sections, server-side rendering with full SEO.</p>
      <p><sub>React 19 · TanStack Start · TypeScript · Supabase · Cloudflare Workers · Tailwind CSS · Vitest</sub></p>
      <p><a href="https://blackframe.in">Live site</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Farely</h3>
      <sub><code>PERSONAL PRODUCT</code> &nbsp; <code>OFFLINE-FIRST</code></sub>
      <p>A transit wallet for tracking Abu Dhabi Hafilat bus card balances. Record a trip in two taps, see the expected balance, and stay in sync across devices with or without a connection.</p>
      <p><b>My role</b><br>Designed and built it end to end: product scope, UI/UX, data model, sync architecture, database security and deployment.</p>
      <p><b>Highlights</b><br>Balances are always derived from an auditable ledger, never stored. A persistent outbox and sync engine handle offline edits, conflicts and multi-device IDs.</p>
      <p><sub>React 19 · TanStack Start · TypeScript · Supabase (Postgres, Auth, Realtime) · Zod</sub></p>
      <p><a href="https://farely-hafelat.vercel.app">Live app</a> &nbsp;·&nbsp; <a href="https://saifibrahim.vercel.app/projects/farely">Case study</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>S &amp; E Fashion Store</h3>
      <sub><code>E-COMMERCE</code> &nbsp; <code>SHOPIFY</code></sub>
      <p>An online fashion store with a modern, fashion-focused identity and a simple shopping flow, from browsing collections to product details and checkout.</p>
      <p><b>My role</b><br>Built the storefront structure, UI and responsive layout on a customized Shopify theme.</p>
      <p><b>Highlights</b><br>A distinct visual identity on top of Shopify's theme system, kept consistent across collections, product pages and navigation on every screen size.</p>
      <p><sub>Shopify · HTML · CSS · JavaScript</sub></p>
      <p><a href="https://saifibrahim.vercel.app/projects/se-fashion-store">Case study</a></p>
    </td>
  </tr>
</table>

<p align="center"><sub>Client work lives in private repositories. Descriptions cover my role and the public product only. More on my <a href="https://saifibrahim.vercel.app/#projects">portfolio</a>.</sub></p>

<br>

## Full-Stack &amp; Backend

The part of the work I care about most is what happens behind the interface.

<table>
  <tr>
    <td width="50%" valign="top"><b>Logic in the database</b><br><sub>Business rules, balances and access checks as PostgreSQL functions, triggers and Row-Level Security, so they hold no matter which client calls them.</sub></td>
    <td width="50%" valign="top"><b>Auth and permissions</b><br><sub>Customer accounts and role-based admin panels, enforced on the server rather than hidden in the UI.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><b>Offline-first data</b><br><sub>Local-first interfaces with queued changes, background sync and conflict handling.</sub></td>
    <td width="50%" valign="top"><b>Payments and commerce</b><br><sub>Hosted checkout integrations with verified webhooks and server-side access decisions.</sub></td>
  </tr>
  <tr>
    <td width="50%" valign="top"><b>Server functions and delivery</b><br><sub>Edge and server functions, protected file downloads and admin tooling for non-technical teams.</sub></td>
    <td width="50%" valign="top"><b>Production details</b><br><sub>Server-side rendering, SEO and structured data, bilingual English/Arabic (RTL), deployment on Vercel and Cloudflare.</sub></td>
  </tr>
</table>

<br>

## Tech Stack

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts,js,html,css,react,vite,tailwind&theme=dark&perline=7">
    <img alt="TypeScript, JavaScript, HTML, CSS, React, Vite, Tailwind CSS" src="https://skillicons.dev/icons?i=ts,js,html,css,react,vite,tailwind&theme=light&perline=7">
  </picture>
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nodejs,supabase,postgres,mongodb,deno,vercel,cloudflare,git,github,vitest&theme=dark&perline=10">
    <img alt="Node.js, Supabase, PostgreSQL, MongoDB, Deno, Vercel, Cloudflare, Git, GitHub, Vitest" src="https://skillicons.dev/icons?i=nodejs,supabase,postgres,mongodb,deno,vercel,cloudflare,git,github,vitest&theme=light&perline=10">
  </picture>
</p>

<table>
  <tr>
    <td><b>Frontend</b></td>
    <td><sub>TypeScript · JavaScript · React · TanStack Start · Vite · Tailwind CSS · shadcn/ui · HTML · CSS</sub></td>
  </tr>
  <tr>
    <td><b>Backend &amp; Data</b></td>
    <td><sub>Supabase · PostgreSQL · SQL functions &amp; RLS · Edge Functions · Node.js · REST APIs · MongoDB</sub></td>
  </tr>
  <tr>
    <td><b>Platforms &amp; Tools</b></td>
    <td><sub>Vercel · Cloudflare Workers · Shopify · Git · GitHub · Vitest</sub></td>
  </tr>
</table>

<br>

## GitHub Activity

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=saiiff25&show_icons=true&hide_border=true&hide_rank=true&bg_color=00000000&title_color=F0F6FC&text_color=9198A1&icon_color=3FB950">
    <img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=saiiff25&show_icons=true&hide_border=true&hide_rank=true&bg_color=00000000&title_color=1F2328&text_color=59636E&icon_color=1A7F37">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=saiiff25&hide_border=true&background=00000000&ring=3FB950&fire=3FB950&currStreakNum=F0F6FC&sideNums=F0F6FC&currStreakLabel=F0F6FC&sideLabels=9198A1&dates=9198A1&stroke=30363D">
    <img height="150" alt="GitHub streak" src="https://streak-stats.demolab.com?user=saiiff25&hide_border=true&background=00000000&ring=1A7F37&fire=1A7F37&currStreakNum=1F2328&sideNums=1F2328&currStreakLabel=1F2328&sideLabels=59636E&dates=59636E&stroke=D1D9E0">
  </picture>
</p>

<sub>Most of my work lives in private repositories, so public numbers show only part of it.</sub>

<br>

## Get in Touch

Have a product to build or a platform that needs a developer? I'm open to projects and collaborations.

<p>
  <a href="https://saifibrahim.vercel.app"><b>Portfolio</b></a> &nbsp;·&nbsp;
  <a href="mailto:saif.ibrahim3070@gmail.com"><b>saif.ibrahim3070@gmail.com</b></a>
</p>
