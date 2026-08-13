# Avafli

**Transforming Visions into Victories**

---

Avafli is a product and consulting agency specializing in sweepstakes, gamification, and marketing technology. We build the tools that drive user engagement at scale.

## WINR SDK

**Sweepstakes & engagement infrastructure for mobile and web app publishers.** Drop the SDK in, and your users get a daily prize-draw experience — streaks, entries, and winner claims — that keeps them coming back. Pass whatever identity you already have (even just a user id) and the SDK captures the rest, turning anonymous users into marketing‑consented, contactable entrants.

**Current version: 2.8** — available on every platform.

| Platform | Package |
|----------|---------|
| iOS | [winr_ios_sdk](https://github.com/AVAFLI/winr_ios_sdk) — Swift · Swift Package Manager & CocoaPods (`WINRSDK`) |
| Android | [winr_android_sdk](https://github.com/AVAFLI/winr_android_sdk) — Kotlin · JitPack |
| Flutter | [winr_flutter_sdk](https://github.com/AVAFLI/winr_flutter_sdk) — Dart · [pub.dev](https://pub.dev/packages/winr_flutter_sdk) |
| Web | [winr_web_sdk](https://github.com/AVAFLI/winr_web_sdk) — TypeScript · [npm](https://www.npmjs.com/package/winr-web-sdk) |

### What it does

- **Daily streak & prize draw** — a drop‑in experience that auto‑opens once per day; users claim daily entries and their streak grows the entry count.
- **First‑party email capture** — the SDK collects (and optionally verifies) emails you don't already have, with explicit, unchecked‑by‑default marketing consent.
- **Cross‑device identity** — one real person = one entry per day across all their devices, stitched by a hashed email.
- **Winner claims** — a built‑in flow to notify winners and collect fulfillment details securely.
- **Fully brandable** — your logo, colors, and prize presentation flow through the whole experience.
- **Privacy‑first** — PII encrypted at rest, an in‑app "delete my data" control, and a configurable server that keeps streaks and entries unforgeable.

### One-line setup

```swift
WINR.configure(WINRConfiguration(apiKey: "…", environment: .production, bundleId: "…", user: WINRUser(id: "user_123")))
// The experience auto-opens once per day. Pass an email to pre-fill it, or omit user for a guest session.
```

## Links

🌐 [avafli-website.web.app](https://avafli-website.web.app) · 📊 [Publisher Dashboard](https://avafli-website.web.app/sdk/dashboard) · 🩺 [Service Status](https://avafli-website.web.app/status) · ✉️ info@avafli.com
