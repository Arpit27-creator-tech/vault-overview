# 🛡️ V.A.U.L.T
### Virtual Academic Underground Learning Team
> **Real-Time Cooperative Multiplayer EdTech Heist Platform**  
> *Where escape-room adrenaline meets high-stakes cross-disciplinary academic mastery.*

---

<p align="center">
  <a href="https://virtualacademic.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/LIVE_APP-virtualacademic.vercel.app-00FFCC?style=for-the-badge&logo=vercel&logoColor=000&labelColor=0d1117" alt="Live App" />
  </a>
  <a href="https://vaults.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/MIRROR-vaults.vercel.app-00E599?style=for-the-badge&logo=vercel&logoColor=000&labelColor=0d1117" alt="Live Mirror" />
  </a>
  <a href="https://github.com/Arpit27-creator-tech/VAULT" target="_blank">
    <img src="https://img.shields.io/badge/SOURCE_CODE-Arpit27--creator--tech%2FVAULT-cyan?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117" alt="Source Code Repo" />
  </a>
  <img src="https://img.shields.io/badge/VERSION-1.0.0-f59e0b?style=for-the-badge&labelColor=0d1117" alt="Version" />
  <img src="https://img.shields.io/badge/LICENSE-MIT-10b981?style=for-the-badge&labelColor=0d1117" alt="License" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite_5-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS_3-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Neon_Serverless-00E599?style=flat-square&logo=neon&logoColor=black" />
  <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" />
  <img src="https://img.shields.io/badge/Web_Audio_API-FF4154?style=flat-square&logo=soundcharts&logoColor=white" />
</p>

> 💡 **Official Codebase:** This repository provides the architectural overview and technical specification for V.A.U.L.T. The complete implementation, frontend, and backend source code are available at [github.com/Arpit27-creator-tech/VAULT](https://github.com/Arpit27-creator-tech/VAULT).

---

## ⚡ Table of Contents

- [Overview & Vision](#-overview--vision)
- [The Problem with Existing EdTech](#-the-problem-with-existing-edtech)
- [Core Gameplay: The Three-Stage Heist](#-core-gameplay-the-three-stage-heist)
- [The Four Operative Roles](#-the-four-operative-roles)
- [The Asymmetric Interdependence Engine](#-the-asymmetric-interdependence-engine)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Project Directory Structure](#-project-directory-structure)
- [Quickstart & Local Installation](#-quickstart--local-installation)
- [Environment Configuration](#-environment-configuration)
- [API & WebSocket Protocol](#-api--websocket-protocol)
- [Deployment Guide](#-deployment-guide)
- [Pedagogical Impact & Bloom's Taxonomy](#-pedagogical-impact--blooms-taxonomy)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🎯 Overview & Vision

**V.A.U.L.T** (*Virtual Academic Underground Learning Team*) is a synchronous, real-time multiplayer educational game where squads of 3–4 players assume specialized operative identities to execute high-stakes virtual "heists". 

Instead of answering solitary multiple-choice trivia, players must combine their subject-matter expertise across **Computer Science & Logic**, **Mathematics & Physics**, **Natural Sciences (Chemistry/Biology)**, and **Linguistics & Cryptography** to infiltrate secure virtual chambers, bypass laser tripwires, synthesize neutralizing chemical compounds, and crack polyalphabetic encryption protocols before the mission timer expires or alarms trigger lockdown.

---

## ⚔️ The Problem with Existing EdTech

Traditional educational software is built around solitary, rote drills or shallow speed competitions:

```
             HIGH COLLABORATION / MULTIPLAYER
                            ▲
                            │
                            │     ★ V.A.U.L.T
                            │       (Cross-Disciplinary, Interdependent, Live Co-Op)
                            │
           Kahoot / Quizizz │
      (Speed MCQs, Shallow) │
                            │
◄───────────────────────────┼───────────────────────────►
SINGLE-SUBJECT              │               MULTI-SUBJECT
                            │
           Duolingo         │       Khan Academy / BrainPOP
    (Solo, Streaks, Drills) │       (Solo, Passive Videos, Quizzes)
                            │
                            ▼
                       SOLO / ISOLATED
```

### Feature Breakdown

| Dimension | Duolingo / Anki | Kahoot! / Quizizz | Khan Academy | ★ **V.A.U.L.T** |
| :--- | :--- | :--- | :--- | :--- |
| **Social Dynamics** | Solo + Passive streaks | Competitive speed clicking | Completely solitary | **Synchronous Co-Op (3–4 Players)** |
| **Subject Synergy** | Language only | Siloed questions | Single-subject video tracks | **Integrated Cross-Disciplinary** |
| **Context & Narrative** | Decontextualized cards | Game show trivia | Textbook lectures | **Immersive Cyberpunk Heist Storyline** |
| **Cognitive Depth** | Rote recall (Memorize) | Quick reflex recall | Conceptual review | **Applied Synthesis & Analysis** |
| **Peer Accountability** | Zero | Individual ranking | None | **Critical (Squad cannot proceed alone)** |
| **Replayability** | Fixed flashcard trees | Static question sets | Linear curriculum | **Procedural Generator + Custom Workshop** |

---

## 🕹️ Core Gameplay: The Three-Stage Heist

Every heist operation tests the squad across three escalating phases:

```
                            ┌─────────────────────────┐
                            │   THE VAULT OPERATION   │
                            └────────────┬────────────┘
                                         │
                 ┌───────────────────────┼───────────────────────┐
                 ▼                       ▼                       ▼
       ┌──────────────────┐    ┌──────────────────┐    ┌──────────────────┐
       │   STAGE 1:       │    │   STAGE 2:       │    │   STAGE 3:       │
       │ Perimeter Breach │───►│ The Central Core │───►│ Vault Extraction │
       │ (Parallel Tasks) │    │(Interlocked Wire)│    │ (Boss Challenge) │
       └──────────────────┘    └──────────────────┘    └──────────────────┘
```

1. **Stage 1: Perimeter Breach (Parallel Probing)**  
   Each operative must disarm their primary perimeter defense station (e.g. initial port scan, circuit balancing, ventilation scrub, cipher initialization).
2. **Stage 2: The Central Core (Interlocked Dependency)**  
   Direct cross-role dependencies activate. No player can complete their terminal without live data, formulas, or coordinates generated by another operative.
3. **Stage 3: Vault Extraction (The Boss Protocol)**  
   All four roles combine their outputs into an synchronized final override sequence under escalated alarm conditions and an accelerating synth audio clock.

---

## 👥 The Four Operative Roles

<table align="center" width="100%">
  <tr>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Arpit27-creator-tech/VAULT/main/public/characters/hacker.jpg" width="140" alt="The Hacker" style="border-radius: 8px;" /><br/>
      <b>💻 The Hacker</b><br/>
      <i>Infiltrator</i>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Arpit27-creator-tech/VAULT/main/public/characters/engineer.jpg" width="140" alt="The Engineer" style="border-radius: 8px;" /><br/>
      <b>⚙️ The Engineer</b><br/>
      <i>Demolitions & Optics</i>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Arpit27-creator-tech/VAULT/main/public/characters/scientist.jpg" width="140" alt="The Scientist" style="border-radius: 8px;" /><br/>
      <b>🧪 The Scientist</b><br/>
      <i>Alchemist & Bio-Defense</i>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Arpit27-creator-tech/VAULT/main/public/characters/cryptographer.jpg" width="140" alt="The Cryptographer" style="border-radius: 8px;" /><br/>
      <b>📜 The Cryptographer</b><br/>
      <i>Linguist & Operator</i>
    </td>
  </tr>
  <tr>
    <td>
      <b>Discipline:</b> Computer Science & Logic<br/>
      <b>Focus:</b> Data structures, recursive algorithms, boolean gates, API routing.<br/>
      <b>Cockpit:</b> Live code terminal, syntax evaluator, firewall router.
    </td>
    <td>
      <b>Discipline:</b> Mathematics & Physics<br/>
      <b>Focus:</b> Trigonometric laser angles, Snell's law optics, circuit resistance, kinetic vectors.<br/>
      <b>Cockpit:</b> Interactive laser refraction grid, optical prism array.
    </td>
    <td>
      <b>Discipline:</b> Chemistry & Natural Sciences<br/>
      <b>Focus:</b> Stoichiometric balancing, pH neutralization, molar mass, thermodynamic gas equilibrium.<br/>
      <b>Cockpit:</b> Reagent bench, autoclave temperature valves, titration pipette.
    </td>
    <td>
      <b>Discipline:</b> Linguistics & Cryptography<br/>
      <b>Focus:</b> Polyalphabetic Vigenère keys, frequency analysis, Caesar/Atbash, etymology.<br/>
      <b>Cockpit:</b> Polyalphabetic decipher desk, frequency chart, radio intercept monitor.
    </td>
  </tr>
</table>

---

## 🧩 The Asymmetric Interdependence Engine

Solo brute-forcing and isolated Googling are mathematically impossible in *V.A.U.L.T*. The solution variables are intentionally partitioned across disparate operative screens:

```mermaid
sequenceDiagram
    autonumber
    actor H as 💻 Hacker
    actor S as 🧪 Scientist
    actor E as ⚙️ Engineer
    actor C as 📜 Cryptographer
    participant Svr as 🛡️ Heist Engine

    Note over H,C: Mission Objective: Bypass Chamber Core B
    Svr->>S: Deliver Compound Reagent Request (Sample 92)
    S->>Svr: Submit Stoichiometric Neutralization (Yield: 7F)
    Svr->>E: Transmit Refractive Index & Optical Density
    E->>Svr: Calculate Precision Laser Angle (θ = 42.5°)
    Svr->>H: Laser strike activates Gateway Memory Register
    H->>C: Transmit Encrypted Hex Stream
    C->>Svr: Decrypt Polyalphabetic Vigenère Key
    Note over H,Svr: Chamber Core B Unlocked! (+500 XP, +30s Timer Bonus)
```

- **Fail-Forward Alarms:** An incorrect submission does not simply halt the game — it escalates the building alarm tier, deducts **12 seconds** from the squad clock, and increases siren intensity.
- **Micro-Sync:** Actions taken on any operative console trigger instant visual status markers on squadmates' screens via WebSocket broadcasts.

---

## 🌟 Key Features

### 🎮 Multiplayer & Gameplay
- **Real-Time Squad Rooms:** Create or join lobbies using memorable 6-character room codes with instant roster updates.
- **Asymmetric Role Selection:** Claim your preferred operative station with real-time role-locking.
- **Tactical Radio & WebRTC Squad Voice:** Built-in spatial squad voice communication with realistic radio squelch effects and low-latency audio transmission.
- **Solo Simulation Drills:** An offline single-player training mode allowing operatives to hone role-specific skills before entering live heists.
- **Custom Heist Architect Workshop:** An intuitive modal permitting teachers, mentors, and players to build custom missions, modify challenges, and tune difficulty tiers.

### 🎧 Cyberpunk Audio & Aesthetics
- **Procedural Web Audio Synth Engine:** Dynamic, tension-responsive synth soundtrack that accelerates its BPM, filters, and intensity as the mission clock ticks down and alarm tiers elevate.
- **Tactile Sound Effects:** Sci-fi mechanical relays, terminal keystrokes, laser refractions, valve releases, and alert klaxons.
- **Claymorphic & Neubrutalist UI:** Neon-accented dark-mode interfaces, volumetric cards, radar sweeps, and particle burst celebrations.

### 🪪 Operative Identity & Metagame
- **Interactive Operative ID Card:** Customizable cyberpunk badge with dynamic holographic foils, titles, callsigns, themes, and XP level rings.
- **Global Operative Directory:** Inspect profiles, achievements, and statistics of fellow agents across the global network.
- **Remediation Roadmap:** Detailed post-mission pedagogical analytics highlighting exact knowledge gaps and providing structured study roadmaps for identified weaknesses.
- **Skill Telemetry & Leaderboards:** Track Bloom-taxonomy analytical progress across all four disciplines.

---

## 🏛️ System Architecture

```mermaid
graph TB
    subgraph Client ["Client Tier (Browser / PWA)"]
        UI_H["💻 Hacker Terminal"]
        UI_E["⚙️ Engineer Laser Grid"]
        UI_S["🧪 Scientist Reagent Lab"]
        UI_C["📜 Cryptographer Deck"]
        HUD["HUD / Radio / Web Audio Engine"]
    end

    subgraph Gateway ["Transport & Gateways"]
        WS_GW["Socket.io WebSocket Server"]
        HTTP_GW["Express REST API (or Vercel Serverless)"]
        RTC_MESH["WebRTC Mesh / Metered TURN"]
    end

    subgraph Core ["Authoritative Engine (Node.js)"]
        LOBBY_MGR["Lobby & Room Manager"]
        HEIST_ENGINE["Heist State Machine & Timer"]
        PUZZLE_VAL["Interdependence Puzzle Validator"]
        PRESENCE["Player Presence & Disconnect Guard"]
    end

    subgraph Data ["Data & Notification Tier"]
        DB[("PostgreSQL (Neon Serverless)")]
        MAIL["Brevo REST / Resend / SMTP"]
    end

    Client <-->|WebSocket Events| WS_GW
    Client <-->|REST API| HTTP_GW
    Client <-->|Voice Stream| RTC_MESH

    WS_GW <--> LOBBY_MGR
    WS_GW <--> HEIST_ENGINE
    HEIST_ENGINE <--> PUZZLE_VAL
    WS_GW <--> PRESENCE

    HTTP_GW <--> DB
    HEIST_ENGINE <--> DB
    HTTP_GW --> MAIL
```

---

## 📂 Project Directory Structure

```
VAULT/
├── api/                       # Vercel serverless API bridge
│   └── index.js               # Express routing for serverless deployments
├── public/                    # Static public assets
│   ├── characters/            # Operative avatars (hacker, engineer, scientist, etc.)
│   ├── favicon.svg            # Neubrutal cyan logo
│   └── manifest.json          # Web app manifest
├── server/                    # Standalone Node.js real-time backend
│   ├── db/
│   │   ├── index.js           # PostgreSQL connection pool (Neon SSL)
│   │   ├── schema.sql         # Relational schema (Users, Heists, Sessions, Stats)
│   │   ├── seed.sql           # Starter missions and test accounts
│   │   └── setup.js           # Automated DB initialization & migration runner
│   ├── routes/                # REST endpoints
│   │   ├── auth.js            # Login, registration, OTP verification, guest mode
│   │   ├── users.js           # Profiles, XP, badges, operative cards
│   │   ├── missions.js        # Mission catalog & blueprints
│   │   ├── heists.js          # Heist session records & custom heist builder
│   │   ├── leaderboard.js     # Global rankings & squad leaderboard
│   │   ├── teams.js           # Permanent squad creation & rosters
│   │   └── friends.js         # Social connections & invitations
│   ├── sockets/               # Real-time WebSocket handlers
│   │   ├── index.js           # Socket.io bootstrap & middleware
│   │   ├── lobbyManager.js    # Room creation, joining, role locking
│   │   ├── heistEngine.js     # Live mission state machine, timer, alarms, actions
│   │   └── presenceManager.js # Heartbeats, reconnect grace period
│   ├── index.js               # HTTP/WebSocket server entry point
│   └── package.json           # Backend dependencies
├── src/                       # Frontend application (React + Vite)
│   ├── animations/            # Lottie and custom motion variants
│   ├── assets/                # Audio cues and icons
│   ├── components/            # UI components and operative consoles
│   │   ├── HackerTerminal.jsx        # Code editor & algorithmic puzzle console
│   │   ├── EngineerLaserGrid.jsx     # Laser refraction & trigonometry canvas
│   │   ├── ScientistLab.jsx          # Chemical stoichiometry & balance bench
│   │   ├── CryptographerDeck.jsx     # Vigenère/cipher decryption desk
│   │   ├── InterdependenceMatrix.jsx # Real-time cross-player dependency diagram
│   │   ├── SquadRoomLobby.jsx        # Lobby & operative selection interface
│   │   ├── SquadRecruitmentBoard.jsx # Public room browser
│   │   ├── OperativeIdCard.jsx       # 3D interactive agent identity badge
│   │   ├── CardCustomizerModal.jsx   # Badge themes, holo effects, custom callsigns
│   │   ├── RemediationRoadmapModal.jsx # Post-heist educational analysis & roadmaps
│   │   ├── SoloTrainingModal.jsx     # Offline practice simulator
│   │   ├── CreateCustomHeistModal.jsx# Custom heist curriculum workshop
│   │   ├── HeistAudioEngine.js       # Procedural Web Audio synth beats & SFX
│   │   ├── RadioComms.jsx            # Squad tactical voice UI
│   │   └── AuthModal.jsx             # Cyberpunk auth modal (OTP & guest logins)
│   ├── services/              # Client networking layers
│   │   ├── api.js             # Fetch wrapper with JWT persistence
│   │   ├── socket.js          # Socket.io client with auto-reconnect
│   │   └── voiceEngine.js     # WebRTC voice mesh engine
│   ├── utils/                 # Helpers (sound effects, achievements, math)
│   ├── App.jsx                # Main application state orchestrator
│   ├── main.jsx               # React DOM entry point
│   └── index.css              # Custom design system tokens & Tailwind imports
├── render.yaml                # Infrastructure specification for Render
├── vercel.json                # SPA routing and API proxying for Vercel
├── vite.config.js             # Vite configuration with API & WebSocket proxy
└── package.json               # Root scripts and workspace dependencies
```

---

## 🚀 Quickstart & Local Installation

### Prerequisites
- [Node.js](https://nodejs.org/) v18.0.0 or higher
- [npm](https://www.npmjs.com/) v9.0.0 or higher
- A [PostgreSQL](https://www.postgresql.org/) database (local PostgreSQL instance or free cloud [Neon](https://neon.tech) PostgreSQL database)

### 1. Clone the Code Repository
```bash
git clone https://github.com/Arpit27-creator-tech/VAULT.git
cd VAULT
```

### 2. Install Dependencies
Install dependencies for both the frontend client and the backend server:

```bash
# Install frontend & root dependencies
npm install

# Install backend server dependencies
cd server
npm install
cd ..
```

### 3. Configure Environment Variables
Create a `.env` file in the project root:

```bash
cp server/.env.example .env
```

And configure your environment settings (refer to the [Environment Configuration](#-environment-configuration) table below).

### 4. Initialize Database Schema
Run the database migration script to generate all required tables, triggers, and default mission data:

```bash
cd server
npm run db:setup
cd ..
```

### 5. Launch the Development Environment
Run the server and the frontend client concurrently:

#### Terminal 1 — Start the Real-Time Backend
```bash
npm run server
# Server will listen on http://localhost:5001 with WebSocket support
```

#### Terminal 2 — Start the Vite Frontend
```bash
npm run dev
# Frontend will launch on http://localhost:3000 (proxies API and WS to 5001)
```

Open your browser and navigate to **`http://localhost:3000`**.

---

## ⚙️ Environment Configuration

Both the frontend and backend utilize environment variables. You can configure them in `.env` at the root and inside `server/.env`:

| Variable | Description | Default / Example |
| :--- | :--- | :--- |
| `DATABASE_URL` | PostgreSQL connection string (supports Neon pooler URL with SSL) | `postgresql://user:pass@localhost:5432/vault` |
| `PORT` | Port number for the Express and Socket.io server | `5001` |
| `NODE_ENV` | Runtime environment (`development` or `production`) | `development` |
| `JWT_SECRET` | Secret key for signing operative authentication tokens | `your-secure-jwt-secret-string` |
| `JWT_EXPIRES_IN` | Token expiration time | `7d` |
| `CORS_ORIGIN` | Allowed origin for frontend requests | `http://localhost:3000` |
| `BREVO_API_KEY` | *(Optional)* Brevo REST API key for sending email verification OTPs | `xkeysib-...` |
| `RESEND_API_KEY`| *(Optional)* Resend REST API key for OTP delivery | `re_...` |
| `SMTP_HOST` | *(Optional)* SMTP server host (e.g. Gmail App Password) | `smtp.gmail.com` |
| `SMTP_PORT` | *(Optional)* SMTP server port | `465` |
| `SMTP_USER` | *(Optional)* SMTP username / email address | `vault.game.hq@gmail.com` |
| `SMTP_PASS` | *(Optional)* SMTP password or application-specific password | `your-app-password` |
| `METERED_USERNAME` | *(Optional)* TURN server username for WebRTC voice behind NATs | `metered-turn-user` |
| `METERED_CREDENTIAL` | *(Optional)* TURN server credential | `metered-turn-pass` |

---

## 📡 API & WebSocket Protocol

### REST API Endpoints

| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/auth/register` | Create a new operative account |
| `POST` | `/api/auth/login` | Authenticate existing operative and receive JWT |
| `POST` | `/api/auth/guest` | Generate an instant guest operative session |
| `POST` | `/api/auth/verify-otp` | Verify 6-digit email registration OTP |
| `GET` | `/api/auth/me` | Fetch active operative profile and stats |
| `GET` | `/api/missions` | Retrieve list of available heist operations |
| `POST` | `/api/heists/custom` | Publish a custom heist operation (Workshop) |
| `GET` | `/api/leaderboard` | Retrieve global operative and squad rankings |
| `GET` | `/api/users/directory` | Search global operatives and inspect ID cards |
| `GET` | `/api/health` | Healthcheck endpoint reporting DB and email provider status |

### WebSocket Event Protocol (`Socket.io`)

```
CLIENT                                             SERVER
  │                                                  │
  ├─── 'join-lobby' (roomCode, operative) ──────────►│
  │◄── 'lobby-updated' (squadRoster, readyState) ────┤
  │                                                  │
  ├─── 'select-role' (roleId) ──────────────────────►│
  │◄── 'role-assigned' (userId, roleId) ─────────────┤
  │                                                  │
  ├─── 'toggle-ready' (isReady) ────────────────────►│
  │◄── 'heist:start-countdown' (seconds) ────────────┤
  │                                                  │
  ├─── 'heist:action' (stageId, roleId, payload) ───►│
  │◄── 'heist:sync' (stageState, puzzleProgress) ────┤
  │◄── 'heist:alarm' (alarmTier, penaltySeconds) ────┤
  │                                                  │
  ├─── 'radio:voice-signal' (peerData) ─────────────►│
  │◄── 'radio:voice-signal' (peerData) ──────────────┤
```

---

## 🚢 Deployment Guide

### Deploying Frontend to Vercel
1. Fork or push your code to GitHub.
2. Link the repository to [Vercel](https://vercel.com).
3. The included `vercel.json` and `api/index.js` automatically configure routing for Vite single-page applications and provide a serverless fallback for `/api` requests.
4. Set your environment variables (`DATABASE_URL`, `JWT_SECRET`, `BREVO_API_KEY`) in the Vercel Project Settings.

### Deploying Real-Time WebSocket Server to Render
1. Create a **Web Service** on [Render](https://render.com).
2. Connect your GitHub repository.
3. Configure the service using the included `render.yaml`:
   - **Root Directory:** `server`
   - **Build Command:** `npm install`
   - **Start Command:** `node index.js`
   - **Environment:** `Node`
4. Set your `CORS_ORIGIN` to your Vercel deployment URL (e.g. `https://virtualacademic.vercel.app` or `https://vaults.vercel.app`).

---

## 🧠 Pedagogical Impact & Bloom's Taxonomy

V.A.U.L.T was engineered to elevate digital learning beyond the bottom tier of **Bloom's Revised Taxonomy**:

```
      ▲
     / \     [Create]  ── Constructing custom heists & multi-step solutions
    /   \    [Evaluate] ── Cross-auditing squadmate outputs under time pressure
   /     \   [Analyze]  ── Diagnosing failed attempts & dissecting asymmetric clues
  /       \  [Apply]    ── Calculating optics, writing code, balancing reactions
 /         \ [Understand] ── Comprehending cipher logic & chemical equilibrium
/           \[Remember] ── Retaining foundational formulas and constants
─────────────
```

- **Distributed Cognition:** No individual can solve the heist alone; true learning happens in the discourse between the Hacker, Engineer, Scientist, and Cryptographer.
- **Diagnostic Remediation:** Every incorrect submission flags specific curriculum standards. Following each heist, students receive a tailored learning roadmap guiding them through targeted review modules.

---

## 🤝 Contributing & Codebase

The full source code, issue tracker, and contribution guide are hosted on the primary code repository:
👉 **[github.com/Arpit27-creator-tech/VAULT](https://github.com/Arpit27-creator-tech/VAULT)**

---

## 📄 License

This project is licensed under the **MIT License** — see the [MIT License](https://opensource.org/licenses/MIT) for details.

---

<p align="center">
  <b>V.A.U.L.T</b> • Virtual Academic Underground Learning Team<br/>
  Crafted with ❤️ for students, educators, and collaborative learners worldwide.<br/>
  <i>Breach the vault. Master the science.</i>
</p>
