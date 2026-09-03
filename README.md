<h1 align="center">Atiqur Rahman</h1>

<p align="center">
  <b>Senior Android Engineer @ MEGA</b> — privacy-first cloud storage for 10M+ people<br>
  I make sync reliable and cold starts fast.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/atiqur-rahman-ab267379"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:atiq.it@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img alt="Based in Bangladesh, working remotely" src="https://img.shields.io/badge/Bangladesh%20%C2%B7%20Remote-2F6F62?style=for-the-badge">
</p>

---

- 🔭 **Currently** — Sync & Backup on MEGA Android: folder pickers, Cloud Explorer, Sync Dashboard, Device Center
- ⚡ **Focus** — where Android buckles under real load: background work, file I/O, cold start, ANRs
- 🌱 **Learning** — Kotlin Multiplatform, and how much of the boring half AI tooling can take
- 💬 **Ask me about** — Compose, WorkManager, Storage Access Framework, or why an app takes two seconds to start

### 🛠️ Stack

**Languages**<br>
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
<img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
<img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white">

**Android**<br>
<img alt="Jetpack Compose" src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white">
<img alt="Coroutines and Flow" src="https://img.shields.io/badge/Coroutines%20%2F%20Flow-2F6F62?style=flat-square">
<img alt="Hilt" src="https://img.shields.io/badge/Hilt-2F6F62?style=flat-square">
<img alt="WorkManager" src="https://img.shields.io/badge/WorkManager-2F6F62?style=flat-square">
<img alt="Room" src="https://img.shields.io/badge/Room-2F6F62?style=flat-square">
<img alt="Retrofit" src="https://img.shields.io/badge/Retrofit-2F6F62?style=flat-square">
<img alt="Material 3" src="https://img.shields.io/badge/Material%203-757575?style=flat-square&logo=materialdesign&logoColor=white">

**Architecture &amp; testing**<br>
<img alt="Clean Architecture" src="https://img.shields.io/badge/Clean%20Architecture-2F6F62?style=flat-square">
<img alt="Multi-module" src="https://img.shields.io/badge/Multi--module-2F6F62?style=flat-square">
<img alt="JUnit" src="https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white">
<img alt="Turbine" src="https://img.shields.io/badge/Turbine-2F6F62?style=flat-square">
<img alt="Robolectric" src="https://img.shields.io/badge/Robolectric-2F6F62?style=flat-square">
<img alt="Espresso" src="https://img.shields.io/badge/Espresso-2F6F62?style=flat-square">

**Tooling &amp; cross-platform**<br>
<img alt="Gradle" src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
<img alt="Firebase" src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black">
<img alt="Kotlin Multiplatform" src="https://img.shields.io/badge/Kotlin%20Multiplatform-7F52FF?style=flat-square&logo=kotlin&logoColor=white">
<img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white">

### 📈 Measured at MEGA

| What | Change | How |
| :-- | :-- | :-- |
| Upload crashes | **▼ 35%** | Camera Uploads re-architected onto Clean Architecture + Coroutines, upload worker in its own module |
| Directory listing | **▲ 40%** | Cut Storage Access Framework IPC round trips, cached single-child lookups |
| ANR rate | **▼ 30%** | Fixed `Sync` repository and Camera Uploads preference threading; made eager sync flows lazy |
| Cold start | **▼ 20%** | MEGA SDK native library preloaded off the main thread, credential and preferences gateways cached |

### 🧩 Also built

- **Jetpack Compose PDF viewer** from scratch, with an in-document search engine on PdfiumCore
- **Native text extraction &amp; search (JNI)** contributed upstream to PdfiumAndroid
- **Material 3 migration** and modularization into shared feature modules across a large multi-module codebase

<sub>Ten years on Android — six of them leading mobile teams at Monstarlab before MEGA.</sub>
