<div align="center">

# Rahul Mehta

Frontend and systems developer. Tauri + Rust desktop apps, Chrome extensions, reactive UIs.

B.Tech, Electrical & Electronics — ADGIPS (GGSIPU), New Delhi · Delhi NCR / remote

<p align="center">
  <a href="https://rahulmehta53.github.io/rahulmehta_fyi/"><img src="https://img.shields.io/badge/Portfolio-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/rahulmehtadev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
  <a href="https://x.com/rahuloncode"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>&nbsp;
  <a href="mailto:rahulmehta5432@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

</div>

---

Most of what I ship is small and local-first: desktop apps that idle under 35MB of RAM, extensions that survive Chrome killing the service worker, new-tab pages that render in under 50ms. I'd rather get the IPC boundary and the cold start right than add another feature.

- **Working on** — [10kTasks](https://www.10ktasks.com) (Rust + Tauri desktop, mirrored by a Next.js web app) and a handful of Manifest V3 extensions
- **Shipped** — 10+ MV3 extensions, one of them on the Chrome Web Store
- **Open to** — frontend, desktop systems, or full-stack roles in Noida / Delhi NCR or remote

---

## Projects

### [10kTasks](https://www.10ktasks.com) — task manager for desktop and web

`Rust` · `Tauri` · `Next.js` · `React` · `TypeScript` · `serde`

Ships as a ~12MB binary that idles under 35MB of RAM, roughly a tenth of what the same UI costs in Electron. Disk I/O, local telemetry, and tray updates run in async Rust command handlers instead of blocking the window. The desktop and [web](https://10ktasks.com) builds stay in sync on hierarchical tasks and focus timers.

### [Blockit](https://github.com/rahulmehta53/Blockit-public) — time blocking in the Chrome sidebar

`TypeScript` · `Manifest V3` · `SidePanel API` · `chrome.storage` · `Tailwind CSS`

A daily planner that sits in the browser sidebar, [published on the Chrome Web Store](https://chromewebstore.google.com/detail/blockit-time-blocking/hgoeelahkegphefndkijgcdifennoacl). The awkward part of MV3 is that the service worker is disposable, so block reminders are scheduled through alarms and state is rehydrated from `chrome.storage.local` after every wake.

### [GlideScape](https://glidescape.vercel.app) — offline-first productivity workspace

`React` · `TypeScript` · `Zustand` · `Dexie` · `Supabase` · `Tailwind CSS`

A focus timer, multi-view calendar, and reflection journal, [live on Vercel](https://glidescape.vercel.app). Everything writes to IndexedDB first and syncs to Supabase auth/storage behind it, so the app keeps working with the network off.

### [Vantage](https://github.com/rahulmehta53/vantage-newtab) — new tab dashboard

`SolidJS` · `WXT` · `Kobalte` · `TypeScript` · `Tailwind CSS` · `Bun`

Under 50ms to first render on an empty tab, using SolidJS fine-grained signals — the reactivity compiles down, so there's almost no runtime DOM overhead to pay for. WXT builds the Chromium and Firefox packages from one codebase.

### YouTube Notes Taker — transcript to Markdown, in the side panel

`JavaScript` · `Manifest V3` · `SidePanel API` · `DOM MutationObserver` · `Markdown`

One click pulls the active video's transcript and timestamps. A content script watches the DOM for the transcript to load, parses timestamps as it mutates, and messages them to the side panel, which compiles a Markdown note.

---

## Stack

**Frontend** — TypeScript, JavaScript, React 19, Next.js, SolidJS, Astro, Tailwind CSS, HTML/CSS
**Desktop** — Rust, Tauri v2, Cargo
**Extensions** — Manifest V3, SidePanel API, service workers, WXT, `chrome.storage`
**Backend & infra** — Node.js, Bun, Python 3, Supabase, Google Cloud, IndexedDB, Git

---

## GitHub

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rahulmehta53&theme=default" alt="Contribution summary" />

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=rahulmehta53&theme=default&utcOffset=5.5" alt="Commits by hour" />

</div>

---

## Elsewhere

[rahulmehta53.github.io/rahulmehta_fyi](https://rahulmehta53.github.io/rahulmehta_fyi/) · [LinkedIn](https://www.linkedin.com/in/rahulmehtadev/) · [X](https://x.com/rahuloncode) · [rahulmehta5432@gmail.com](mailto:rahulmehta5432@gmail.com)

Happy to talk about desktop performance, extension architecture, or a role on your team.
