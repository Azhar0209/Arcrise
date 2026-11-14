# 📦 ARCRISE — Android APK Releases & Version Archive

Official distribution channel for ARCRISE Android Application Packages (`.apk`).

---

## 🚀 Current Release: `v1.3.2` (Recommended)

| Property | Value |
| :--- | :--- |
| **Filename** | `Arcrise-v1.3.2-debug.apk` |
| **Package ID** | `com.thearc.app` |
| **Target OS** | Android 8.0+ (API 26+) up to Android 14 (API 34) |
| **Build Type** | Debug / Sideload Verified |
| **Architecture** | Universal (arm64-v8a, armeabi-v7a, x86_64) |
| **Size** | ~68 MB |
| **Release Date** | November 2026 |

---

## 📋 Version History & Changelog

### **v1.3.2 — 3D Card Photo Customizer & Sovereign Founder Permanent Free Pro** *(Latest)*
- **Interactive 3D Card Photo & Alignment Engine**:
  - Replaced static initials (`MA`) on the 3D Card with the athlete's real high-resolution photograph.
  - Added an interactive **"Adjust Card Photo (Size & Alignment)"** control panel inside the 3D Card Modal.
  - **Dynamic Zoom & Size**: Live slider from 50% to 250% with precision `[-]` / `[+]` controls.
  - **Horizontal Position**: Live slider from -120px to +120px with `[ ◀ ]` / `[ ▶ ]` directional nudges.
  - **Vertical Position**: Live slider from -120px to +120px with `[ ▲ ]` / `[ ▼ ]` directional nudges.
  - **Custom Card Upload & Reset**: Upload any photo specifically for the 3D card or 1-tap reset to profile photo.
  - Real-time WebGL canvas updates on the swinging 3D card + 100% synchronized HD PNG download badge.
- **24K Gold Sovereign Founder Strap**:
  - Exclusively for the Founder, the 3D lanyard strap is woven with 24K gold metallic thread and laser-etched: `👑 ARC PROTOCOL // SOVEREIGN CREATOR // MOHAMMAD AZHAR // 000` with dual gold-stitched borders!
- **Sovereign Founder Automatic Free Pro (Zero-Leakage Paywall)**:
  - Cryptographically bound to Mohammad Azhar (`02md.azhar@gmail.com` / `ARC-A5YT`).
  - Automatically grants Permanent Lifetime Sovereign Pro at ₹0 cost with zero payment gates.
  - Strict enforcement: All unverified or mock Pro grants for non-founders are completely revoked to Free Tier. Other users must purchase via Razorpay / UPI to unlock Pro.

---

### **v1.3.1 — Netbanking In-App Modal Dialog & Pro Availability Timeline**
- **Resolved Netbanking Fatal Crash**:
  - Replaced WebView same-instance window transport with a dedicated full-screen `popupDialog` WebView.
  - Added dedicated navigation bar with `🔒 Secure Bank Gateway` header and `✕ Cancel` dismiss action.
  - Enabled third-party cookies for seamless cross-domain bank authorization and 3DS OTP redirects.
  - Dedicated hardware back-button listener to traverse bank history or safely return without crashing.
- **Pro Availability & Expiry Engine**:
  - Displays complete Pro membership timeline across the app: **Activated On** start date, **Expiring On** end date, and live **Days Remaining** badge.
  - Integrated into the Pro Subscription Hub, Athlete Profile drawer, and Pro Features matrix.
  - Lifetime Sovereign memberships display `Permanent (Never Expires · Lifetime Sovereign Tier)`.

---

### **v1.3.0 — Water Reminder Protocol, Netbanking In-App Engine & Clean Interface**
- **Sovereign Hydration Protocol (Water Reminder in Pro)**:
  - Native background notifications via Android `AlarmManager` with device reboot resilience.
  - Fully customizable reminder intervals: 30m, 45m, 60m (default), 90m, and 120m.
  - Configurable Sleep Window (Quiet Hours): Silence notifications between set hours (e.g. 10:00 PM to 07:00 AM) so your sleep is never disturbed.
  - Pleasant and soothing custom audio notification tone (`arc_water_chime.mp3`) with gentle acoustic resonance.
  - 1-tap quick glass logging with daily midnight intake reset and real-time hydration meter.
- **Fixed Netbanking & 3DS Mobile Navigation**:
  - Eliminated external browser chooser dialogs ("Open with Chrome / Brave / Internet").
  - In-place WebView popup management routes all bank OTP, 3DS authentication, and Razorpay redirects securely inside the app.
  - Backward navigation safety prevents unexpected app exits while on bank gateways.
- **Removed Target Wake Clock**: Completely removed the wake slider from the Today dashboard for a streamlined, focused interface.
- **Protected Pro Entitlements**: Eliminated any unverified bypass buttons. Direct UPI transactions now require 12-digit UTR verification.

---

### **v1.2.0 — Live Payments & In-App Netbanking Engine**
- **In-App Netbanking & 3DS**: Bank login portals and OTP verification now load seamlessly inside the application WebView without triggering external browser prompts.
- **Native UPI Intent Interception**: Single-tap routing for Google Pay, PhonePe, Paytm, and BHIM with automatic package fallback.
- **Production Payment Integration**: Direct Razorpay Live Key (`rzp_live_...`) integration and manual UPI route to `02md.azhar@okaxis`.
- **Zero Simulation Leakage**: Completely eliminated all free bypass simulation buttons. Pro entitlements are strictly bound to verified transactions.
- **Compliance Linkage**: Connected official Netlify Edge site (`https://arcrise.netlify.app`) with full Terms, Privacy, and Refund documentation.

---

### **v1.1.0 — Luxury Porcelain Light Mode & Avatar Architecture**
- **Porcelain Light Theme**: Full light theme redesign with deep contrast, golden accents, and luxury card elevation.
- **Athlete Avatar System**: High-resolution profile picture crop and local/cloud persistence surviving device restarts.
- **Audio Soundscapes**: Synthesized Web Audio API interval chimes for Focus Timer (25/5 interval intervals).
- **Activity Rings & Radar**: Real-time concentric progress rings and category radar charts.

---

### **v1.0.0 — Sovereign Discipline OS Initial Release**
- **Core Architecture**: Daily discipline task matrix with Free Day (high-XP) and Busy Day modes.
- **Workout Routine Engine**: Calisthenics, strength, and endurance routine tracker with automatic XP accrual.
- **Macro & Calorie Calculator**: Scientific Mifflin-St Jeor formula with adaptive bulking/cutting targets.
- **Offline Guest Mode**: LocalStorage persistence with seamless account migration to Firebase Firestore.
- **Community Leaderboard**: Real-time athlete ranking and squad accountability.

---

## 📲 How to Install on Android

1. **Download the APK**: Download `Arcrise-v1.2.0-debug.apk` directly to your Android device.
2. **Allow Installation**:
   - If prompted: *"For your security, your phone is not allowed to install unknown apps from this source"*.
   - Tap **Settings** &rarr; Toggle on **Allow from this source**.
3. **Install & Launch**:
   - Tap **Install**.
   - Open **ARCRISE** and start your athletic progression.

---

*For support, feature requests, or billing inquiries, contact:*  
**ARCRISE Support Team** &bull; `arcrise.hq@gmail.com` &bull; [`https://arcrise.netlify.app`](https://arcrise.netlify.app)
