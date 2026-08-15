### Hi, I'm Akshay 👋

MS Information Systems student at Northeastern University (Boston). I build across embedded systems, iOS, ML, and cloud infrastructure.

Portfolio: [akshaymrdev.vercel.app](https://akshaymrdev.vercel.app)

---

### Things I've built

- **EdgeSplit**: Disaggregated LLM inference that prefills on a laptop CUDA GPU and decodes on an Android phone, handing off raw sequence state over a checksummed TCP frame. V2 Cuts time-to-first-token 65 to 82% on Qwen3-0.6B, and a hand-tuned NEON accumulator in llama.cpp's `Q4_K×Q8_K` dot product adds 4.8% decode throughput on the phone. [Code](https://github.com/AMR5210/Edge-split) · [Demo](https://github.com/user-attachments/assets/2347ef21-61b7-4d75-b052-2c0447d69dc4)
- **MBTA Live**: Live MBTA arrivals, home-screen widgets, and lock-screen Live Activities on iOS, backed by a nine-service event-driven platform that stands up on EKS or GKE from one Terraform codebase. [Code](https://github.com/AMR5210/MBTALive) · [Demo](https://github.com/user-attachments/assets/38673945-1b2a-4e52-8bb4-25d283beaccc)
- **WatchGPT**: Photo analysis and streamed chat on Apple Watch, behind a Go backend with Cognito auth, Redis caching, SSE streaming, and circuit breaking on EKS. [Code](https://github.com/AMR5210/watchgpt) · [Demo](https://github.com/user-attachments/assets/ef333493-b819-4e40-bcf7-6009dd02c78f)
- **Orbital Threat Assessment**: ML pipeline for hazardous-asteroid detection over 958K NASA JPL records, reaching 0.99 PR-AUC on a 449:1 imbalanced held-out set. [Code](https://github.com/AMR5210/orbital-threat-assessment) · [Notebook](https://github.com/AMR5210/orbital-threat-assessment/blob/main/Project_codeFile.ipynb)

---

### Open source contributions

- <img src="https://avatars.githubusercontent.com/u/6154722?s=48" height="14" alt="Microsoft" title="Microsoft"/> **microsoft/typescript-go**: Fixed a false TS1293 on destructured `require` under `--module preserve` by exempting binding elements from the ESM syntax check. [PR #4800](https://github.com/microsoft/typescript-go/pull/4800)
- <img src="https://cdn.simpleicons.org/google" height="14" alt="Google" title="Google"/> **google/tunix**: Fixed a TOCTOU race condition. [PR #1627](https://github.com/google/tunix/pull/1627)
- <img src="https://cdn.simpleicons.org/pytorch" height="14" alt="PyTorch" title="PyTorch"/> **pytorch/pytorch**: Fixed stale 404 documentation links flagged by the nightly URL lint job. [PR #189619](https://github.com/pytorch/pytorch/pull/189619)
- <img src="https://cdn.simpleicons.org/arm" height="14" alt="Arm" title="Arm"/> **ARM-software/ComputeLibrary**: Replaced `std::deque` with `std::vector` in the HeuristicTree BFS to clear a GCC 14 `-Wstrict-overflow` build failure. [PR #1304](https://github.com/ARM-software/ComputeLibrary/pull/1304)

---

### Languages
[![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)]()
[![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)]()
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)]()
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)]()
[![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)]()
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)]()
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)]()
### Cloud & Infrastructure
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)]()
[![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)]()
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)]()
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)]()
[![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)]()
[![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white)]()
[![KEDA](https://img.shields.io/badge/KEDA-326CE5?style=for-the-badge&logo=keda&logoColor=white)]()
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)]()
### Frontend
[![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=for-the-badge&logo=swift&logoColor=white)]()
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)]()
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)]()
[![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)]()
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)]()
### Systems & Performance
[![Arm NEON Intrinsics](https://img.shields.io/badge/Arm_NEON_Intrinsics-0091BD?style=for-the-badge&logo=arm&logoColor=white)]()
[![Binary Protocol Design](https://img.shields.io/badge/Binary_Protocol_Design-37474F?style=for-the-badge)]()
[![Android/Termux Source Builds](https://img.shields.io/badge/Android%2FTermux_Source_Builds-3DDC84?style=for-the-badge&logo=android&logoColor=black)]()
### Machine Learning
[![llama.cpp](https://img.shields.io/badge/llama.cpp-000000?style=for-the-badge)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)]()
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)]()
[![Hugging Face Transformers](https://img.shields.io/badge/Hugging_Face_Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)]()
[![Quantization](https://img.shields.io/badge/Quantization_(QAT_%2F_PTQ)-6E44FF?style=for-the-badge)]()
[![Knowledge Distillation](https://img.shields.io/badge/Knowledge_Distillation_(CAKLD)-4C1D95?style=for-the-badge)]()
[![MI300X ROCm](https://img.shields.io/badge/MI300X_ROCm-ED1C24?style=for-the-badge&logo=amd&logoColor=white)]()
### Backend
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)]()
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)]()
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)]()
### Data & Messaging
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)]()
[![TimescaleDB](https://img.shields.io/badge/TimescaleDB-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)]()
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)]()
[![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)]()
[![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white)]()
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)]()
### Observability
[![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white)]()
[![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)]()
[![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)]()
### CI/CD
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)]()
---

### Patents

- **A system and method for optimizing Bill of Material cost and power performance for Drones**: co-inventor, IN Patent 582,124 (2026)
- **A system and method for optimizing Bill of Material cost and power performance of Graphics Processing Unit (GPU) core**: co-inventor, IN Patent 537,663 (2024) · [Certificate](https://iprsearch.ipindia.gov.in/RQStatus/PatentCertificatePDF.aspx?AppNo=MjAyMzQxMDQ0MDc4&FullPath=LSBDZXJ0aWZpY2F0ZSBvZiBJbnZlbnRvcnNoaXAtMDQ0MDAwMTQ3KCAyOC0wMS0yMDI1ICkucGRm)

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=AMR5210&label=Profile%20views&color=6f42c1&style=flat" alt="Profile views" />
</p>
