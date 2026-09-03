<h2 align="center">Hi 👋, I'm Shoyeb Akhtar</h2>
<p align="center">
  <strong>Mobile Product Engineer · React Native · iOS · Android</strong><br>
  <em>Available for freelance mobile product development</em>
</p>

---

### 🧠 The Short Version
I build mobile products end to end — from an empty repo to the App Store, and then keep them alive. 

Most developers stop at the code. For a business, the hard part starts at release. I specialize in the full lifecycle: building the architecture, navigating store reviews, setting up CI/CD, and managing the crashes, performance bottlenecks, and SDK migrations that happen once real users get their hands on the app.

Much of my work has been in map-heavy apps — live location, clustering, thousands of markers — which is where React Native tends to break in the most interesting ways.

**What I bring to a project:**
- **Build:** React Native & Expo architecture, complex data layers (Redux/RTK Query), offline and caching strategies, and map-driven interfaces that stay fast on real devices.
- **Ship:** EAS builds and OTA updates, signing and provisioning, TestFlight, App Store Connect and Play Console setup, and getting apps through review.
- **Keep Alive:** Sentry/Crashlytics triage, performance work on real hardware, SDK migrations, and analytics you can actually trust before you make business decisions on it.

---

### 🛠 Tech Stack
- **Mobile:** React Native, Expo, EAS, TypeScript, Expo Router / React Navigation, Reanimated, Gesture Handler
- **Maps & Location:** react-native-maps, Google Maps Platform (Directions, Places), marker clustering, geolocation, deep links
- **Ship & Operate:** App Store Connect, Play Console, TestFlight, signing & provisioning, store review, EAS Update (OTA), CI/CD
- **Observability & Analytics:** Sentry, Crashlytics, Play Vitals, GA4 / Firebase Analytics, BigQuery, PostHog, AppsFlyer
- **Backend & Cloud:** Node.js, Express, MongoDB, PostgreSQL, Firebase (Auth, FCM, Remote Config), GCP, Docker
- **Web:** React, Next.js, Redux / RTK Query

---

### 📱 Proven Track Record

- **RangeNow — EV Charging** – [App Store](https://apps.apple.com/in/app/rangenow-ev-charging/id6759698887) – [Google Play](https://play.google.com/store/apps/details?id=now.range.app) 
  *Consumer EV-charging app to find chargers, plan trips, and book sessions. Built from zero; I own mobile end to end.*
- **Kuttl** – [@KuttlApp](https://x.com/KuttlApp) 
  *Centralized tracker for purchases, refunds, and subscriptions. Built the React Native app from zero and led its release to the Play Store.*

---

### 📦 Open Source & Upstream Fixes
Bugs found in production and reported upstream:

- **[sentry-react-native #6630](https://github.com/getsentry/sentry-react-native/issues/6630)** – Sentry was silently dropping every log and span on iOS with React Native ≥ 0.86 while still reporting HTTP 200, so error reporting looked healthy while collecting nothing. Root cause was an unreliable `performance.timeOrigin`; fixed and shipped in [8.25.0](https://github.com/getsentry/sentry-react-native/releases/tag/8.25.0).

---

### 🧭 Things I've Learned Shipping Apps
- An app's hard part starts at release, not before it.
- Most "React Native is slow" turns out to be architecture, not the framework.
- Signing, provisioning, and store review break more launches than code does.
- A crash you can't reproduce is a data problem before it's a debugging problem.
- The second release is harder than the first — you have users now, and you can't break their experience.

---

### 📫 Let's Work Together
Looking to build an MVP, rescue a struggling mobile project, or need a reliable engineer to handle your app's release cycle? Let's talk.

<p align="center">
  <a href="mailto:toshoyeb@gmail.com">Email Me</a> ·
  <a href="https://www.linkedin.com/in/shoyeb-akhtar/">LinkedIn</a>
</p>
