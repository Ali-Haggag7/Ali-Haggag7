<div align="center">
  <img src="./image.png" alt="Ali Haggag Banner" width="100%" />
  <br/>
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=25&pause=1000&color=00E5FF&center=true&vCenter=true&width=800&lines=Software+Engineer+%7C+Systems+Architect;Architecting+Real-time+3D+Physics+Engines;Compiler+%26+Custom+DSL+Developer;Socket.io+%26+WebRTC+Specialist;Building+Offline-first+PWAs" alt="Typing SVG" />
  </a>
  <br/>
<p align="center"><a href="https://www.linkedin.com/in/ali-haggag7/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a><a href="mailto:ali.haggag2005@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a><a href="https://alihaggag.me/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=next.js&logoColor=white"/></a><a href="https://alihaggag.me/Ali_Haggag_CV.pdf"><img src="https://img.shields.io/badge/Resume-00C853?style=for-the-badge&logo=google-drive&logoColor=white"/></a></p>
</div>
<br/>

### 👨‍💻 About Me

> **"Architecting high-performance, real-time web applications, custom compilers, and deterministic multiplayer game engines with clean code."**

I'm **Ali Haggag**, a Software Engineer & CS Student focused on **System Design, Performance Optimization, and Security Hardening.** I specialize in building complex backends, custom language parsers, and low-latency real-time synchronization layers.

---

#### 🌟 Featured Engineering Builds

*   🤖 **[Logic Arena](https://github.com/Ali-Haggag7/logic-arena) — Competitive Robot Battle Simulator** `v3.6.5`
    *   *Compiler & Sandbox:* Engineered **AliScript v3** (Lexer → AST → sandboxed evaluator, no `eval()`) with a deterministic 2,000-ops/tick TLE quota — fair execution limits regardless of hardware.
    *   *Real-time Sync:* 20 TPS server physics engine with client-side `lerp` interpolation to 60 FPS; delta diffing cuts WebSocket payload size by ~80%.
    *   *Tech Stack:* Next.js 16, NestJS 11, React Three Fiber (Three.js), Socket.io, Redis, PostgreSQL, Prisma, Docker + Nginx, DigitalOcean.

*   🚀 **[Flurry Super App](https://github.com/Ali-Haggag7/Flurry-Super-App) — Real-time Social Super App** `v2.0`
    *   *Communication:* WebRTC P2P audio/video via a custom Socket.io signaling server (<50ms latency).
    *   *Resilience:* Offline-first PWA — IndexedDB action queue synced through Inngest durable functions and a Workbox service worker.
    *   *Tech Stack:* WebRTC, Socket.io, Gemini AI, PWA, React, MongoDB, i18next.

*   🏗️ **[CS Arena Platform](https://github.com/Ali-Haggag7/CS-Arena) — Developer Ecosystem**
    *   *State Engine:* Resolved cascading UI filter race conditions using `useTransition` and a URL-first state engine on Next.js 16 Server Components.
    *   *Tech Stack:* Next.js 16, Sanity CMS, NextAuth, Sentry, Resend, Framer Motion.

---

#### 🩹 Notable Engineering Incidents

*A few real production issues I've diagnosed and fixed — documented in full on my [portfolio](https://alihaggag.me).*

*   **The Ghost Match Massacre** *(Logic Arena, WebSocket/NestJS)* — Disconnected players' matches kept running server-side, pinning CPU at 100%. Fixed by tying match lifecycle to live client count.
*   **Operator Precedence Disaster** *(AliScript compiler)* — `2 + 3 * 4` evaluated to `20`. The expression parser had no precedence tower. Fixed by splitting addition/multiplication into separate parse levels.
*   **Deterministic TLE Quota** *(Sandboxing)* — Wall-clock execution limits made the same script pass on one machine and fail on another. Replaced with a platform-agnostic ops-per-tick counter.

---

#### ⚡ Core Capabilities

*   **Systems Design:** Domain-Driven Design (DDD), Microservices, Anti-Corruption Layers (Zod), and Enterprise Security pipelines.
*   **Real-time Protocols:** WebSocket event handling, WebRTC signaling, and client-side interpolation buffers.
*   **Performance Optimization:** CPU profiling, database pagination query constraints, and asset bundle pruning.

<br/>

---

<div align="center">

### 🛠️ Technical Arsenal

| **Category** | **Technologies** |
| :--- | :--- |
| **Frontend** | <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,nextjs,threejs,tailwind&perline=8" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,mongodb,postgres,firebase,supabase,graphql&perline=8" /> |
| **Compiler & Systems** | ![AST Design](https://img.shields.io/badge/AST_Design-2D3748?style=flat-square) ![Deterministic Sandboxing](https://img.shields.io/badge/Deterministic_Sandboxing-2D3748?style=flat-square) ![A* Pathfinding](https://img.shields.io/badge/A*_Pathfinding-2D3748?style=flat-square) <img src="https://skillicons.dev/icons?i=cpp&perline=1"/> |
| **Data & ORM Layer** | ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white) |
| **Real-time & AI** | ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=flat-square&logo=socket.io&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![PWA](https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white) ![Inngest](https://img.shields.io/badge/Inngest-000000?style=flat-square) |
| **Auth & Security** | ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![NextAuth](https://img.shields.io/badge/NextAuth-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white) ![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-4285F4?style=flat-square&logo=google&logoColor=white) ![Helmet](https://img.shields.io/badge/Helmet-4A4A4A?style=flat-square&logo=nodedotjs&logoColor=white) |
| **DevOps & Infra** | <img src="https://skillicons.dev/icons?i=docker,nginx,vercel,cloudflare,azure&perline=5" /> ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white) ![Sevalla](https://img.shields.io/badge/Sevalla-FF6B35?style=flat-square) ![pnpm Workspaces](https://img.shields.io/badge/pnpm_Workspaces-F69220?style=flat-square&logo=pnpm&logoColor=white) |
| **CMS & State** | ![Sanity](https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=react&logoColor=white) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![i18next](https://img.shields.io/badge/i18next-26A69A?style=flat-square&logo=i18next&logoColor=white) |
| **Monitoring** | ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![Azure Monitor](https://img.shields.io/badge/Azure_Monitor-0089D6?style=flat-square&logo=microsoftazure&logoColor=white) |
| **Design & UI** | <img src="https://skillicons.dev/icons?i=figma&perline=1" /> ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white) |
| **CS & Tools** | <img src="https://skillicons.dev/icons?i=c,git,github,gitlab,vscode,postman,linux,bash,npm,pnpm&perline=10" /> |

</div>
<br/>

---

<div align="center">

### 🏆 GitHub Trophies

<img src="https://github-profile-trophy-ahmed.vercel.app/?username=Ali-Haggag7&theme=onestar&no-bg=true&no-frame=true&row=1&column=7" alt="GitHub Trophies" />

</div>
<br/>

<div align="center">

### 📊 GitHub Stats

<img src="https://github-readme-stats-fast.vercel.app/api?username=Ali-Haggag7&show_icons=true&theme=tokyonight&hide_border=true" height="150" alt="Ali's GitHub Stats" />
<img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Ali-Haggag7&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Ali's Top Languages" />

<br/>

<img src="https://streak-stats.demolab.com/?user=Ali-Haggag7&theme=tokyonight&hide_border=true&background=0d1117&fire=00E5FF&ring=00E5FF&currStreakLabel=00E5FF&currStreakNum=00E5FF&sideLabels=58A6FF&sideNums=58A6FF&dates=8B949E" height="150" alt="Ali's Streak" />
<img src="https://github-readme-stats-fast.vercel.app/api/wakatime?username=AliHaggag7&layout=compact&theme=tokyonight&hide_border=true" height="150" alt="Ali's Coding Time" />

<br/>
<hr/>

<p>🚀 <i>Building deterministic systems where performance, correctness, and maintainability come first.</i></p>

</div>
