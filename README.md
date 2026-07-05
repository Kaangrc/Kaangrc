# Hi there, I'm Yusuf Kaan Gürcüoğlu 👋
### **Computer Engineer | Mobile & System Architecture Specialist**

Customizing and designing robust end-to-end digital products, scalable cross-platform mobile architectures, and secure multi-tenant web systems. I focus on structural integrity, reactive data flows, and clean code boundaries rather than just building interfaces.

⚙️ **Core Philosophy:** Real-world production engineering is about handling constraints, edge cases, data isolation, and failures gracefully.

---

## 📱 Shipped Production Apps (Closed Source / NDA)
*The source codes for these projects are proprietary, but they are live in production, serving active users, and available on the stores.*

### 🩺 **[PatientMesh](https://patientmesh.com)** 🔗 [App Store](https://apps.apple.com/tr/app/patientmesh/id6762303444?l=tr) | [Google Play](https://play.google.com/store/apps/details?id=com.patientmesh.app&pcampaignid=web_share)
* **Role:** Project Manager & Technical Lead
* **Ownership:** Solely responsible for the entire cross-platform mobile development lifecycle, architectural decisions, state management, and deployment processes from scratch.
* **System Overview:** A high-scale medical data and clinical form management platform designed for doctors and orthopedic decision-support pipelines.
* **Engineering Impact:** Established rigid data binding layers, role-based workflows, and decoupled presentation bounds to safely process sensitive clinical assets with zero downtime.

### 🧾 **Thiki — Warranty & Invoice Tracking** 🔗 [App Store](https://apps.apple.com/tr/app/thiki/id6758831569?l=tr) | [Google Play](https://play.google.com/store/apps/details?id=com.thiki.invoice.thiki&pcampaignid=web_share)
* **Role:** Lead Mobile Architect (Co-developed and shipped in a 2-person mobile team)
* **System Overview:** A localized production consumer app driving document intelligence, subscription models, and workspace collaboration across **28 locales**.
* **Architecture & State:** Implemented a feature-sliced, service-oriented architecture driven by a **Riverpod 3** reactive state layer, **GoRouter**, and **Hive** local caching. Features a cache-first offline read path with a 10-minute staleness TTL alongside online-required mutation barriers utilizing multi-state connectivity probing.
* **Security & Auth:** Deployed multi-provider auth (Google OIDC, Email, Anonymous guest sessions) with a custom guest-merge flow, alongside full **Apple Sign-In** implementations optimized via custom redirect pipelines on Android.
* **Monetization & Infrastructure:** Programmed a dual-tier monetization engine synced across client-side **RevenueCat** entitlements and database-level **PostgreSQL triggers**. The document pipeline integrates on-device **ML Kit Text Recognition** with an external Supabase AI Gateway edge function for dynamic LLM model routing and regex fallbacks.

---

## 💻 SaaS & Freelance Web Projects

### 🚗 **[CarViox — Cloud ERP for Automotive](https://carviox.com)**
* **Role:** Sole Architect & Full-Stack Engineer
* **System Overview:** A multi-tenant, serverless SPA designed to digitize automotive maintenance cards, shop-floor service operations, and rental fleets for small-to-medium businesses.
* **Architecture Highlights:** Developed with **React 19**, **TypeScript**, and **Vite**, backed entirely by **Firebase** (Auth, Cloud Firestore, Hosting, and App Check bot protection).
* **Data Isolation:** Designed a strict multi-tenant schema isolation using `ownerId` bindings across Firestore documents, hardened via explicit database security rules enforcing deny-by-default logic and strict soft-delete constraints (`allow delete: if false`).
* **Document Pipeline:** Engineered a programmatic client-side PDF template system responding to specific brand configurations, routed through a native Web Share API and WhatsApp deep-link communication pipeline.

### 🌐 **Commercial Web Projects**
High-performance, responsive corporate web spaces delivered as a freelance developer:
* 🚢 **[Sunmarine](https://sunmrn.com)** – Modern frontend architecture with smooth, performant responsive layouts.
* 🌿 **[Aroniaceae](https://www.aroniaceae.com)** – E-commerce rendering pipeline and modern product staging showcase.
* 🏛️ **[SK Mimarlık](https://xn--skmimarlk-2pb.com)** – Minimalist, SEO-optimized digital portfolio built for high-end architectural visibility.

---

## 🛠 Tech Stack & Engineering Tools

* **Languages:** Dart , JavaScript, TypeScript, Python, SQL.
* **Frameworks & UI:** Flutter (iOS, Android, Web), React 19, Tailwind CSS 4, Django REST.
* **State & Architecture:** Clean Architecture, BLoC / Cubit, Riverpod 3, Provider, Vertical Slices, MVVM.
* **Backend & Security:** Node.js, Cloud Firestore, Supabase, Firebase Auth, App Check, PostgreSQL RLS.
* **DevOps & Workflow:** Git & GitHub, Docker, CI/CD Pipelines, Postman, Jira.

---

## 📬 Let's Connect
* 💼 **LinkedIn:** [linkedin.com/in/kaangurcuoglu](https://www.linkedin.com/in/kaangurcuoglu/)
* 📧 **Email:** kaangurcuogluu@gmail.com
