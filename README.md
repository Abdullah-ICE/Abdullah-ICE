<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:02569B,50:0175C2,100:13B9FD&height=220&section=header&text=MD.%20ABDULLAH-AL-MAMUN&fontSize=40&fontAlignY=36&desc=Flutter%20Developer%20%7C%20Mobile%20Application%20Engineer%20%7C%20Cross-Platform%20%26%20Offline-First%20Systems&descFontSize=15&descAlignY=58&fontColor=ffffff" alt="Md. Abdullah-Al-Mamun Banner" width="100%" />

  <!-- Animated Typing SVG Headline -->
  <a href="https://abdullah-al-mamun-six.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&duration=3000&pause=1000&color=02569B&center=true&vCenter=true&width=750&lines=Building+Production+Android%2C+iOS+%26+Desktop+Apps;Clean+Architecture+%7C+Riverpod+%7C+Offline-First+SQLite;High-Throughput+Systems+%7C+Atomic+Concurrency+Control;Google+ML+Kit+Vision+%7C+Dart+Isolates+%7C+Hardware+Bridges" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>B.Sc. in Information & Communication Engineering (ICE)</strong> • Bogura, Bangladesh
  </p>

  <!-- Quick Action & Social Badges -->
  <p align="center">
    <a href="https://abdullah-al-mamun-six.vercel.app/" target="_blank">
      <img src="https://img.shields.io/badge/Live_Portfolio-abdullah--al--mamun-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live Portfolio" />
    </a>
    <a href="https://www.linkedin.com/in/abdullah-ice/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-abdullah--ice-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="mailto:abdullah.mamun8191@gmail.com">
      <img src="https://img.shields.io/badge/Email-abdullah.mamun8191%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <a href="https://play.google.com/store/apps/developer?id=iDeatedLab" target="_blank">
      <img src="https://img.shields.io/badge/Google_Play-Production_Apps-34A853?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play" />
    </a>
    <a href="https://github.com/Abdullah-ICE?tab=repositories">
      <img src="https://img.shields.io/badge/GitHub-50+_Repos-24292e?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repositories" />
    </a>
  </p>

</div>

---

### 👨‍💻 Executive Summary

I am a **Flutter Developer & Mobile Application Engineer** with an academic foundation in **Information & Communication Engineering (B.Sc. ICE)** from TMSS Engineering College (affiliated with University of Rajshahi).

I specialize in engineering **cross-platform applications (Android, iOS, Windows Desktop, Web)** designed with **Clean Architecture, MVVM, and offline-first resilience**. My production track record spans hyper-local logistics engines with atomic concurrency handling, CBT mental health platforms, enterprise desktop POS systems synchronizing multi-entity local databases, and on-device computer vision systems.

- 🔭 **Current Role:** Junior Mobile Application Developer at **[iDeatedLab](https://ideatedlab.com)** (Bogura, Bangladesh)
- 🚀 **Flagship Deployments:** Apps running live on **Google Play Store**, enterprise desktop environments, and IoT telematics hardware
- 🧠 **Architectural Philosophy:** Strict separation of concerns (Clean Architecture), zero UI frame-drops, resilient local persistence (`SQLite` / `sqflite_common_ffi`), and atomic cloud state synchronization (`runTransaction`)
- 🛠️ **Deep Specializations:** Dart Isolates, Background Services, Exact Alarms, Hardware Bridges (Kotlin `MethodChannel`, ESC/POS Thermal Printing, GPS/GSM NMEA parsers), and Google ML Kit on-device vision

---

### 🏛️ Engineering Metrics & Core Highlights

<div align="center">

| 📱 **4+ Apps on Google Play** | 🖥️ **Enterprise Desktop POS** | ⚡ **Atomic Concurrency** | 📦 **Open-Source Dart Package** | 📡 **IoT & Telematics Systems** |
| :---: | :---: | :---: | :---: | :---: |
| Hyperlocal logistics, wellness, and blood donation | 4 integrated apps with offline 9-entity sync | Firestore `runTransaction` race-condition free | 240+ countries phone parser & formatter | GPS/GSM tracking & autonomous gas sensors |

</div>

---

### 🏆 Featured Production Ecosystems & Engineering Systems

#### 1. [Pashey Achi — Hyperlocal On-Demand Logistics Ecosystem](https://play.google.com/store/apps/details?id=com.abmamun.pashey_achi)
> **Stack:** Flutter • Dart • Cloud Firestore • PHP REST API • SQLite • FCM • MVVM • Provider  
> **Play Store Links:** [Customer App](https://play.google.com/store/apps/details?id=com.abmamun.pashey_achi) • [Rider App](https://play.google.com/store/apps/details?id=com.abmamun.pashey_achi_rider)

- **3-Tier Distributed Architecture:** Complete end-to-end ecosystem connecting Customer, Rider, and Central Admin apps across 10+ service verticals (food, grocery, emergency pharmacy, ambulance dispatch).
- **Atomic Concurrency Control:** Implemented Firestore transactions (`runTransaction`) and batch writes to eradicate race conditions during simultaneous multi-rider delivery claims.
- **Resilient Notification & Cache Pipeline:** Coupled Firebase Cloud Messaging (FCM) high-priority channels with SQLite local caching and lifecycle-aware stream management for uninterrupted operations under spotty network conditions.

```
[Customer Request] ──► [Firestore Atomic Batch/Transaction] ──► [Rider Pool Broadcast via FCM]
                                │                                          │
                                └──► [Local SQLite Cache & Offline Sync] ◄─┘
```

---

#### 2. Restomgr POS — Enterprise Restaurant Management Ecosystem
> **Stack:** Flutter (Desktop Windows) • Dart • Riverpod • `sqflite_common_ffi` • REST API • Inno Setup • GitHub Actions CI/CD  
> **Status:** Production Enterprise Workstation & Mobile Suite

- **Quad-App Ecosystem:** Engineered 4 interconnected applications: **Manager Desktop POS Workstation**, **QR-Based Customer Web App**, **Waiter Mobile App**, and **Customer Mobile App**.
- **Offline-Resilient Sync Engine:** Architected local persistence utilizing `sqflite_common_ffi` with memory fallback, auto-reconciling 9 core business entities (menus, tables, staff, split-coupons, multi-account ledger) with atomic local stock deduction.
- **Hardware Integration & Automated Builds:** Built dual-mode thermal receipt printing (Kitchen Display System KDS tickets + POS invoices) and automated Windows installer packaging using GitHub Actions CI/CD and Inno Setup.

---

#### 3. [Blood Bondhu — Real-Time Emergency Blood Donation Platform](https://play.google.com/store/apps/details?id=com.abmamun.bloodbondhu)
> **Stack:** Flutter • Dart • Cloud Firestore • FCM • PHP • REST API • MVVM  
> **Play Store Link:** [Blood Bondhu on Google Play](https://play.google.com/store/apps/details?id=com.abmamun.bloodbondhu)

- **Instant Donor Matchmaking:** Real-time geolocation-aware donor discovery engine with emergency push notification dispatch via Firebase Cloud Messaging.
- **Automated Medical Rules:** Programmed 90-day physiological donor eligibility calculation and a 5-minute anti-spam rate limiter.
- **Privacy-First Architecture:** Integrated secure contact protection with phone-number token masking and mutual consent acceptance protocols.

---

#### 4. [DeskFit — Workplace Posture & Sedentary Habit Tracker](https://play.google.com/store/apps/details?id=com.ideatedlab.deskfit)
> **Stack:** Flutter • Riverpod • SQLite • Dart Isolates • Exact Alarms • Canvas Animations • In-App Purchases  
> **Play Store Link:** [DeskFit on Google Play](https://play.google.com/store/apps/details?id=com.ideatedlab.deskfit)

- **Isolate-Based Background Engine:** Engineered an isolated background thread utilizing Android `AlarmManager` exact alarms for battery-efficient sleep mode and missed-break catch-up.
- **Sensory Interaction:** Custom hold-to-stand timer powered by tactile non-linear haptic feedback, custom Canvas procedural animations, and reaction metrics.
- **Offline Analytics & Internationalization:** Local SQLite habit history, streak computation algorithms, In-App Purchases (IAP), and 7-language localization (`l10n`).

---

#### 5. [Unload: Brain Dump Journaling — Mental Wellness Platform](https://play.google.com/store/apps/details?id=com.ideatedlab.unload)
> **Stack:** Flutter • Riverpod • Cloud Firestore • AudioPlayers • Firebase Auth • l10n  
> **Play Store Link:** [Unload on Google Play](https://play.google.com/store/apps/details?id=com.ideatedlab.unload)

- **Cognitive Reframing Engine:** CBT-inspired mental wellness app featuring mood categorization, thought restructuring workflows, and reactive Firestore streams.
- **Mindful Audio & Visuals:** Built parametric mindfulness breathing animations synchronized with multi-track ambient audio layering using `AudioPlayers`.
- **Localization:** Bilingual architecture with native English and Bengali (`bn`) localization.

---

#### 6. Homelyx — Smart Home Asset & Warranty Management Platform
> **Stack:** Flutter • Riverpod • SQLite • Clean Architecture • Firebase (Auth/FCM/FIAM) • Google OAuth  
> **Status:** Production Architecture

- **Hierarchical Domain Modeling:** Designed multi-property asset graphs (`Homes` → `Rooms` → `Appliances`) backed by SQLite relational schemas with foreign-key cascading deletes.
- **Dynamic Warranty Calculations:** Engineered real-time depreciation algorithms, service warranty countdowns, and a document vault with zoomable PDF/image rendering.
- **Dual Cloud/Push Integration:** Combined Google OAuth, runtime Firebase In-App Messaging suppression, and custom foreground notification channels.

---

#### 7. RoutineX — Intelligent Routine & On-Device Computer Vision Engine
> **Stack:** Flutter • Riverpod • SQLite • Google ML Kit • Camera Streams • Kotlin MethodChannels • FlChart  
> **Status:** Active Development

- **On-Device Computer Vision:** Streams live camera frames into Google ML Kit for real-time facial liveness verification to dismiss mission-critical wake-up alarms.
- **Native Android Lockscreen Intents:** Kotlin `MethodChannel` bridge triggering high-priority full-screen lockscreen alarms overriding silent modes.
- **Algorithmic Analytics:** Offline SQLite persistence paired with FlChart for heuristic routine optimization based on user habit archetypes.

---

#### 8. Hardware & IoT Telematics Systems
> **Stack:** Embedded C/C++ • Arduino Uno • SIM808 / SIM800L GSM • NMEA Telematics • MQ-6 Sensor

- **Vehicle Tracking & Anti-Theft Security:** Telematics hardware combining Arduino Uno and SIM808 GPS/GSM module to acquire satellite NMEA coordinates, transmit instant SMS alerts, and plot live locations directly on Google Maps.
- **Autonomous LPG Gas Leak Detector:** Autonomous safety appliance pairing MQ-6 gas density sensors with SIM800L module to trigger opto-isolated relay fans and dispatch emergency SMS notifications.

---

### 📦 Open-Source Packages & Libraries

| Repository | Description | Technologies |
| :--- | :--- | :--- |
| 📦 **[phone_number_formatter](https://github.com/Abdullah-ICE/phone_number_formatter)** | Lightweight Flutter & pure Dart package to format, parse, and validate phone numbers for 240+ countries. Features real-time `TextInputFormatter`, auto-zero stripping, searchable country picker dialog, and full 11-digit Bangladesh validation without native dependencies. | `Dart` `Flutter` `Regex` `Pub.dev Ready` |
| ⚡ **[OmniWire](https://github.com/Abdullah-ICE/OmniWire)** | High-speed data transfer and transparent synchronization protocol architecture designed for modern connected devices. | `Dart` `Sockets` `Data Sync` |
| ⚙️ **[background-service](https://github.com/Abdullah-ICE/background-service)** | Robust background processing patterns using Dart Isolates, Android Foreground Services, and resilient lifecycle management. | `Dart` `Kotlin` `Android Services` |
| 🗂️ **[Task-Manager-with-GetX-](https://github.com/Abdullah-ICE/Task-Manager-with-GetX-)** | Production-structured task management client consuming REST APIs with token persistence, state caching, and reactive GetX state. | `Flutter` `GetX` `REST API` |

---

### 🛠️ Technical Arsenal & Skill Matrix

<div align="center">

#### 💻 Programming Languages
<p>
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C/C++" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
</p>

#### 📱 Mobile, Desktop & Cross-Platform
<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Android_SDK-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/iOS_Deployment-000000?style=for-the-badge&logo=apple&logoColor=white" alt="iOS" />
  <img src="https://img.shields.io/badge/Flutter_Desktop-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Flutter Desktop" />
  <img src="https://img.shields.io/badge/Method_Channels-4A154B?style=for-the-badge&logo=slack&logoColor=white" alt="MethodChannels" />
  <img src="https://img.shields.io/badge/Localization_(l10n)-2E7D32?style=for-the-badge&logo=google-translate&logoColor=white" alt="Localization" />
</p>

#### 🏗️ Architecture & State Management
<p>
  <img src="https://img.shields.io/badge/Clean_Architecture-1572B6?style=for-the-badge&logo=blueprint&logoColor=white" alt="Clean Architecture" />
  <img src="https://img.shields.io/badge/MVVM_Pattern-008080?style=for-the-badge&logo=blueprint&logoColor=white" alt="MVVM" />
  <img src="https://img.shields.io/badge/Riverpod-2B3A42?style=for-the-badge&logo=flutter&logoColor=47C5FB" alt="Riverpod" />
  <img src="https://img.shields.io/badge/GetX-800080?style=for-the-badge&logo=flutter&logoColor=white" alt="GetX" />
  <img src="https://img.shields.io/badge/Provider-0052CC?style=for-the-badge&logo=flutter&logoColor=white" alt="Provider" />
  <img src="https://img.shields.io/badge/Offline--First_Design-E65100?style=for-the-badge&logo=databricks&logoColor=white" alt="Offline-First" />
</p>

#### 💾 Local Persistence & Data Synchronization
<p>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/sqflite-0288D1?style=for-the-badge&logo=sqlite&logoColor=white" alt="sqflite" />
  <img src="https://img.shields.io/badge/sqflite__common__ffi-01579B?style=for-the-badge&logo=windows&logoColor=white" alt="sqflite_common_ffi" />
  <img src="https://img.shields.io/badge/Foreign_Key_Cascades-455A64?style=for-the-badge&logo=database&logoColor=white" alt="FK Cascades" />
  <img src="https://img.shields.io/badge/Cache_Invalidation-37474F?style=for-the-badge&logo=redis&logoColor=white" alt="Cache Invalidation" />
</p>

#### ☁️ Backend, Cloud & APIs
<p>
  <img src="https://img.shields.io/badge/Cloud_Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Cloud Firestore" />
  <img src="https://img.shields.io/badge/Firebase_Auth-FFA000?style=for-the-badge&logo=firebase&logoColor=white" alt="Firebase Auth" />
  <img src="https://img.shields.io/badge/Push_Notifications_(FCM)-FF6F00?style=for-the-badge&logo=firebase&logoColor=white" alt="FCM" />
  <img src="https://img.shields.io/badge/RESTful_APIs-009688?style=for-the-badge&logo=postman&logoColor=white" alt="RESTful APIs" />
  <img src="https://img.shields.io/badge/JWT_Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="OAuth" />
</p>

#### 🔬 Advanced Engineering & Hardware Integration
<p>
  <img src="https://img.shields.io/badge/Dart_Isolates-0D47A1?style=for-the-badge&logo=dart&logoColor=white" alt="Dart Isolates" />
  <img src="https://img.shields.io/badge/Firestore_runTransaction-FF8F00?style=for-the-badge&logo=firebase&logoColor=black" alt="runTransaction" />
  <img src="https://img.shields.io/badge/Google_ML_Kit_(Vision)-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google ML Kit" />
  <img src="https://img.shields.io/badge/AlarmManager_Exact-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="AlarmManager" />
  <img src="https://img.shields.io/badge/Thermal_Printing_(ESC%2FPOS)-263238?style=for-the-badge&logo=print&logoColor=white" alt="ESC/POS" />
  <img src="https://img.shields.io/badge/Arduino_Telematics-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino" />
</p>

#### 🛠️ Tooling, DevOps & Performance Profiling
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub_Actions_CI%2FCD-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Flutter_DevTools-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="DevTools" />
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
  <img src="https://img.shields.io/badge/Inno_Setup-107C41?style=for-the-badge&logo=windows&logoColor=white" alt="Inno Setup" />
</p>

</div>

---

### 💼 Professional Experience

```markdown
┌─────────────────────────────────────────────────────────────────────────────┐
│ iDeatedLab • Bogura, Bangladesh                                             │
│ Junior Mobile Application Developer                           Sep 2025 – Now │
├─────────────────────────────────────────────────────────────────────────────┤
│ • Architect and maintain production Flutter mobile (Android/iOS) apps with  │
│   modular Clean Architecture and reusable enterprise component design.       │
│ • Implement compile-safe state flows with Riverpod and GetX, connecting     │
│   REST APIs, JWT token lifecycles, and resilient network exception handling. │
│ • Integrate Firebase backend ecosystems (Firestore, Auth, FCM, FIAM) and    │
│   offline persistence engines using SQLite.                                  │
│ • Profile frame drops, memory allocations, and widget re-render overhead    │
│   using Flutter DevTools to ensure steady 60fps performance budgets.        │
└─────────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────────┐
│ Atmotech IT & Software Firm • Bogura, Bangladesh                            │
│ Mobile Application Development Intern                     Jan 2026 – Jul 2026│
├─────────────────────────────────────────────────────────────────────────────┤
│ • Developed responsive cross-platform interfaces adhering to Material 3     │
│   design principles and reactive state paradigms.                           │
│ • Integrated REST endpoints and Firebase real-time sync systems.             │
│ • Pair-programmed with senior engineering staff on code refactoring, bug    │
│   resolution, and automated build pipelines.                                │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

### 🎓 Academic Foundation

- **B.Sc. in Information & Communication Engineering (ICE)**  
  *TMSS Engineering College (Affiliated with University of Rajshahi)* • **2020 – 2025**  
  *Focus:* Mobile Systems, Object-Oriented Software Engineering, Computer Networks, Database Architecture, Telecommunications & IoT Hardware.
- **Higher Secondary Certificate (HSC) — Science**  
  *Govt. Model School & College, Sonatola, Bogura* • **Completed 2019**

---

### 📈 GitHub Velocity & Consistency

<div align="center">

  <a href="https://github.com/Abdullah-ICE">
    <img src="https://streak-stats.demolab.com/?user=Abdullah-ICE&theme=tokyonight&hide_border=true&border_radius=8" alt="GitHub Streak" />
  </a>

  <br/><br/>

  <p>
    <img src="https://img.shields.io/badge/Engineering_Mindset-Clean_Code_%26_High_Availability-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Mindset" />
    <img src="https://img.shields.io/badge/Architecture-Offline--First_%7C_Clean_Arch_%7C_MVVM-007ACC?style=flat-square" alt="Arch" />
    <img src="https://img.shields.io/badge/Commitment-Continuous_Learning_%26_Refactoring-2EA44F?style=flat-square&logo=github&logoColor=white" alt="Commitment" />
  </p>

</div>

---

### 📫 Connect & Collaborate

Whether you are looking to build a high-performance **offline-first mobile app**, need to solve **complex concurrency or database synchronization** challenges, or want to discuss modern cross-platform engineering—let's connect!

<div align="center">

  <a href="https://abdullah-al-mamun-six.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Website-abdullah--al--mamun-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/abdullah-ice/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-abdullah--ice-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:abdullah.mamun8191@gmail.com">
    <img src="https://img.shields.io/badge/Email-abdullah.mamun8191%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://wa.me/8801571348191" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-%2B880_1571--348191-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
  </a>

  <br/><br/>
  
  <sub>Crafted with engineering precision by <strong>Md. Abdullah-Al-Mamun</strong> • Powered by Flutter & Dart Passion</sub>

</div>
