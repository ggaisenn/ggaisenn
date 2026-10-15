<div align="center">

<pre>

╔══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╗
║                                                                                                                          ║
║    ██████╗  ██████╗ ██╗  ██╗ ██████╗   █████╗  ██╗   ██╗     ██████╗  ██████╗ ██╗ ███████╗███████╗███╗   ██╗███╗   ██╗   ║
║   ██╔════╝ ██╔══██╗ ██║  ██║ ██╔══██╗ ██╔══██╗ ██║   ██║    ██╔════╝ ██╔══██╗ ██║ ██╔════╝██╔════╝████╗  ██║████╗  ██║   ║
║   ██║  ███╗███████║ ██║  ██║ ██████╔╝ ███████║ ██║   ██║    ██║  ███╗███████║ ██║ ███████╗█████╗  ██╔██╗ ██║██╔██╗ ██║   ║
║   ██║   ██║██╔══██║ ██║  ██║ ██╔══██╗ ██╔══██║ ╚██╗ ██╔╝    ██║   ██║██╔══██║ ██║ ╚════██║██╔══╝  ██║╚██╗██║██║╚██╗██║   ║
║   ╚██████╔╝██║  ██║ ██████╔  ██║  ██║ ██║  ██║  ╚████╔╝     ╚██████╔╝██║  ██║ ██║ ███████║███████╗██║ ╚████║██║ ╚████║   ║
║    ╚═════╝ ╚═╝  ╚═╝ ╚═════╝  ╚═╝  ╚═╝ ╚═╝  ╚═╝   ╚═══╝       ╚═════╝ ╚═╝  ╚═╝ ╚═╝ ╚══════╝╚══════╝╚═╝  ╚═══╝╚═╝  ╚═══╝   ║
║                                                                                                                          ║ 
║                              Systems and Tooling Engineer · B.Tech CSE · ABV-IIITM GWALIOR                               ║
╚══════════════════════════════════════════════════════════════════════════════════════════════════════════════════════════╝
</pre>

</div>

---

## `CONNECT`

<div align="center">

[![Website](https://img.shields.io/badge/🌐_Portfolio-GauravGaisenn-6366F1?style=for-the-badge)](https://gauravgaisenn.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-ggaisenn-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ggaisenn)
[![Instagram](https://img.shields.io/badge/Instagram-gaisenn__talks-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/gaisenn_talks/)
[![YouTube](https://img.shields.io/badge/YouTube-gaisenn_talks-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@gaisenntalks)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=Codeforces&logoColor=white)](https://codeforces.com/profile/gaurav_gaisenn)
</div>

---

## `ABOUT`

```yaml
name:       Gaurav Gaisenn
username:   ggaisenn
role:       B.Tech CSE Student
institute:  ABV-IIITM Gwalior, Madhya Pradesh
focus:
  - Systems Programming (C/C++)
  - Real-Time Simulation Engines
  - Developer Tooling (Node.js Scripting, CMake, Docker)
  - Open-Source
open_to:
  - Open-source contributions
```

---

## `PROJECTS`

### [`ThermaSync-EV`](https://github.com/ggaisenn/ggthermalsync) — EV Thermal Simulation & Telemetry Pipeline

```
Language  │ C++17, Node.js, Three.js, Docker
Platform  │ Cross-Platform / Docker Compose
License   │ Apache-2.0
Status    │ Completed · v1.0
```

![Engine-in-Action](profile/projects/1.avif)

Real-Time Telemetry Engine simulating EV battery thermal behavior. 
- C++17 physics core with PID cooling logic
- Node.js TCP/WebSocket backend for safety validation and ring-buffer history.
- Three.js/Chart.js 3D browser dashboard.

## Status

| Area | State | Includes |
|---|---|---|
| Core engine | Implemented | 16-cell thermal model, PID cooling control, safety override, TCP telemetry |
| Telemetry backend | Implemented | TCP validation, ring-buffer history, HTTP API, WebSocket stream, safety triggers, simulation controls |
| Dashboard | Implemented | Responsive views, 3D battery/coolant model, rolling charts, cell HUD, alerts, light/dark theme |
| Fault injection | Implemented | Normal and overheat mock streams; Cell chaos scenario with backend and PID verification |
| Docker Compose | Implemented | Engine, backend, and static dashboard services with local networking |

### [`ggcli`](https://github.com/ggaisenn/ggcli) — Custom CLI Tool

```
Language  │ Javascript
Platform  │ URLs: Cross-Platform, Apps: macOS
License   │ Apache-2.0 license
Status    │ Active
```

A CLI tool built using Node.js that enables users to launch web links and local applications.

### Current Status

| Step | Feature                                        | Status  |
| ---- | --------------------------------------------   | ------  |
| 1    | Script binary entry (`bin/index.js`)           |  Done   |
| 2    | Command-line arguments parsing (`arg`)         |  Done   |
| 3    | Custom logging with color themes (`chalk`)     |  Done   |
| 4    | Launcher command logic (`open`)                |  Done   |
| 5    | Configuration file search (`cosmiconfig`)      |  Done   |
| 6    | Global package execution links (`npm link`)    |  Done   |
| 7    | Custom JSON Schema configuration rules         |  Done   |
| 8    | Schema-based verification (`ajv`)              |  Done   |
| 9    | Better validation logs (`better-ajv-errors`)   |  Done   |
| 10   | Namespace debugging flag (`debug`)             |  Done   |
| 11	 | Cross-platform URL format validation	          |  Done   |
| 12	 | Host system local app check (`command-exists`) |  Done   |
| 13   | `www.` protocol handling                       |  Done   |
| 14   | macOS App Launch (e.g., `--open Slack`)        |  Done   |
| 15   | Cross-Platform App launcher                    | Process |
|      |---------- MORE FEATURES COMING SOON -----------|         |


## `TECH STACK`

<div align="center">

**Languages**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Backend & Networking**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socket.io&logoColor=white)

**Frontend & Visualization**

![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-563d7c?&style=for-the-badge&logo=css3&logoColor=white)

**Tools & DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)
</div>

---

## `STATS`

<div align="center">

<br/>

<a href="https://git.io/streak-stats"><img src="./profile/streak.svg" alt="GitHub Streak" /></a>

</div>

---

## `ROADMAP`

```

2026 ──┼──  [ggthermalsync] EV thermal physics engine & telemetry pipeline
       |    [ggcli] Custom CLI tool
       │    [ggalloc] Custom memory allocator
       │     First open-source PRs merged
       │
```

---

<div align="center">

```
Open to Contributions, PRs
Let's Forge Greatness Together
```

</div>
