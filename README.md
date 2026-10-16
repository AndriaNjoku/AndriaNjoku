# Hi, I'm Andria Njoku 👋

**Systems Architect • Android Specialist • Founder of [KarmaPolitics](https://karmapolitics.co.uk)**

I design and build software at the intersection of **civic intelligence**, **distributed systems**, and **human-centric AI**. My work is driven by a simple conviction: the world is already complicated enough—software should make power legible, tools should be owned by the people who use them, and truth should always be verifiable.

---

## 🏛️ KarmaPolitics: Evidence-Led Civic Accountability

> *"Less 'trust me.' More 'show me the record.'"*

Modern politics is engineered for distraction: soundbites, headlines, 10-second outrage clips, and unfulfilled pledges—with almost zero connection back to real power.

**[KarmaPolitics](https://karmapolitics.co.uk)** is my answer to this collapse of accountability. It is an end-to-end civic intelligence platform that tracks UK parliamentary activity, legislative votes, ministerial statements, and political speech in real time, grounding public discourse in **hard evidence and primary sources**.

```text
  UK Parliament / Hansard / Legislation.gov.uk
                      │
                      ▼
   Distributed Ingestion & Axiom Normalization (AWS / OpenSearch)
                      │
                      ▼
    Apollo GraphQL Federated Political Graph (REST + GQL)
         │                                       │
         ▼                                       ▼
  📱 Android App (Jetpack Compose)       🔮 Oracle AI Intelligence Engine
  • Tactile AI Newspaper ("Karma Matters") • Primary-source cited Q&A ("Receipts")
  • MP Cabinet & 7-Day Forecast Hits       • Evidence Quests & Lens Simplifier
  • Radical Privacy ("Views Aren't For Sale") • Verifiable Parliamentary Context
```

### Core Architecture & Capabilities

* **📱 Flagship Android App ([`AndriaNjoku/KarmaPolitics`](https://github.com/AndriaNjoku/KarmaPolitics))**
  * **Modern Reactive UI**: 100% Kotlin & Jetpack Compose, Coroutines, Flow, Hilt, Room offline caching, Material 3.
  * **"Karma Matters" AI Newspaper**: A weekly personalized broadsheet newspaper experience built with realistic 3D mesh page-curl physics, dynamic spine crease depth, and dual-screen broadsheet leaf turning.
  * **Interactive Cabinet Mechanics**: Users appoint real MPs to their Cabinet, track their voting records across issues, and make 7-day Focus predictions that put civic understanding to the test.
  * **Low-Latency Parliament Media Player**: Integrated ExoPlayer/Media3 streaming engine supporting parliamentary debate broadcasts, high-bitrate MP4/HLS streams, and accessible transport controls.
  * **Uncompromising Privacy**: Built on the strict principle that *"Your political views aren't for sale."* Zero behavioural tracking, client-isolated preference boundaries, and explicit consent modals.

* **⚙️ Distributed Backend ([`AndriaNjoku/KarmaPoliticsBackend`](https://github.com/AndriaNjoku/KarmaPoliticsBackend))**
  * **High-Throughput Ingestion Pipelines**: Continuous automated ingestion and entity resolution across UK Parliament APIs, Hansard debates, written questions, and official divisions.
  * **Federated Political Knowledge Graph**: Scalable Apollo GraphQL federation and REST APIs delivering sub-second response times for rich legislative queries and MP score histories.
  * **Axiom Normalization & Evidence Scoring**: Objective scoring algorithms that evaluate policy impacts, bill amendments, and member attendance without partisan bias.
  * **Resilient Infrastructure**: Event-driven AWS serverless architecture (Lambda, ECS Fargate, EventBridge, DynamoDB, OpenSearch, CDK) built for zero-downtime legislative data streaming.

* **🔮 Oracle Intelligence & Evidence Quests**
  * Translates opaque, centuries-old parliamentary legalese into crystal-clear plain English through **Oracle Lens**.
  * Every single AI response is anchored by **verifiable primary source receipts** (exact Hansard columns, division numbers, and official gazettes) with confidence indicators.
  * Crowdsources civic verification through **Evidence Quests**, letting citizens supply and vet primary sources to close evidence gaps in political claims.

---

## 🎙️ Daemon: Sovereign, Local-First Ambient AI

Beyond civic accountability, I believe software tools should belong entirely to the individuals who rely on them—not locked inside walled gardens or corporate subscription traps.

I am building **[Daemon](https://github.com/AndriaNjoku/Daemon)**: an open-source, self-hosted ambient intelligence daemon.

```text
  Wearable / Ambient Audio 🎙️ ──► Local Whisper Transcript ──► OpenClaw AI 🤖 ──► Obsidian Second Brain 🗂️
```

* **Local-First & Private**: Captures ambient speech, thoughts, and conversations, translating loose ideas into structured daily notes, tasks, and context graphs.
* **Direct Obsidian Integration**: Seamlessly pipes distilled thoughts into personal Markdown vaults without third-party cloud lock-in.

---

## 🛠️ Technical Arsenal

| Category | Technologies & Tools |
| :--- | :--- |
| **Mobile & Client** | Kotlin, Jetpack Compose, Android SDK, Coroutines & Flow, Android Architecture Components, Hilt / Dagger, Room, Media3 (ExoPlayer), PageCurl |
| **Backend & Distributed Systems** | Python, TypeScript, Node.js, Apollo GraphQL Federation, REST APIs, WebSockets, Fastify, Pydantic |
| **Cloud & DevOps** | AWS (Lambda, ECS Fargate, DynamoDB, OpenSearch, EventBridge, SQS/SNS, S3, CDK, CloudFront), Docker, Terraform, CI/CD Actions |
| **Data & AI Systems** | Retrieval-Augmented Generation (RAG), Semantic Vector Search, Autonomous Ingestion Agents, Hansard Scraping & Entity Resolution |
| **Engineering Values** | TDD / Unit Testing, Architecture Integrity, Accessible UI Design, Zero-Trust Privacy, Craftsmanship |

---

## 🧭 Principles & Engineering Philosophy

- **Accountability Over Rhetoric**: If power isn't legible and verifiable to everyday people, democracy becomes an illusion.
- **Deep Craft Over Superficial Velocity**: Polished physics, sub-frame animation fluidness, resilient offline states, and robust schema design matter.
- **Sovereign Computing**: People should own their data, their cognitive notes, and their political perspective without being packaged as algorithmic ad inventory.
- **Make the Complex Understandable**: Great engineering dissolves unnecessary friction and surfaces clarity from institutional noise.

---

## 🌐 Connect & Explore

- 💼 **Platform**: [karmapolitics.co.uk](https://karmapolitics.co.uk)
- 📱 **Android Client**: [github.com/AndriaNjoku/KarmaPolitics](https://github.com/AndriaNjoku/KarmaPolitics)
- ⚙️ **Backend System**: [github.com/AndriaNjoku/KarmaPoliticsBackend](https://github.com/AndriaNjoku/KarmaPoliticsBackend)
- 🧠 **Daemon Project**: [github.com/AndriaNjoku/Daemon](https://github.com/AndriaNjoku/Daemon)
- ✉️ **Contact**: [feedback@karmapolitics.co.uk](mailto:feedback@karmapolitics.co.uk)

---
*Building things because the world is complicated enough already.*
