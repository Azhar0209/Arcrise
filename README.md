# ⚡ ARCRISE — Sovereign Athletic Discipline & Habit OS

[![Android](https://img.shields.io/badge/Platform-Android%208.0%2B-brightgreen.svg?style=flat-square)](apk/Arcrise-v1.3.4-debug.apk)
[![Status](https://img.shields.io/badge/Status-Public%20Beta%20%E2%80%A2%20Active%20Testing-orange.svg?style=flat-square)](#-public-beta--active-testing-notice)
[![Feedback](https://img.shields.io/badge/Feedback-Direct%20Channels%20Open-blue.svg?style=flat-square)](#-how-to-share-feedback--report-bugs)
[![React](https://img.shields.io/badge/React-18-blue.svg?style=flat-square)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite-5-purple.svg?style=flat-square)](https://vitejs.dev)
[![Capacitor](https://img.shields.io/badge/Capacitor-6-cyan.svg?style=flat-square)](https://capacitorjs.com)
[![Tests](https://img.shields.io/badge/Tests-18%2F18%20Passed-success.svg?style=flat-square)](test/run_all_tests.js)
[![Official Website](https://img.shields.io/badge/Website-arcrise.netlify.app-gold.svg?style=flat-square)](https://arcrise.netlify.app)

> **Become who you set out to be.**  
> ARCRISE is the disciplined operating system for personal progression, athletic mastery, and daily execution. Built with high-adherence habit architecture, structured strength & calisthenics routines, 90-day consistency heatmaps, and a real community leaderboard.

---

## ⚠️ PUBLIC BETA & ACTIVE TESTING NOTICE

> ### 📢 YES, ARCRISE IS 100% REAL & OPERATIONAL — BUT CURRENTLY UNDER ACTIVE TESTING!
>
> **ARCRISE is a real, live, fully-functional athletic discipline & habit operating system.** It is not a mockup, concept, or prototype. The habit engine, workout routines, Mifflin-St Jeor macro calculator, focus soundscapes, and live athlete leaderboards are all live and executing daily.
>
> However, **the platform is currently in PUBLIC BETA (Active Testing & Rapid Refinement Phase).**
> - 🛠️ **Expect Occasional Bugs & Glitches:** We are pushing frequent updates, refining animations, and hardening device compatibility across hundreds of Android screen sizes and chipsets. You may occasionally run into visual imperfections, UI glitches, or transient errors.
> - 🔄 **Continuous Improvement:** We are actively monitoring performance, upgrading physics engines (such as our dynamic quotes deck and 3D lanyard), and polishing user flows in real time.
> - 💬 **We Need Your Feedback:** Your voice directly decides what gets built, polished, and fixed next. If something feels off, if you spot a bug, or if you have an idea for a killer feature, tell us immediately!

### 📬 How to Share Feedback & Report Bugs
1. **In-App Direct Feedback Screen**: Tap your Profile photo in the app → scroll to **"Send Feedback / Report Issue"** → enter your thoughts and submit instantly.
2. **Direct Founder / HQ Email**: Email us directly at [**`arcrise.hq@gmail.com`**](mailto:arcrise.hq@gmail.com) with screenshots, screen recordings, or details.
3. **GitHub Issues**: Open a new issue right here in this repository under the [**Issues Tab**](https://github.com/Azhar0209/Arcrise/issues).

---

## 📥 Download ARCRISE Android App

The official compiled Android Application Packages are organized in the [`apk/`](apk/) directory:

| Version | Status | Download Link | Key Changes |
| :--- | :--- | :--- | :--- |
| **`v1.3.4`** | **🔥 Latest (Recommended)** | [**Download Arcrise-v1.3.4-debug.apk**](apk/Arcrise-v1.3.4-debug.apk) | Sovereign Force Upgrade Protocol (blocks old APKs), full-screen animated Error Page, universal redeem, skeleton dashboard loading, and silky quotes gestures |
| **`v1.3.3`** | Stable | [Arcrise-v1.3.3-debug.apk](apk/Arcrise-v1.3.3-debug.apk) | Sovereign Founder Gifting Suite, VIP Whitelist engine, WhatsApp 1-tap code sharing, and Gift Code redemption |
| **`v1.3.2`** | Stable | [Arcrise-v1.3.2-debug.apk](apk/Arcrise-v1.3.2-debug.apk) | 3D Card photo customizer with size & alignment sliders, 24K gold strap, automatic Lifetime Pro for Founder |
| **`v1.3.1`** | Stable | [Arcrise-v1.3.1-debug.apk](apk/Arcrise-v1.3.1-debug.apk) | Netbanking in-app modal dialog, crash resolution, subscription availability timeline |
| **`v1.3.0`** | Archived | [`apk/README.md`](apk/README.md#version-history--changelog) | Water Reminder protocol with quiet hours, Netbanking fix, clean dashboard |

*Full version changelog and installation instructions are available in [**`apk/README.md`**](apk/README.md).*

---

## ✨ Core Pillars & Features

### 1. ⚔️ Daily Task Architecture & High-XP Modes
- **Adaptive Day Types**: Switch between **Busy Day** (essential habits) and **Free Day** (expanded 16-task high-yield protocol up to +30 pts per custom task).
- **Zero-Drop Protection**: Streak calculation rewards sustained discipline while preserving lifetime earned points.

### 2. 🏋️‍♂️ Structured Workout Routines & Progression
- **Athlete Training Matrix**: Calisthenics, functional strength, and endurance routines with exercise tracking.
- **Instant XP Accrual**: Workout completion awards verified XP with strict idempotency.

### 3. ⏱️ Focus Timer & Audio Soundscapes
- **25/5 Pomodoro Cadence**: Built-in interval timer with Web Audio API synthesized chimes.
- **Audio Restoration**: Ambient soundscapes designed for cognitive focus and athletic recovery.

### 4. 📊 Macro & Calorie Engine
- **Mifflin-St Jeor Engine**: Accurate BMR and TDEE calculations tailored to body weight, height, and target goals (Lean Bulk, Maintenance, Aggressive Cut).
- **Dynamic Macro Distribution**: Automatically scales protein, carbohydrate, and healthy fat percentages.

### 5. 🏆 Community Leaderboard & Squads
- **Live Leaderboard**: Real-time XP ranking across athletes.
- **Squad Accountability**: Join discipline squads to compete and hold teammates accountable.

### 6. 👑 ARCRISE Pro Sovereign Suite
- **Flexible Commitment**: Monthly (₹79/mo), Annual (₹599/yr), and Permanent Lifetime Sovereign (₹1,499 one-time).
- **Seamless In-App Payments**: Powered by Razorpay Live Gateway and Direct 1-Tap UPI routing.

---

## 📂 Repository Structure

The codebase is organized into clean, dedicated modules:

```
THE ARC (ARCRISE)/
├── android/          # Native Android Studio & Gradle project (Capacitor bridge)
│   ├── app/          # Java source code (MainActivity.java, ArcAppPlugin.java)
│   └── build/        # Gradle build scripts and Android configurations
├── api/              # Serverless preregistration & email delivery backend
├── apk/              # Official APK release binaries, version history & changelog
│   ├── Arcrise-v1.2.0-debug.apk   # Latest Android build
│   └── README.md                  # APK release notes & installation guide
├── assets/           # App screenshots, brand logos & high-res vector assets
│   ├── branding/     # SVG logos, lockups, and app icons
│   └── screenshots/  # High-definition application screenshots
├── docs/             # Technical specifications, security rules & audit logs
│   ├── CHANGELOG.md               # Complete repository development changelog
│   ├── DECISIONS_AND_ASSUMPTIONS.md # Core architectural decisions
│   ├── DEPLOY_INSTRUCTIONS.md     # Production deployment playbook
│   ├── FIRESTORE_DATA_MAPPING.md  # Database schema & security model
│   ├── HANDOFF.md                 # Engineering handoff documentation
│   ├── PROJECT_AUDIT.md           # Security & performance audit reports
│   └── TEST_CHECKLIST.md          # Acceptance criteria & verification checklist
├── netlify/          # Netlify serverless functions & edge routing
├── public/           # Static web assets, audio chimes, and PWA manifest
├── src/              # React 18 application source code
│   ├── components/   # Modular UI components, screens & cards
│   ├── services/     # Entitlements, email, and authentication services
│   ├── shaders/      # WebGL & Canvas visual effects
│   ├── utils/        # Razorpay checkout, UPI routing, and helpers
│   └── App.jsx       # Root React component & state orchestration
├── test/             # 16 automated verification test suites (all passing)
├── index.html        # Production landing page
├── terms.html        # Terms & Conditions (Merchant compliance)
├── privacy.html      # Privacy Policy
├── refund.html       # Cancellation & Refund Policy (Razorpay compliance)
├── capacitor.config.json # Capacitor runtime configuration
├── package.json      # NPM dependencies and build scripts
└── vite.config.js    # Vite 5 production bundler configuration
```

---

## 🛠️ Technology Stack

| Layer | Technologies |
| :--- | :--- |
| **Frontend UI** | React 18, Vite 5, Tailwind CSS, Framer Motion, Lucide Icons |
| **Mobile Runtime** | Capacitor 6, Android Native Java (Custom BridgeWebViewClient) |
| **Cloud & Database** | Firebase Firestore (Security Rules enforced), Netlify Functions |
| **Payments & Billing** | Razorpay Live Gateway, Native Android UPI Deep Linking |
| **Email Delivery** | Resend API, Gmail SMTP fallback |
| **Audio Engine** | Web Audio API (Synthesized focus chimes) |

---

## 🧪 Automated Test Verification

ARCRISE includes 16 end-to-end automated test suites covering every critical path:

```bash
# Run the master test runner
node test/run_all_tests.js
```

**Verification Results:**
- `[1/16]` Vite Production Build: **PASSED**
- `[2/16]` Firestore Security Rules (41 invariants): **PASSED**
- `[3/16]` Core Logic & Acceptance Criteria (15 rules): **PASSED**
- `[4/16]` Pre-Registration & Legal Compliance: **PASSED**
- `[5/16]` Progression & Gamification: **PASSED**
- `[6/16]` Pillar 3 Achievements & Milestones: **PASSED**
- `[7/16]` Pillar 4 Leaderboard & Accountability: **PASSED**
- `[8/16]` Feedback Submission & Validation: **PASSED**
- `[9/16]` Calorie & Macro Calculator: **PASSED**
- `[10/16]` Day Selection & Navigation: **PASSED**
- `[11/16]` Verified Athlete Credential Boundary: **PASSED**
- `[12/16]` Avatar System & Local Persistence: **PASSED**
- `[13/16]` Offline Guest Mode & Cloud Sync: **PASSED**
- `[14/16]` Day Planning Engine & Time Blocks: **PASSED**
- `[15/16]` Comprehensive 25-Claim System Audit: **PASSED**
- `[16/16]` Phase 5 Monetization & Analytics: **PASSED**

---

## 🚀 Local Development

```bash
# 1. Install dependencies
npm install

# 2. Run local development server
npm run dev

# 3. Build web bundle & sync to Android
npm run build
npx cap sync android

# 4. Compile Android debug APK
cd android
./gradlew assembleDebug
```

---

## 📜 Legal & Compliance

- **Terms of Service**: [`https://arcrise.netlify.app/terms`](https://arcrise.netlify.app/terms)
- **Privacy Policy**: [`https://arcrise.netlify.app/privacy`](https://arcrise.netlify.app/privacy)
- **Refund Policy**: [`https://arcrise.netlify.app/refund`](https://arcrise.netlify.app/refund)
- **Support Contact**: `arcrise.hq@gmail.com`

---

*© 2026 ARCRISE. All rights reserved. Sovereign discipline and athletic progression.*
