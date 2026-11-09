<div align="center">

# Martin Atanasov

### Product engineer · Web · Windows · Android

**I ship finished software.** Tested, documented, released — not demos.
From a university-admission platform used by Bulgarian students to native
Windows utilities and fully offline, on-device AI tools.

<br>

[![Portfolio](https://img.shields.io/badge/Portfolio-martin--atanasov.netlify.app-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://martin-atanasov.netlify.app/)
[![Email](https://img.shields.io/badge/Email-matanasov573%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matanasov573@gmail.com)
[![Location](https://img.shields.io/badge/Pleven-Bulgaria-2ECC71?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Open to work](https://img.shields.io/badge/Open_to-Opportunities-8A2BE2?style=for-the-badge&logo=handshake&logoColor=white)](mailto:matanasov573@gmail.com)

</div>

---

## About

I build complete products across three platforms. A typical project of mine ships with
a unit-tested core, written architecture decisions, a manual test matrix, performance
budgets measured against real numbers, and a tagged release people can actually download.

Two principles run through almost everything I make:

- **Local-first and private.** No telemetry, no accounts, no cloud round-trip. `FocusLens`
  stores everything in a local SQLite file, `FlowLocal` runs Whisper and an LLM entirely
  offline, `ShotKeep` ships without the internet permission so it *cannot* upload, and
  `Nowdrop` moves files over your own Wi-Fi.
- **Correctness you can prove.** Pure, deterministic cores separated from I/O so the rules
  can be tested — a 102-test rules engine in `Belot`, 62 tests behind the `FocusLens` agent,
  on-device verification gates in `ShotKeep`.

---

## Flagship Work

### 🎓 УниПът — University Admission Platform
[![Live](https://img.shields.io/badge/Live-uniput.eu-success?style=flat-square&logo=netlify&logoColor=white)](https://uniput.eu/)
[![Repo](https://img.shields.io/badge/Source-Uni--put-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/Uni-put)

A free platform helping Bulgarian students calculate their admission score, find a career
direction, and compare universities in one place.

- **Score calculator** that applies each programme's official formula and automatically
  selects the best-scoring grade for every slot
- **Career advisor** — RIASEC personality assessment in 30 / 60 / 90-question versions,
  mapped to matching programmes via the O\*NET database
- **University & dormitory search** with filtering by institution, faculty, programme and city,
  plus favourites, grade management, user profiles and an admin data-management role

`React 19` · `Vite 6` · `React Router 7` (fully lazy-loaded) · `Tailwind CSS 4 + DaisyUI` ·
`Framer Motion` · `Three.js / R3F` · `Supabase (Postgres + Auth + Storage)` · `Vitest`

---

### ♠️ Белот онлайн — Real-Time Multiplayer Card Game
[![Repo](https://img.shields.io/badge/Source-belot-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/belot)
![Tests](https://img.shields.io/badge/engine_tests-102-brightgreen?style=flat-square)

Four-player Bulgarian Belot in the browser, built on a strict **authoritative-server /
pure-engine** architecture: the client only renders state and sends intents, so the rules
cannot be cheated client-side.

- **Cheat-proof by design.** The server validates every action against a pure rules engine
  and emits one `PlayerView` per seat with hidden hands masked — no card ever leaks over the wire
- **Complete official ruleset** — bidding (♣♦♥♠/NT/AT), contra/re-contra, capot,
  terca/kvarta/quinta, carrés, belot, suspended-hand carry, divide-by-10 scoring
- **102 scenario-driven engine tests** covering rankings, legal moves, announcement edge cases,
  scoring, and full deterministic hand replays from fixed seeds
- **Heuristic bots** that evaluate each contract against their hand, with tunable randomness
- Bilingual BG/EN UI with Cyrillic-aware typography, mobile-responsive across three breakpoints

`TypeScript` monorepo (shared / engine / server / client) · `Fastify + Socket.IO` · `React + Vite` ·
`Zustand` · `Framer Motion` · `Docker` (47 KB ESM server bundle) · `Render + Netlify`

---

### 🪟 EdgeStage — Stage Manager for Windows
[![Release](https://img.shields.io/github/v/release/Martin-Atanasov123/EdgeStage?style=flat-square&label=release&color=60CDFF)](https://github.com/Martin-Atanasov123/EdgeStage/releases/latest)
[![CI](https://img.shields.io/github/actions/workflow/status/Martin-Atanasov123/EdgeStage/ci.yml?style=flat-square&label=CI)](https://github.com/Martin-Atanasov123/EdgeStage/actions)
[![Repo](https://img.shields.io/badge/Source-EdgeStage-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/EdgeStage)

A window switcher driven by **live previews** at the edge of your screen. Rest the pointer at
the edge or hit a hotkey, click a preview, and it zooms into the real window.

- Real **DWM thumbnails**, not screenshots — a video keeps playing, a terminal keeps scrolling
- **Exposé view**: every window at once in an adaptive grid, previews flying out of the real windows
- Opens **without stealing focus**, so you keep typing; ignored during window drags and full-screen apps
- Search-as-you-type, group-by-app, close-from-card, hidden-app rules, hold-to-switch
- Multi-monitor and DPI aware · full theming (accent, density, radius, motion) applied live
- **No network, no telemetry, no admin rights** — ~0.1% of one CPU core idle

`C# / .NET 10` · `WPF` · `Win32 + DWM interop` · `PowerShell` · GitHub Actions CI

---

### 📡 Nowdrop — Cross-Device File Transfer
[![Site](https://img.shields.io/badge/Site-nowdrop.netlify.app-success?style=flat-square&logo=netlify&logoColor=white)](https://nowdrop.netlify.app/)
[![Release](https://img.shields.io/github/v/release/Martin-Atanasov123/nowdrop-downloads?style=flat-square&label=preview&color=orange)](https://github.com/Martin-Atanasov123/nowdrop-downloads/releases/latest)

AirDrop-style transfer between **Mac, Windows PC and Android** — files, links, text and
clipboard, over your own Wi-Fi. Shipped as signed-pending installers for all three platforms,
iterated across **22 preview releases**.

---

### 🔒 FocusLens — Privacy-First Screen Time Tracker
[![Release](https://img.shields.io/github/v/release/Martin-Atanasov123/FocusLens?style=flat-square&label=release&color=blue)](https://github.com/Martin-Atanasov123/FocusLens/releases/latest)
[![Repo](https://img.shields.io/badge/Source-FocusLens-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/FocusLens)
![Tests](https://img.shields.io/badge/agent_tests-62-brightgreen?style=flat-square)

Three clients, one local database, **zero cloud**. A tray agent tracks active-window time on
Windows, a Chrome MV3 extension adds per-domain browser time, and an Android app adds phone usage —
all landing in one local SQLite file behind an HTML dashboard. No accounts, no uploads.

- The extension sends **only hostnames, never full URLs**, and only to `127.0.0.1`, buffering
  locally while the agent is offline
- The Android side doubles as a standalone app blocker enforcing daily limits via an always-on
  foreground service
- Paired by local token / QR; ships with architecture and tech-decision records

`Python` (tray agent, 1 Hz sampler, Flask, PyInstaller) · `TypeScript` · `Chrome MV3` ·
`Expo / React Native` · `Kotlin` · `SQLite` · `Vitest + pytest`

---

### 🎙️ FlowLocal — Offline Voice-to-Text
[![Repo](https://img.shields.io/badge/Source-Voice--to--text-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/Voice-to-text)

Hold CapsLock → speak → release, and cleaned-up text is pasted into whatever app has focus.
**100% offline**: Whisper for recognition, a local LLM via Ollama for cleanup.

- **Hardware-adaptive setup** — detects your GPU and pulls cleanup models sized to actual VRAM;
  Whisper re-checks free VRAM at every startup and picks the best model that fits
- **Rewrite mode** — select text anywhere, press `Ctrl+CapsLock`, pick Professional / Friendly /
  Shorter / Longer / Email / Fix grammar; works on any text in any app
- **Command mode** — dictate an instruction and it writes the requested text for you
- Bilingual EN/BG, auto-selected from your current keyboard layout

`Python` · `Whisper` · `Ollama` · `PowerShell` bootstrap · Windows tray app

---

### 😀 QuickEmoji — Hotkey Emoji Insertion
[![Repo](https://img.shields.io/badge/Source-QuickEmoji-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/QuickEmoji)

Press `Win+Shift+E` anywhere, type a word, press Enter — the best emoji appears where you were
typing, via Unicode injection with a clipboard fallback for elevated targets.

Built against explicit **performance budgets**, measured rather than assumed:

| Metric | Budget | Measured |
|---|---|---|
| Search core per query | ≤ 5 ms (p95) | ≈ 0.10 ms warm |
| Catalog load | ≤ 150 ms | 26–56 ms (asserted in CI) |
| Enter → emoji in target app | ≤ 150 ms | ≈ 2 ms |
| Cold start → tray ready | ≤ 1.5 s | ≈ 0.69 s |
| Idle CPU | 0% — no polling | 0% (no timers while hidden) |

Fuzzy multi-language search, per-app insertion overrides, skin-tone preference, font-capability
filtering, and a diagnostics export.

`C# / .NET 10` · `Windows App SDK` · `WinUI / XAML` · global hotkeys & input injection

---

### 📱 ShotKeep — On-Device Screenshot Triage
[![Repo](https://img.shields.io/badge/Source-No--ScreenShot-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/No-ScreenShot)

Android app that catches each new screenshot and offers **Keep / Delete / Later** straight from a
heads-up notification, classifying it on-device. **No internet permission** — it cannot upload,
even by mistake.

Validated through a formal feasibility gate and per-milestone device verification on real
MIUI/HyperOS hardware: live detection via a foreground-service `ContentObserver`, survival across
service death and reboot, catch-up recovery with a watermark, and a correction loop that records
every misclassification so the classifier is tuned from real data instead of self-agreeing fixtures.

`Kotlin` · `Jetpack` · `MediaStore` · foreground services · Gradle KTS

---

<details>
<summary><b>More projects</b> — portfolio, e-commerce, games & experiments</summary>

<br>

| Project | What it is | Stack |
|---|---|---|
| [**Portfolio**](https://martin-atanasov.netlify.app/) | My personal site | `TypeScript` `React` `CSS` |
| [**MarketPlace**](https://github.com/Martin-Atanasov123/MarketPlace) | Full-stack marketplace — SoftUni defence project | `JavaScript` `Node` `Express` |
| [**EngeleBlur**](https://github.com/Martin-Atanasov123/EngeleBlur) | Blurs and darkens the screen when the laptop lid angle drops, estimated from the webcam | `Python` `OpenCV` |
| [**Chess**](https://martin-atanasov123.github.io/Chess-Game/) | Browser chess with full move legality | `JavaScript` |
| [**Rubik's Cube**](https://github.com/Martin-Atanasov123/Rubik-Cube) | Interactive 3D cube | `TypeScript` |
| [**Quiz Game**](https://martin-atanasov123.github.io/Quiz-Game/) · [**Millionaire**](https://martin-atanasov123.github.io/Who-Wants-to-Be-a-Millionaire/) | Quiz engines with scoring & lifelines | `JavaScript` |
| [**Puzzle**](https://martin-atanasov123.github.io/Puzzel/) · [**Matching**](https://martin-atanasov123.github.io/Matching-game/) · [**Tic-Tac-Toe**](https://github.com/Martin-Atanasov123/tic-tac-toe) | Logic & memory games | `JavaScript` |
| [**On-Screen Keyboard**](https://martin-atanasov123.github.io/Keyboard/) | Virtual keyboard with live input | `JavaScript` |
| [**Restaurant Menu**](https://martin-atanasov123.github.io/Restaurant-menu/) · [**Knives Site**](https://martin-atanasov123.github.io/knives-site/) | Early client-style sites | `HTML` `CSS` `JS` |

</details>

---

## Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-2D3748?style=for-the-badge&logo=react&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socket.io&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

**Desktop & Mobile**

![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF_/_WinUI-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Jetpack](https://img.shields.io/badge/Android_Jetpack-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

**AI & Local ML**

![Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**Testing & Tooling**

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

---

## How I Work

| | Practice | In the code |
|---|---|---|
| 🧪 | **Pure cores, tested as contracts** | `Belot`'s engine has no `Date.now()`, no I/O, no randomness outside a seeded `mulberry32` — so 102 tests assert *scoring behaviour*, not implementation, and refactors stay safe |
| 📐 | **Decisions written down** | `ARCHITECTURE.md`, `TECH_DECISIONS.md`, `DECISIONS.md` and `SPEC.md` live beside the code, with trade-offs stated |
| 📊 | **Budgets, measured** | Performance targets are published with measured numbers — including the ones I **missed** and why |
| 🔬 | **Verified on real hardware** | Feasibility gates and per-milestone device verification on an actual phone, because fixtures written by the rule-author agree with themselves by construction |
| 🚢 | **Tagged releases** | Versioned builds, changelogs and installers, not just a `main` branch |
| 🔐 | **Privacy as architecture** | Omit the permission, bind to `127.0.0.1`, send hostnames instead of URLs — enforced structurally, not promised in a policy |
| 🤖 | **AI-assisted velocity** | Agentic workflows for prototyping and review, with the engineering rigour above as the guard rail |

---

## GitHub Activity

<div align="center">

![Followers](https://img.shields.io/github/followers/Martin-Atanasov123?style=for-the-badge&logo=github&logoColor=white&color=0a0e17&labelColor=161b22)
![Stars](https://img.shields.io/github/stars/Martin-Atanasov123?style=for-the-badge&logo=github&logoColor=white&color=0a0e17&labelColor=161b22)
![Profile views](https://komarev.com/ghpvc/?username=Martin-Atanasov123&style=for-the-badge&color=0a0e17&label=PROFILE+VIEWS)

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Martin-Atanasov123&theme=tokyonight" alt="Profile overview: commits, stars, repositories and contribution timeline" width="98%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Martin-Atanasov123&theme=tokyonight" alt="Repositories per language" width="32%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Martin-Atanasov123&theme=tokyonight" alt="Most committed languages" width="32%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Martin-Atanasov123&theme=tokyonight&utcOffset=2" alt="Most productive time of day" width="32%" />

</div>

---

## Beyond Code

Quantitative strategy games and capital markets — the same appeal as a deterministic rules
engine: fixed rules, incomplete information, decisions under uncertainty. And guitar 🎸.

---

<div align="center">

### Let's build something

[![Portfolio](https://img.shields.io/badge/Portfolio-martin--atanasov.netlify.app-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://martin-atanasov.netlify.app/)
[![Email](https://img.shields.io/badge/Get_in_touch-matanasov573%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matanasov573@gmail.com)

<br>

> **“Execution beats ideas that never leave the notebook.”**

<sub>Thanks for stopping by — have a look at <a href="https://uniput.eu/">УниПът</a> or grab <a href="https://github.com/Martin-Atanasov123/EdgeStage/releases/latest">EdgeStage</a>.</sub>

</div>
