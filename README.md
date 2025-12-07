# ✨ Nova / 신성 (Shinseong) ✨

![Build Status](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0-blue?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-purple?style=for-the-badge)
![Made With Love](https://img.shields.io/badge/made%20with-%F0%9F%92%96-red?style=for-the-badge)

🚀 **Nova** is the global English version of our social media platform.  
🌌 **신성 (Shinseong)** is the Korean-first version — intentionally engineered to be **100% better** in speed, features, cultural fit, personalization, and community tools.

---

## 🎨 OUR LOGO

S O C I A L   A P P

N O V A   /   신 성 (Shinseong)

---

## ✨ Highlights

- 🧑‍🎨 **Dynamic Profiles**: Personas, badges, animated banners, AR avatars, and AI-generated living biographies.
- 🎥 **Content Creation**: Real-time co-editing, AI scene editing, collaborative audio tracks, shoppable live streams.
- 🫂 **Communities**: Official fan cafés, tiered fan clubs, reputation points, seasonal events, cross-community exhibitions.
- 🧠 **AI Everywhere**: Mood-aware feeds, etiquette-aware messaging, predictive assistants, explainable recommendations.
- 💸 **Monetization**: Real-time donations, creator storefronts, KR payment rails, collaborative revenue splits.
- 🎮 **Gamification**: Missions, streaks, leaderboards, team challenges, seasonal quests.
- 🌐 **Localization**: Adaptive translation, Hangul-optimized typography, cultural skins, holiday packs.
- 🛡️ **Safety**: Context-aware moderation, respectful defaults, anonymous reporting, pre-post warning nudges.
- 🕹️ **VR/AR Spaces**: Micro-worlds, gesture-based communication, mixed-reality overlays, fandom concerts.

---

## 🖥️ Full Repository Structure

socialx/
├── apps/                  # Frontend apps
│   ├── nova-web/          # English web app
│   ├── shinseong-web/     # Korean web app
│   ├── nova-mobile/       # English mobile app
│   ├── shinseong-mobile/  # Korean mobile app
│   └── desktop/           # Desktop app (Electron)
│
├── backend/               # Backend services (simplified)
│   ├── auth/              # Authentication
│   ├── profiles/          # User profiles
│   ├── content/           # Posts, media
│   ├── feed/              # Feed + recommendations
│   ├── messaging/         # Chat + notifications
│   └── community/         # Groups, fan cafés
│
├── packages/              # Shared libraries
│   ├── ui/                # UI components
│   ├── core/              # Core domain models
│   ├── i18n/              # Internationalization
│   └── feature-flags/     # Toggle Nova vs Shinseong features
│
├── infra/                 # Infrastructure configs
│   ├── firebase/          # Firebase configs & rules
│   ├── docker/            # Dockerfiles
│   └── ci-cd/             # GitHub Actions / workflows
│
├── data/                  # Schemas & seed data
│   ├── firestore/         # Firestore collections
│   ├── storage/           # Cloud Storage rules
│   └── seed/              # Example seed data
│
├── docs/                  # Documentation
│   ├── nova/              # Nova-specific docs
│   ├── shinseong/         # Shinseong-specific docs
│   └── architecture/      # System overview
│
└── README.md              # Project overview


---

## 🎯 Try It Out

Clone the repo and spin up a local dev environment:

```bash
# 1. Clone the monorepo
git clone https://github.com/your-org/socialx.git
cd socialx

# 2. Install dependencies
npm install

# 3. Start Nova (English version)
npm run dev:nova

# 4. Start Shinseong (Korean version, enhanced)
npm run dev:shinseong

Open your browser:

🌍 Nova: http://localhost:3000

🇰🇷 Shinseong: http://localhost:4000

📸 Screenshots & Previews
COMING SOON
