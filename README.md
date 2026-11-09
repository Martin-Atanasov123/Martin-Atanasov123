<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e17,50:1f3b73,100:1f6feb&height=180&section=header&text=Martin%20Atanasov&fontColor=ffffff&fontSize=52&fontAlignY=36&desc=Product%20Engineer%20%C2%B7%20Web%20%C2%B7%20Windows%20%C2%B7%20Android&descSize=16&descAlignY=58" width="100%" alt="Martin Atanasov — Product Engineer" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=I+ship+finished+software%2C+not+demos.;Local-first+%C2%B7+private+%C2%B7+offline+by+design.;Tested+cores.+Measured+budgets.+Tagged+releases." alt="Tagline" />

<br><br>

[![Portfolio](https://img.shields.io/badge/Portfolio-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://martin-atanasov.netlify.app/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matanasov573@gmail.com)
[![Pleven](https://img.shields.io/badge/Pleven,_BG-2ECC71?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Open to work](https://img.shields.io/badge/Open_to_work-8A2BE2?style=for-the-badge&logo=handshake&logoColor=white)](mailto:matanasov573@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />

</div>

## 👋 About

```yaml
name:        Martin Atanasov
located_in:  Pleven, Bulgaria
role:        Product Engineer
platforms:   [ Web, Windows, Android ]

principles:
  - local-first by architecture, not by policy
  - pure cores, so correctness can be proven
  - budgets measured, including the ones I miss

currently_shipping: [ УниПът, Nowdrop, EdgeStage ]
exploring:          [ on-device AI, Win32 interop, offline-first sync ]

reach_me_at: matanasov573@gmail.com
open_to:     [ collaboration, freelance, full-time ]
```

I build **complete products** across web, Windows and Android — each one shipping with a
tested core, written architecture decisions, measured performance budgets, and a release
people can actually download.

> 🔐 **Local-first by architecture, not policy.** `ShotKeep` ships without the internet
> permission, so it *cannot* upload. `FlowLocal` runs Whisper and an LLM fully offline.
> `Nowdrop` moves files over your own Wi-Fi. No telemetry, no accounts, no cloud.
>
> 🧪 **Correctness you can prove.** Pure, deterministic cores kept apart from I/O — so a
> 102-test rules engine can assert *behaviour* instead of implementation.

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />
</div>

## 🚀 Flagship Work

### 🎓 УниПът — University Admission Platform

[![Live](https://img.shields.io/badge/%E2%96%B6_Live-uniput.eu-3ECF8E?style=flat-square)](https://uniput.eu/)
[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/Uni-put)
<img src="https://skillicons.dev/icons?i=react,vite,tailwind,threejs,supabase,postgres&theme=dark" height="28" align="right" />

A free platform helping Bulgarian students **calculate their admission score, find a career
direction, and compare universities** in one place. The calculator applies each programme's
official formula and auto-selects the best grade for every slot; a RIASEC assessment
(30/60/90 questions) maps personality to matching programmes via the O\*NET database.

<sub>`React 19` · `Vite 6` · `Tailwind 4 + DaisyUI` · `Framer Motion` · `Three.js` · `Supabase` · `Vitest`</sub>

---

### ♠️ Белот онлайн — Real-Time Multiplayer Card Game

[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/belot)
[![Engine tests](https://img.shields.io/badge/engine_tests-102-3ECF8E?style=flat-square)](https://github.com/Martin-Atanasov123/belot)
<img src="https://skillicons.dev/icons?i=ts,react,nodejs,docker&theme=dark" height="28" align="right" />

Four-player Bulgarian Belot in the browser, built **cheat-proof by design**: the client only
renders state and sends intents, while the server validates every action against a pure rules
engine and emits one masked `PlayerView` per seat — no card ever leaks over the wire.
Complete official ruleset, heuristic bots, bilingual BG/EN, mobile-responsive.

<sub>`TypeScript` monorepo · `Fastify + Socket.IO` · `React + Vite` · `Zustand` · `Docker` · `Render + Netlify`</sub>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />
</div>

## 🛠️ Shipped Tools

<table>
<tr>
<td width="50%" valign="top">

### 🪟 EdgeStage

[![Release](https://img.shields.io/github/v/release/Martin-Atanasov123/EdgeStage?style=flat-square&label=release&color=60CDFF)](https://github.com/Martin-Atanasov123/EdgeStage/releases/latest)
[![CI](https://img.shields.io/github/actions/workflow/status/Martin-Atanasov123/EdgeStage/ci.yml?style=flat-square&label=CI)](https://github.com/Martin-Atanasov123/EdgeStage/actions)

Stage Manager for Windows. **Live DWM thumbnails** at the screen edge — a video keeps
playing in the preview. Click one and it zooms into the real window. Plus an Exposé grid
of every window at once.

Opens *without stealing focus*. No network, no telemetry, ~0.1% CPU idle.

<img src="https://skillicons.dev/icons?i=cs,dotnet,powershell&theme=dark" height="26" />

</td>
<td width="50%" valign="top">

### 📡 Nowdrop

[![Site](https://img.shields.io/badge/%E2%96%B6_nowdrop.netlify.app-3ECF8E?style=flat-square)](https://nowdrop.netlify.app/)
[![Preview](https://img.shields.io/github/v/release/Martin-Atanasov123/nowdrop-downloads?style=flat-square&label=preview&color=orange)](https://github.com/Martin-Atanasov123/nowdrop-downloads/releases/latest)

AirDrop-style transfer between **Mac, Windows and Android** — files, links, text and
clipboard, over your own Wi-Fi.

Signed-pending installers for all three platforms, iterated across **22 preview releases**.

![Windows](https://img.shields.io/badge/Windows-.msi-0078D4?style=flat-square&logo=windows&logoColor=white)
![macOS](https://img.shields.io/badge/macOS-.zip-000000?style=flat-square&logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-.apk-3DDC84?style=flat-square&logo=android&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ FlowLocal

[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/Voice-to-text)
[![Offline](https://img.shields.io/badge/100%25-offline-8A2BE2?style=flat-square)](https://github.com/Martin-Atanasov123/Voice-to-text)

Hold CapsLock → speak → release, and clean text lands in whatever app has focus.
**Fully offline** Whisper + local LLM.

Detects your GPU and picks models sized to actual VRAM. Select any text anywhere to
rewrite it; dictate an instruction and it writes the text for you. EN/BG, auto-detected.

<img src="https://skillicons.dev/icons?i=python,powershell&theme=dark" height="26" />

</td>
<td width="50%" valign="top">

### 😀 QuickEmoji

[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/QuickEmoji)
[![Search](https://img.shields.io/badge/search-0.10ms-3ECF8E?style=flat-square)](https://github.com/Martin-Atanasov123/QuickEmoji)

Press `Win+Shift+E`, type a word, hit Enter — the best emoji appears where you were typing.

Built to **published performance budgets, measured not assumed**: 0.10 ms search,
0.69 s cold start, 0% idle CPU. Per-app overrides, skin tones, multi-language.

<img src="https://skillicons.dev/icons?i=cs,dotnet&theme=dark" height="26" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📱 ShotKeep

[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/No-ScreenShot)
[![No internet](https://img.shields.io/badge/no_internet_permission-8A2BE2?style=flat-square)](https://github.com/Martin-Atanasov123/No-ScreenShot)

Catches each new screenshot and offers **Keep / Delete / Later** from a notification,
classifying it on-device.

Ships **without the internet permission** — it cannot upload, even by mistake. Verified
on real hardware: survives service death and reboot, recovers missed shots.

<img src="https://skillicons.dev/icons?i=kotlin,androidstudio,gradle&theme=dark" height="26" />

</td>
<td width="50%" valign="top">

### 💡 EngeleBlur

[![Source](https://img.shields.io/badge/Source-181717?style=flat-square&logo=github)](https://github.com/Martin-Atanasov123/EngeleBlur)

Blurs and darkens your screen when the **laptop lid angle drops** — estimated from the
webcam alone, no extra sensors.

A small, sharp idea: shoulder-surfing protection that needs no hardware.

<img src="https://skillicons.dev/icons?i=python,opencv&theme=dark" height="26" />

</td>
</tr>
</table>

<details>
<summary><b>📦 More projects</b> — portfolio, e-commerce, games & experiments</summary>

<br>

| Project | What it is | Stack |
|---|---|---|
| [**Portfolio**](https://martin-atanasov.netlify.app/) | My personal site | `TypeScript` `React` |
| [**MarketPlace**](https://github.com/Martin-Atanasov123/MarketPlace) | Full-stack marketplace — SoftUni defence project | `JavaScript` `Node` `Express` |
| [**Chess**](https://martin-atanasov123.github.io/Chess-Game/) | Browser chess with full move legality | `JavaScript` |
| [**Rubik's Cube**](https://github.com/Martin-Atanasov123/Rubik-Cube) | Interactive 3D cube | `TypeScript` |
| [**Quiz**](https://martin-atanasov123.github.io/Quiz-Game/) · [**Millionaire**](https://martin-atanasov123.github.io/Who-Wants-to-Be-a-Millionaire/) | Quiz engines with scoring & lifelines | `JavaScript` |
| [**Puzzle**](https://martin-atanasov123.github.io/Puzzel/) · [**Matching**](https://martin-atanasov123.github.io/Matching-game/) · [**Tic-Tac-Toe**](https://github.com/Martin-Atanasov123/tic-tac-toe) | Logic & memory games | `JavaScript` |
| [**On-Screen Keyboard**](https://martin-atanasov123.github.io/Keyboard/) | Virtual keyboard with live input | `JavaScript` |
| [**Restaurant Menu**](https://martin-atanasov123.github.io/Restaurant-menu/) · [**Knives Site**](https://martin-atanasov123.github.io/knives-site/) | Early client-style sites | `HTML` `CSS` `JS` |

</details>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />
</div>

## ⚙️ Tech Stack

<div align="center">

**Languages**

[![Languages](https://skillicons.dev/icons?i=ts,js,cs,python,kotlin,postgres&theme=dark)](#)

**Frontend**

[![Frontend](https://skillicons.dev/icons?i=react,vite,tailwind,threejs,html,css&theme=dark)](#)

**Backend & Data**

[![Backend](https://skillicons.dev/icons?i=nodejs,express,supabase,postgres,docker&theme=dark)](#)

**Desktop & Mobile**

[![Desktop](https://skillicons.dev/icons?i=dotnet,cs,androidstudio,kotlin,gradle,powershell&theme=dark)](#)

**Tooling**

[![Tooling](https://skillicons.dev/icons?i=git,githubactions,vitest,netlify,vscode,figma&theme=dark)](#)

<sub>Also: `Fastify` · `Socket.IO` · `Zustand` · `Framer Motion` · `Whisper` · `Ollama` · `WPF / WinUI` · `pytest`</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />

</div>

## 🧭 How I Work

| | | |
|:--:|---|---|
| 🧪 | **Pure cores, tested as contracts** | Belot's engine has no `Date.now()`, no I/O, no randomness outside a seeded PRNG — so tests assert *scoring behaviour*, and refactors stay safe |
| 📊 | **Budgets, measured** | Performance targets published with real numbers, including the ones I **missed** and why |
| 🔬 | **Verified on real hardware** | Feasibility gates and device verification on an actual phone — fixtures written by the rule-author agree with themselves by construction |
| 🚢 | **Tagged releases** | Versioned builds, changelogs and installers, not just a `main` branch |
| 🔐 | **Privacy as architecture** | Omit the permission, bind to localhost — enforced structurally, not promised in a policy |

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />
</div>

## 📊 GitHub Activity

<div align="center">

![Followers](https://img.shields.io/github/followers/Martin-Atanasov123?style=for-the-badge&logo=github&logoColor=white&color=0a0e17&labelColor=161b22)
![Stars](https://img.shields.io/github/stars/Martin-Atanasov123?style=for-the-badge&logo=github&logoColor=white&color=0a0e17&labelColor=161b22)
![Profile views](https://komarev.com/ghpvc/?username=Martin-Atanasov123&style=for-the-badge&color=0a0e17&label=PROFILE+VIEWS)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Martin-Atanasov123/Martin-Atanasov123/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Martin-Atanasov123/Martin-Atanasov123/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/Martin-Atanasov123/Martin-Atanasov123/output/github-snake.svg" alt="A snake eating my GitHub contribution graph" width="98%" />
</picture>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Martin-Atanasov123&theme=tokyonight" alt="Profile overview: commits, stars, repositories and contribution timeline" width="98%" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Martin-Atanasov123&theme=tokyonight" alt="Repositories per language" width="32%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Martin-Atanasov123&theme=tokyonight" alt="Most committed languages" width="32%" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Martin-Atanasov123&theme=tokyonight&utcOffset=2" alt="Most productive time of day" width="32%" />

</div>

## 🎸 Beyond Code

Quantitative strategy games and capital markets — the same appeal as a deterministic rules
engine: fixed rules, incomplete information, decisions under uncertainty. And guitar.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0a0e17,50:1f6feb,100:0a0e17&height=3" width="100%" alt="" />

### Let's build something

[![Portfolio](https://img.shields.io/badge/Portfolio-martin--atanasov.netlify.app-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://martin-atanasov.netlify.app/)
[![Email](https://img.shields.io/badge/matanasov573@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matanasov573@gmail.com)

<br>

> **“Execution beats ideas that never leave the notebook.”**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,50:1f3b73,100:0a0e17&height=120&section=footer" width="100%" alt="" />

</div>
