# Fahd Adebayo

Full-stack & mobile engineer — React Native, Next.js, TypeScript.
Co-founder/CTO at Groom. Two apps live on the App Store & Google Play.

Most of my production work lives in private repos — happy to walk through any codebase live on a call.

---

## What I've shipped

### 🧭 [Groom](https://www.usegroom.com) — AI-powered in-app onboarding for SaaS
Co-founder & CTO. Built the Next.js 15 dashboard and a **zero-dependency 23 KB embeddable SDK** that runs inside arbitrary customer apps: live DOM perception across shadow roots and iframes, resilient element targeting that survives React re-renders, and cross-page guided flows. Constrained-LLM design — the model only resolves intent targets; step sequences are built deterministically and verified. NVIDIA Inception member.

`Next.js 15` `React 19` `NestJS` `PostgreSQL` `Gemini` `AWS`

### 🕌 Deen AI — Qur'an, hadith & prayer companion
Mobile developer. **Live on the [App Store](https://apps.apple.com/us/app/deen-ai-adhan-ai-chat-quran/id6756240670) and [Google Play](https://play.google.com/store/apps/details?id=net.emerj.deenai).** ~79k lines of TypeScript, 89 screens, 15 languages (4 RTL). Fully offline Qur'an + 14,865 hadiths in a two-database SQLite architecture; custom Kotlin AlarmManager module for reliable adhan delivery; subscriptions with server-side receipt validation; self-hosted staged OTA rollouts.

`Expo SDK 54` `React Native 0.81` `op-sqlite` `Kotlin` `WidgetKit` `Firebase`

### ❤️ Forj — matchmaking for professionals
Lead mobile developer (team of two). **Live on the [App Store](https://apps.apple.com/us/app/forj-dating-for-professionals/id6784864431) and [Google Play](https://play.google.com/store/apps/details?id=com.forj.online).** Real-time chat with optimistic sends and reconciliation, Agora voice calls that survive screen unmounts, four-path auth, StoreKit 2 / Play Billing with server-side verification, and a release script that fingerprints each JS bundle and blocks environment-contaminated builds from shipping.

`React Native 0.81` `Expo Router` `Socket.IO` `Agora` `StoreKit 2` `Play Billing`

---

## How I work

- **AI-assisted, human-verified.** Claude Code daily — including structured whole-codebase audits before major phases. My last audit surfaced a push-notification race condition, unbounded database growth, and dead code from an abandoned architecture.
- **Recovery paths over happy paths.** Most of the engineering value in my work lives in the seams: push-vs-socket races, engines surviving navigation, builds that verify themselves before shipping.
- **Ship, then harden.** Three products taken from first commit to production, including store publishing, OTA pipelines, and the architecture calls in between.

---

📍 Lagos (WAT) — full EU overlap, US mornings
📅 [Book a call](https://cal.com/fahd-dev) · 💼 [Contra](https://contra.com/fahdadebayo02_ub1jc8l4) · 🌐 [Portfolio](https://adebayofahd.netlify.app)
