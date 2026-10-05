## Alex Isaev

Software engineer in Rishon LeZion, Israel: backend, infrastructure and security. Ex-NVIDIA intern.

I build systems that run without supervision: a brief in, a production deployment out, every layer in between mine. Python back ends (Django, FastAPI, Celery, Channels), Docker, PostgreSQL and Redis, self-hosted LLM services with evaluation harnesses, and security from both sides: penetration tests, and systems built so that tampering shows.

[LinkedIn](https://www.linkedin.com/in/isaev4lex) · [isaev4lex@proton.me](mailto:isaev4lex@proton.me) · Russian, English, Hebrew

### Public projects

| Project | What it is |
|---|---|
| [jarvis](https://github.com/isaev4lex/jarvis) | Self-hosted voice assistant for Apple Silicon: local speech recognition, LLM and text-to-speech, an async Django backend, and a closed action contract that the Mac re-checks before anything runs. |
| [tamrur](https://github.com/isaev4lex/tamrur) | Offline iPhone app for the Israeli driving theory exam (SwiftUI, Swift 6), built from open government data by a tested Python pipeline that identifies road signs with perceptual hashing and OCR. |
| [blinkdates-case-study](https://github.com/isaev4lex/blinkdates-case-study) | Case study of my creator platform, co-owned and closed source: per-minute WebRTC call billing on a signed, append-only ledger, and a media pipeline built for one server. |
| [studio-platform-case-study](https://github.com/isaev4lex/studio-platform-case-study) | Case study of a freelance platform for a yoga school: Hebrew right-to-left site, a CMS run from a phone, signed private video, live classes from a browser with no media server. |
| [devsecops-lab](https://github.com/isaev4lex/devsecops-lab) | Container supply-chain pipeline: Trivy scan of the exact image bytes, Syft SBOM, a gate with expiring waivers, verified publish, SARIF in code scanning. |
| [encrypt-tool](https://github.com/isaev4lex/encrypt-tool) | C++17 file encryption CLI: scrypt and chunked AES-256-GCM, atomic writes, migration from the old format, tested under sanitizers on Linux and macOS. |

### Why most of my code is not here

Since February 2023 I have worked at NextGen Solutions. Everything I write there belongs to the company and stays private, so none of it is on this page. In outline: the control plane for a farm of 16 ARM boards hosting up to 105 cloud Android devices (1,959 tests), a self-hosted LLM service that answers in 18 languages, a speech-to-text service on Whisper, a container-per-watch monitoring service on the Docker SDK, and the company's external penetration test.

The same applies to client work. From 2020 to 2022 I wrote 10 websites by hand, most of them on Django, for businesses in Tashkent; their code contains client content and is private. BlinkDates is a commercial product I co-own with a partner, so it is published as a case study rather than as source.

What is public here is code I own outright, plus case studies that describe private systems without their source. I am glad to walk through any of it in an interview.

### How I work

An AI coding agent types most of the code. I decide what gets built, what must never break, and what has to be true before a release ships. Every task starts from a written specification with its security constraints and acceptance checks. Releases are gated on the full test suite in a throwaway container, a check in a real browser, and a separate adversarial review of anything that moves money or grants access. Secrets, payments and production deploys stay with me.

Everything I wrote between 2020 and 2022 was written by hand, before such tools existed.

### Stack

- **Backend:** Python (Django, DRF, Channels, FastAPI, Celery), PostgreSQL, MongoDB, Redis, REST and WebSocket APIs, C++
- **AI and media:** self-hosted LLMs (Ollama, Qwen3), evaluation harnesses, Whisper, FFmpeg, Playwright
- **Frontend and real time:** React, TypeScript, Tailwind CSS, WebRTC, SwiftUI
- **Infrastructure:** Docker Compose and the Docker SDK, nginx, Linux, Cloudflare, MinIO, GitHub Actions, Jenkins
- **Security:** OWASP Top 10 review, black-box and internal penetration testing, CSP, encryption at rest

### Certificates

| Certificate | Year | Scan |
|---|---|---|
| Cybersecurity Specialist, Israel Professional College | 2025 | [view](Certificates/0.%20Main%20certs/2.%20IPC_cyber.jpg) |
| Artificial Intelligence, Israel Professional College | 2025 | [view](Certificates/0.%20Main%20certs/3.%20IPC_AI.jpg) |
| Cybersecurity Specialist from Scratch, Netology (389 hours) | 2024 | [diploma](Certificates/0.%20Main%20certs/1.%20Netology_cyber.jpg) · [modules](Certificates/2.%20Netology%20cyber) |
| C++ developer track, Netology (7 modules) | 2024–2025 | [modules](Certificates/3.%20Netology%20CPP) |
| Information Security and Data Privacy training, NVIDIA | 2022 | [1](Certificates/1.%20Nvidia/1.%20Cybersecurity%20and%20Data%20Privacy%20at%20NVIDIA%20certficate.jpg) · [2](Certificates/1.%20Nvidia/2.%20Information%20Security%20at%20NVIDIA%20certificate.jpg) |
| Java program and NVIDIA internship, MASA Tlalim (420 hours) | 2022 | [internship](Certificates/4.%20Other%20Certs/1.%20Internship%20MASA.jpg) · [course](Certificates/4.%20Other%20Certs/2.%20MASA-1.jpg) · [diploma](Certificates/4.%20Other%20Certs/3.%20MASA-2.jpg) |
| Hebrew, Ulpan Aleph, Ministry of Aliyah exam (grade 94) | 2024 | [course](Certificates/4.%20Other%20Certs/4.%20Ulpan-1.jpg) · [exam](Certificates/4.%20Other%20Certs/5.%20Ulpan-2.jpg) |
