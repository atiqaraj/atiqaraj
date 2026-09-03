## Atiqur Rahman

**Senior Android Engineer at MEGA** — privacy-first cloud storage and communications, 10M+ users.

> Ten years of Android for people who need it private and fast.

Senior Android engineer with 10+ years on customer-facing mobile products, including 3.5+ years
owning flagship features in MEGA's privacy-first app. Deep in Kotlin, Jetpack Compose,
Coroutines/Flow and Clean Architecture, with a security- and performance-first mindset. I take
end-to-end ownership — architecture, implementation, testing, analytics and launch — and lift team
quality through code reviews, documentation and mentorship.

`Remote · Bangladesh`  ·  `1,900+ commits at MEGA`  ·  `GitHub since 2016`

### Measured impact

Four changes in MEGA's Android app, each measured against the behaviour it replaced.

| Change | Delta | How |
| :-- | :-- | :-- |
| Upload-related crashes | **−35%** | Re-architected the Camera Uploads engine off a legacy implementation onto Clean Architecture with Kotlin Coroutines — upload worker extracted into a dedicated data module, plus cross-folder conflict detection |
| File access & directory listing | **+40% faster** | Removed Storage Access Framework bottlenecks: fewer IPC round trips and cached single-child lookups in the file layer |
| ANR rate | **−30%** | Fixed ANRs in Camera Uploads preferences and `Sync` repository threading, and converted eager sync flows to lazy execution — memory and CPU came down with them |
| Cold start | **−20%** | Pre-loaded the MEGA SDK native library on a background thread and cached the credential and preferences gateways, taking both off the UI-thread critical path |

### Experience

**Senior Android Engineer — MEGA** · Sep 2022 – Present
- Owned end-to-end Android delivery of the **Sync & Backup** experience — folder pickers, Cloud
  Explorer integration, Sync Dashboard and Device Center — across a large multi-module codebase.
- Re-architected **Camera Uploads** onto Clean Architecture with Coroutines, extracting the upload
  worker into a dedicated data module and adding cross-folder conflict detection.
- Built a modern **Jetpack Compose PDF viewer** from the ground up, including an in-document search
  engine on PdfiumCore, and contributed native text-extraction and search (JNI) to PdfiumAndroid.
- Drove modularization into shared feature modules, dependency-management cleanup and the
  **Material 3** migration.
- Strengthened quality with extensive unit and Robolectric coverage plus product-analytics
  instrumentation; mentored engineers through code reviews and technical documentation.

**Technical Lead — Monstarlab** · Jan 2016 – Aug 2022
- Led mobile teams through the full product lifecycle — requirements, architecture, development,
  testing and Play Store release — for client-facing apps.
- Architected apps from scratch on MVVM, Clean Architecture, Coroutines, Flow, RxJava and MVP,
  applying SOLID principles and design patterns.

**Backend Software Engineer — iBaax** · 2015  ·  **Software Engineer — SCSL** · 2014

### Stack

- **Languages** — Kotlin (10+ yrs) · Java · Dart · Python & JavaScript exposure
- **Android** — Jetpack Compose · Coroutines/Flow · RxJava · Hilt/Dagger · WorkManager · Room · Retrofit · Navigation · Paging 3 · Material 3
- **Architecture** — Clean Architecture · MVVM · MVP · SOLID · design patterns · multi-module · dependency injection
- **Testing** — JUnit · Mockito · Turbine · Robolectric · Espresso
- **Cross-platform** — Kotlin Multiplatform (KMP) · Flutter
- **Practice** — CI/CD · Git · Gradle · AI-assisted development · secure coding · multithreading · performance & memory profiling

### Public code

The production work lives in MEGA's private multi-module codebase. What's public here are focused
demos of APIs worth understanding properly.

- [**ResultAPIDemo**](https://github.com/atiqaraj/ResultAPIDemo) — deep dive into the Activity Result API, written when `onActivityResult()` was deprecated
- [**EspressoExample**](https://github.com/atiqaraj/EspressoExample) — instrumented UI testing patterns with Espresso
- [**firebaseauth**](https://github.com/atiqaraj/firebaseauth) — Firebase Authentication reference app

### Education

**M.Sc., Information Technology** · Jahangirnagar University · 2014–2015  
**B.Sc., Information Technology** · Jahangirnagar University · 2010–2013

---

[Email](mailto:atiq.it@gmail.com) · [LinkedIn](https://www.linkedin.com/in/atiqur-rahman-ab267379)
