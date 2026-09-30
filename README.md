<div align="center">

# Ehsanur Rahman

### Mobile & Full-Stack AI Engineer · Founder, Hourwise Labs

**Flutter · React Native · Swift · Python — offline-first sync, on-device AI, LLM apps**

**11 years shipping production software · 50+ apps · 1M+ users · 4.7★ average**

[![Website](https://img.shields.io/badge/ehsanur.com-000000?style=flat-square&logo=googlechrome&logoColor=white)](https://ehsanur.com)
[![Email](https://img.shields.io/badge/mail@ehsanur.com-000000?style=flat-square&logo=maildotru&logoColor=white)](mailto:mail@ehsanur.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sujit70777)
[![pub.dev](https://img.shields.io/badge/pub.dev-9%20packages-000000?style=flat-square&logo=dart&logoColor=white)](https://pub.dev/publishers/ehsanur.com/packages)
[![Hourwise](https://img.shields.io/badge/Hourwise-Mac%20App%20Store-000000?style=flat-square&logo=apple&logoColor=white)](https://apps.apple.com/us/app/hourwise-billable-hours/id6811420308)
[![Open to Remote](https://img.shields.io/badge/Open%20to-Remote%20(US%2FUK%2FEU)-000000?style=flat-square)](https://ehsanur.com)

</div>

<br>

## About

I build apps that keep working when the network doesn't, and now apps where AI does the tedious part, privately.

Eleven years in mobile, starting in native Android. I specialise in **offline-first architecture and conflict-free (CRDT) data sync**: the part that quietly breaks most apps in the field. I've open-sourced a CRDT sync library for Flutter and shipped apps holding a 4.7★ rating at 100,000+ daily active users.

Today I'm the founder and sole engineer of **Hourwise Labs**, growing a shipped Mac app into a full-stack AI product: on-device models, a Python backend, sync across Mac, iOS and Android, and a retrieval agent that answers with citations.

I care about clean architecture, native platform integration (WidgetKit, App Intents, Live Activities, WorkManager), test discipline, and the unglamorous work of getting apps *through* App Store and Play review.

I worked shifted hours with a Brazil-based team for three years, so US, UK or EU hours are routine for me. Available full-time or as an independent contractor (B2B) via Deel, Wise or direct invoicing.

<br>

## Building now: Hourwise

**Private, AI-assisted timekeeping and billing for solo lawyers and small firms.**
[Mac App Store](https://apps.apple.com/us/app/hourwise-billable-hours/id6811420308) · [ehsanur.com/hourwise](https://ehsanur.com/hourwise/) · *closed source*

**Live today:** native macOS menu-bar app — SwiftUI + AppKit (~17k lines of Swift), local-first SQLite/GRDB, on-device time attribution (rule engine + naive-Bayes classifier), EventKit calendar import, PDFKit invoices, LEDES 1998B / XLSX / CSV / QuickBooks / Xero exports, StoreKit 2 subscriptions.

**Roadmap:**

| Stage | What | Stack |
|---|---|---|
| **Now** | AI billing narratives written on-device, with billing-rule checks and UTBMS codes | Apple Foundation Models, SwiftUI |
| Next | Private meeting capture → transcript, summary and draft time entry | ScreenCaptureKit, SpeechAnalyzer, on-device LLM |
| Next | Backend: accounts, firm seats, CRDT sync across Swift, Dart and Python clients | Python, FastAPI, PostgreSQL, Fly.io |
| Next | Mobile companion: timers, voice entries, court time, Live Activities | Flutter, WidgetKit, ActivityKit, Kotlin |
| Later | "Ask my matters": tool-using agent with hybrid search, citations and evals | Claude API, pgvector, Postgres full-text |

I'll write up each stage as it ships.

<br>

## Core Stack

**Mobile & desktop**

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![React%20Native](https://img.shields.io/badge/React%20Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS%20%26%20macOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Riverpod](https://img.shields.io/badge/Riverpod-0D47A1?style=for-the-badge&logo=flutter&logoColor=white)

</div>

**AI, data & backend**

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-191919?style=for-the-badge&logo=anthropic&logoColor=white)
![On-device AI](https://img.shields.io/badge/On--device%20AI-1F4D3A?style=for-the-badge&logo=apple&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

</div>

**Shipping**

<div align="center">

![GitHub%20Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![App%20Store](https://img.shields.io/badge/App%20Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white)
![Google%20Play](https://img.shields.io/badge/Google%20Play-414141?style=for-the-badge&logo=google-play&logoColor=white)

</div>

<br>

## Open Source

| Package | What it does |
|---|---|
| **[flutter_crdt_sync_kit](https://pub.dev/packages/flutter_crdt_sync_kit)** | Offline-first, CRDT-based local data layer. Write while offline, merge conflict-free on reconnect. Pluggable Supabase/REST adapters. |
| **[local_voice](https://pub.dev/packages/local_voice)** | Privacy-first, fully on-device voice command recognition. No cloud, no API keys, works in airplane mode. |
| **[flutter_a11y_lens](https://pub.dev/packages/flutter_a11y_lens)** | Live accessibility auditor — inspects the running widget tree and flags WCAG violations in real time via an on-screen overlay. |
| **[flutter_liquid_glass_widgets](https://pub.dev/packages/flutter_liquid_glass_widgets)** | UI kit implementing Apple's Liquid Glass design language — shader-powered blur, physics-based animation, dynamic lighting. |
| **[flutter_fabric](https://pub.dev/packages/flutter_fabric)** | Canvas library porting Fabric.js's interaction model to Flutter — selectable, draggable, rotatable objects with undo/redo. |

[All 9 packages on pub.dev →](https://pub.dev/publishers/ehsanur.com/packages)

<br>

## Shipped Work

**[Hourwise](https://apps.apple.com/us/app/hourwise-billable-hours/id6811420308)** — Native macOS time tracking and invoicing for lawyers. Founder and sole engineer: design, build, App Store release and marketing.

**Tanto** — Brazilian corporate reimbursement platform: AI invoice capture validated against SEFAZ state tax agencies, policy checks, and instant Pix payout. Team lead and sole developer. *(Company closed Sept 2025; listings removed.)*

**[Farenow](https://play.google.com/store/apps/details?id=com.app.farenow)** — Multi-service super app for a US client (Houston, TX): ride-hailing, on-demand bookings, food and grocery delivery, consultations, and marketplace listings in one Flutter app. Team lead and sole developer.

**[Peace of Mind (POM)](https://apps.apple.com/us/app/pom-app/id6760588055)** — iOS estate planning: digital will management, biometric-locked vault, interactive life timeline. Diagnosed and fixed StoreKit 2 subscription race conditions — `pending`-status bugs, duplicate purchase persistence, navigation-timing failures.

**[Muslim Times Pro](https://apps.apple.com/us/app/muslim-times-pro-prayer-quran/id6740039144)** — Prayer times with azan alerts, full Quran with recitation and translation, mosque locator, Qibla compass. WidgetKit home-screen widgets sharing live data with Flutter via App Group `UserDefaults`, kept in sync with an Android counterpart.

**[Prabartan Educational Platform](https://play.google.com/store/apps/dev?id=6504002943007145339)** — Offline-capable learning apps reaching 100,000+ students across 5 countries, including Learn Python (100K+ installs).

[More on ehsanur.com →](https://ehsanur.com)

<br>

## Side Projects

**[OMR Scanner](https://github.com/sujit70777/omr_scanner_flutter)** — Fully offline exam answer-sheet scanner using registration-mark alignment and homography instead of OCR, with live camera guidance and auto-capture.

**[Jatri — Bangladesh Transit App](https://github.com/sujit70777/Jatri---Bangladesh-Transit-App)** — Journey planner and ticketing app built on real MRT Line 6 and BRTA route data.

**[ar_measure](https://github.com/sujit70777/ar_measure)** — Cross-platform AR measurement plugin for Flutter, wrapping ARKit and ARCore.

<br>

<div align="center">

**Open to remote Senior Mobile and AI Engineer roles, and contract work — US, UK and EU teams.**

[![Portfolio](https://img.shields.io/badge/Portfolio-ehsanur.com-000000?style=flat-square)](https://ehsanur.com)
[![Email](https://img.shields.io/badge/Email-mail@ehsanur.com-000000?style=flat-square)](mailto:mail@ehsanur.com)

</div>
