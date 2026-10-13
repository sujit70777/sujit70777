<!-- Header -->
<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Ehsanur Rahman — Senior Flutter Engineer. Native iOS, Android and macOS." />
</p>

<p align="center">
  <a href="https://ehsanur.com">
    <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Sans&weight=600&size=22&duration=3200&pause=900&color=C9972F&center=true&vCenter=true&width=760&lines=Senior+Flutter+Engineer+%C2%B7+native+iOS%2C+Android%2C+macOS;Custom+plugins+%C2%B7+offline-first+sync+%C2%B7+payments;Remote+%C2%B7+works+with+any+time+zone" alt="Senior Flutter Engineer" />
  </a>
</p>

<p align="center">
  <a href="mailto:mail@ehsanur.com"><img src="https://img.shields.io/badge/Hire%20me-mail@ehsanur.com-C9972F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/sujit70777"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://ehsanur.com"><img src="https://img.shields.io/badge/Case%20studies-ehsanur.com-1F4D3A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Case studies" /></a>
</p>

<br>

## 👋 What I fix

I'm a Senior Mobile & Full-Stack AI Engineer — 7 years of Flutter inside 11 years of mobile — with native iOS, Android and macOS (Swift, SwiftUI, Kotlin). When a package can't do the job, I write the plugin or platform channel myself. I build with AI coding agents and own the architecture and code review. I fix apps that break offline, lose data on sync, fail on real-world edge cases, mishandle payments and subscriptions — and now, AI features that have to respect privacy. I own the work from architecture to App Store and Google Play release.

<br>

## 🧩 Problems I've solved

| The problem | What I did | Result |
|---|---|---|
| **Prayer times were wrong at high latitudes.** Users in far-northern cities saw times that didn't match their local schedule; earlier fixes had failed. | Traced it to the sunrise/sunset calculation; built a new offline prayer-time engine | Correct times where they were wrong before, online or offline |
| **A receipt scanner too slow for a FinTech reimbursement flow.** Users also waited on a spinner during verification. | Native scanner (Swift/Java) behind Flutter; live WebSocket verification progress; offline claims with sync; instant payout | ~0.5 s per code; reimbursement ~5–10 s after the scan |
| **Stripe and Apple payments that disagreed** in a subscription app. Apple tracks purchases per Apple ID, the app per account. | As team lead, redesigned one account-level entitlement model for both payment systems, with duplicate-purchase detection | After ~2 years in development, approved and live within ~1 month |
| **Learning apps that broke without internet.** | Led 6 developers; device as the source of truth with a Firebase/SQLite sync layer | Two apps passed 100,000 downloads each |
| **Lawyers losing billable hours.** | Built [Hourwise](https://apps.apple.com/us/app/hourwise-billable-hours/id6811420308) solo: passive capture, on-device learning from corrections, LEDES exports | Live on the Mac App Store; work history never leaves the Mac |
| **Releases took an hour and waited on one laptop.** | Fastlane + GitHub Actions pipeline | ~10–20 minutes per release |

<p align="right"><a href="https://ehsanur.com">Full case studies →</a></p>

<br>

## 🚀 Building now: Hourwise

Private, AI-assisted timekeeping and billing for solo lawyers and small firms · founder and sole engineer · *closed source*

| Status | Problem it solves | Stack |
|:---:|---|---|
| ![Live](https://img.shields.io/badge/LIVE-1F4D3A?style=flat-square) | Billable time lost to forgotten timers; on-device learning assigns work to client matters | SwiftUI · AppKit · SQLite/GRDB · StoreKit 2 |
| ![Now](https://img.shields.io/badge/NOW-C9972F?style=flat-square) | Lawyers still write billing narratives by hand | Apple Foundation Models (on-device) |
| ![Next](https://img.shields.io/badge/NEXT-2F6B52?style=flat-square) | Meetings never become time entries | ScreenCaptureKit · SpeechAnalyzer · on-device models |
| ![Next](https://img.shields.io/badge/NEXT-2F6B52?style=flat-square) | Firms need seats and sync across Mac, iPhone, Android | Python · FastAPI · PostgreSQL · CRDT sync · Flutter |

<br>

## 📦 Open source

| Package | The problem it removes |
|---|---|
| **[flutter_crdt_sync_kit](https://pub.dev/packages/flutter_crdt_sync_kit)** | Two devices edit the same data offline and one change silently overwrites the other. CRDT merge, Supabase/REST adapters. |
| **[local_voice](https://pub.dev/packages/local_voice)** | Voice commands that need the cloud, an API key and a connection. |
| **[flutter_a11y_lens](https://pub.dev/packages/flutter_a11y_lens)** | Accessibility bugs found late by users or auditors — flags WCAG issues live. |

<p align="right"><a href="https://pub.dev/publishers/ehsanur.com/packages">My packages on pub.dev →</a></p>

<br>

## 🛠️ Tools I use to solve them

<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,swift,kotlin,androidstudio,apple,py,fastapi,postgres,sqlite,firebase,supabase,githubactions&perline=8" alt="Flutter, Dart, Swift, Kotlin, Android, Apple, Python, FastAPI, PostgreSQL, SQLite, Firebase, Supabase, GitHub Actions" />
</p>

<br>

## 🤝 Working with me

- **Remote from Bangladesh (UTC+6).** Full-time or contract; no relocation or visa sponsorship required; works with any time zone with a flexible core overlap.
- **Your hours:** three years working an overseas team's hours.
- **Async by default:** a written update every day — shipped, blocked, needed.
- **Ownership:** architecture → code → tests → CI/CD → store approval → maintenance.

<p align="center">
  <a href="mailto:mail@ehsanur.com"><img src="https://img.shields.io/badge/Email%20me-mail@ehsanur.com-C9972F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<!-- Footer -->
<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="" />
</p>
