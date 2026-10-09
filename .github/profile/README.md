<div align="center">

# Google Developer Groups on Campus — USTO-MB
### Université des Sciences et de la Technologie d'Oran Mohamed-Boudiaf (USTO-MB)
**Oran, Algeria (Wilaya 31)**

[![GDG Community](https://img.shields.io/badge/GDG%20Community-USTO--MB-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://gdg.community.dev)
[![GitHub Organization](https://img.shields.io/badge/GitHub-gdg--usto--mb-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gdg-usto-mb)
[![Location](https://img.shields.io/badge/Location-Oran%2C%20Algeria-EA4335?style=for-the-badge&logo=google-maps&logoColor=white)]()
[![Focus](https://img.shields.io/badge/Focus-Open%20Source%20%7C%20Cloud%20%7C%20AI%20%7C%20Web-34A853?style=for-the-badge)]()

<p align="center">
  A student-led developer community and technical innovation incubator at USTO-MB. We bridge the divide between theoretical computer science curricula and production-grade software engineering through peer learning, open-source development, and national community platforms.
</p>

</div>

---

## 📌 Mission & Strategic Goals

**GDG on Campus USTO-MB** is university-recognized and supported by Google for Developers. Our primary objective is to cultivate high-caliber engineering talent capable of architecting, deploying, and maintaining scalable, secure digital systems.

### Core Objectives:
1. **Bridge Academia & Production Engineering**: Transition students from classroom exercises to real-world software architecture, industry standards (TDD, CI/CD, IaC), and collaborative Git workflows.
2. **Build Public-Good Digital Infrastructure**: Develop and maintain open-source applications that solve concrete societal and university challenges across Algeria (e.g., student federation, national event synchronization, academic tooling).
3. **Foster Technical Leadership & Open Source Culture**: Cultivate active contributors who can lead workshops, publish technical research, and participate in international competitions such as the annual **Google Solution Challenge**.
4. **Connect Regional & National Ecosystems**: Serve as Western Algeria's primary student developer hub, interconnecting with developer communities across all 58 Algerian wilayas.

---

## 🚀 Flagship Projects & Engineering Ecosystem

Our repositories focus on building robust, modular software using modern web frameworks, serverless cloud architectures, and machine learning pipelines.

### 🌟 [NACS Platform (National Association of Campus Societies)](https://github.com/sirgio03/NACS-BETA)
A production web platform and administrative governance portal federating Algerian university student societies across all 58 wilayas.
- **Frontend**: Angular 20 Standalone architecture, Angular Signals reactive state, strictly typed TypeScript.
- **Backend**: Firebase Cloud Functions v2 (Node.js 24 LTS runtime) enforcing a **server-side mutation boundary**.
- **Security & Data Layer**: Cloud Firestore with strict default-deny rules, Firebase App Check with reCAPTCHA Enterprise, and raster-only Cloud Storage policies (Zero SVG tolerance for Stored XSS prevention).
- **Core Solved Problems**:
  - Eliminates **±3-day event date conflicts** between tech clubs across wilayas via an automated proximity detector.
  - Centralizes verified student society profiles with zero personal data leakage.
  - Maintains an immutable national showcase of university hackathon projects and open-source tools.

### 🌟 Google Solution Challenge Initiatives
Annual engineering tracks addressing the **United Nations 17 Sustainable Development Goals (SDGs)** utilizing Google technologies (Firebase, Google Cloud Platform, TensorFlow, Flutter):
- AI-driven agricultural analytics for arid regional climates.
- Accessible student health, scheduling, and academic collaboration tooling.

### 🌟 Campus Utilities & Open Source Tooling
- Modular libraries, authentication helpers, and UI design token kits tailored for Algerian university workflows.
- Reusable GitHub Actions workflows and security validation templates for student projects.

---

## 🛠️ Technical Focus Tracks & Stack Matrix

Our community operates structured technical divisions providing guided mentorship and code review:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        GDG on Campus USTO-MB                           │
│                         Technical Tracks                               │
└───────────────────────────────────┬────────────────────────────────────┘
                                    │
       ┌───────────────┬────────────┴───┬──────────────┬──────────────┐
       ▼               ▼                ▼              ▼              ▼
  [ Web & SPA ]  [ Cloud/Backend ] [ Mobile Dev ]   [ AI & ML ]   [ DevOps/Sec ]
   Angular 20      Cloud Functions    Flutter        TensorFlow      GitHub CI/CD
   TypeScript      Node.js 24 runtime Jetpack Comp.  Vertex AI       App Check
   Signals / RxJS  Cloud Firestore    Dart / Kotlin  Gemini API      Firestore TDD
```

| Domain | Primary Technologies | Practical Competencies Emphasized |
| :--- | :--- | :--- |
| **Frontend & Web** | Angular 20, TypeScript, SCSS, RxJS, Angular Signals | Component-driven architecture, reactivity, SSR/hydration, accessibility, Core Web Vitals optimization. |
| **Cloud & Serverless** | Google Cloud Platform (GCP), Firebase, Cloud Functions v2, Firestore | Serverless REST/Callable endpoints, atomic transactions, composite indexing, event-driven architecture. |
| **Mobile Engineering**| Flutter, Dart, Android SDK, Kotlin, Jetpack Compose | State management (Bloc/Signals), cross-platform deployment, local caching, offline-first synchronization. |
| **AI & Machine Learning** | Python, TensorFlow, PyTorch, Google Cloud Vertex AI, Gemini API | Supervised modeling, LLM application engineering, prompt design, data pipelines, Edge AI deployment. |
| **DevOps & Security** | GitHub Actions, Firebase Emulator Suite, App Check, Docker | Automated testing (unit & rules TDD), zero-trust security modeling, preview channel automation, secret isolation. |

---

## 🏛️ Community Programs & Activities

Throughout the academic year, GDG on Campus USTO-MB organizes technical initiatives designed to upskill students at all levels:

- 💻 **DevFest Oran**: Annual flagship tech conference gathering student developers, professional engineers, and industry leaders for deep-dive technical sessions and workshops.
- 🧪 **Google Cloud & Flutter Study Jams**: Hands-on guided codelab cohorts where participants earn Google Cloud skill badges and build deployable applications.
- ⚡ **Hackathons & Ideathons**: 24- to 48-hour intensive building sprints focusing on solving university, community, and national challenges.
- 🔍 **Architecture & Code Review Clinics**: Weekly peer reviews where student pull requests are reviewed by core leads for clean code, design patterns, and test coverage.
- 🎙️ **Tech Talks & Speaker Sessions**: Technical lectures on systems engineering, cloud architecture, cybersecurity, and technical career readiness.

---

## 🤝 Student Developer Contribution Standard

We welcome contributions from USTO-MB students and peer developer communities across Algeria. All organization repositories adhere to strict software quality baselines.

### 1. Branching Workflow
- `main` / `prod`: Production releases only. Protected branch; requires PR approval and passing CI.
- `staging` / `develop`: Integration branches for validated code.
- Feature branches: `feat/<issue-id>-<short-description>`
- Bugfix branches: `fix/<issue-id>-<short-description>`

### 2. Commit Protocol
We enforce **Conventional Commits**:
```bash
feat(calendar): add wilaya filter to national agenda viewport
fix(auth): handle expired token edge case in session guard
test(rules): add negative test cases for unauthorized profile role update
docs(api): document callable function payload schemas
```

### 3. Pre-PR Checklist
Before requesting review on any GDG USTO-MB repository:
- [ ] Code builds without warnings or errors under strict TypeScript compiler flags.
- [ ] Unit tests pass locally (Karma / Node / Flutter test).
- [ ] Security rules tests pass against local emulators (`@firebase/rules-unit-testing`).
- [ ] No API keys, credentials, or `.env` files are tracked in Git.
- [ ] Conventional commit syntax followed for all commits.

---

## 🌐 Connect With Us

Stay connected with our core organizing team, announcements, and upcoming events:

- 🌍 **GDG Community Platform**: [gdg.community.dev/gdg-on-campus-universite-des-sciences-et-de-la-technologie-doran-mohamed-boudiaf-oran-algeria/](https://gdg.community.dev)
- 🐙 **GitHub Organization**: [github.com/gdg-usto-mb](https://github.com/gdg-usto-mb)
- 🏫 **Campus**: Université des Sciences et de la Technologie d'Oran Mohamed-Boudiaf (USTO-MB), BP 1505 El M'naouer, Oran, Algeria
- 📧 **Contact**: Reach out via our official community page or open a discussion on our repositories.

---

<div align="center">
  <sub>Built with purpose by the student developer community of <b>GDG on Campus USTO-MB</b>.</sub>
</div>
