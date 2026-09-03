## Atiqur Rahman

Android engineer at **MEGA** — privacy-first cloud storage for 10M+ people. I make sync reliable
and cold starts fast.

Kotlin and Compose day to day, and a lot of time in the parts of Android that buckle under
real-world load: background work, file I/O, sync. I like problems where the fix is measurable —
most of mine turn out to be threading, caching, or deleting a layer that shouldn't have existed.

### What I build

**Sync & Backup** on MEGA Android — folder pickers, Cloud Explorer integration, Sync Dashboard,
Device Center. Two-way sync is unforgiving: most of the work is conflict handling and keeping
state you can actually trust.

**Camera Uploads** — re-architected off a legacy engine onto Clean Architecture and Coroutines,
upload worker extracted into its own data module, cross-folder conflict detection added.

**A Compose PDF viewer**, from scratch, with an in-document search engine on PdfiumCore — which
meant first contributing native text extraction and search (JNI) upstream to PdfiumAndroid.

### Things I made faster

- **Upload crashes −35%** — the Camera Uploads re-architecture above
- **Directory listing +40%** — fewer Storage Access Framework IPC round trips, cached single-child lookups
- **ANR rate −30%** — fixed Camera Uploads preference reads and `Sync` repository threading, made eager sync flows lazy
- **Cold start −20%** — pre-loaded the MEGA SDK native library off the main thread, kept credential and preferences gateways out of the startup path

### Working with

- **Daily** — Kotlin · Jetpack Compose · Coroutines/Flow · Hilt · WorkManager · Room · Retrofit · Material 3
- **Shape of the code** — Clean Architecture · multi-module · dependency injection
- **Tests** — JUnit · Turbine · Robolectric · Espresso
- **Also** — Kotlin Multiplatform · Flutter · Java · Dart

### On this account

The production work lives in MEGA's private codebase, so most of what's here is forks I've read
through. The originals worth a look:

- [ResultAPIDemo](https://github.com/atiqaraj/ResultAPIDemo) — the Activity Result API, written when `onActivityResult()` was deprecated
- [EspressoExample](https://github.com/atiqaraj/EspressoExample) — instrumented UI testing patterns
- [firebaseauth](https://github.com/atiqaraj/firebaseauth) — Firebase Authentication reference app

Before MEGA I spent six years leading mobile teams at Monstarlab, shipping client apps end to end.

---

[Email](mailto:atiq.it@gmail.com) · [LinkedIn](https://www.linkedin.com/in/atiqur-rahman-ab267379)
